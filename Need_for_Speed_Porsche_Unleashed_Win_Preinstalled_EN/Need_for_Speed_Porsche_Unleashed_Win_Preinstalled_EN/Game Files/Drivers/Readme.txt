Widescreen Aspect Ratio Support for Need for Speed Porsche Unleashed
--------------------------------------------------------------------
This patch fixes the aspect ratio in Need for Speed Porsche Unleashed when
running the game in widescreen. By default, the game always assumes a 4:3 aspect
ratio and as such, on a widescreen monitor the game accordingly appears
horizontally stretched. With this patch, the game's graphics will be adjusted to
match the aspect ratio of the monitor (while interface elements will be left
as-is), thereby eliminating ridiculously wide cars and oval wheels. It's tested
with both the Direct3D 7 renderer as well as the game's Glide renderer (using
nGlide, http://www.zeus-software.com/downloads/nglide).

In addition, this patch (hopefully) fixes the notorious "Normandie crash" that
seemed somehow related to the game's lens flare effect and/or the rear view
mirror.

Installation
------------
- extract the contents of this archive into the `Drivers` subdirectory of your
  NFSPU installation directory
- install the *Microsoft Visual C++ 2013 x86 Redistributable* using the included
  `vcredist_x86.exe` installer
- enable the widescreen patch by double-clicking the
  `Enable Widescreen Renderer.reg` file (and confirming all prompts)
- (optionally) if you prefer to use the game's Voodoo renderer (with a Glide API
  wrapper), uncomment the `;driver=voodoo2` line in `porsche-widescreen.ini`,
  (so that it reads `driver=voodoo2`)

To disable the widescreen patch again, double-click one of the other
`Enable * Renderer.reg` files to switch back to that renderer.

Known Issues
------------
- When zooming into the car interior in the menus, there can be some visual
  glitches. These are purely cosmetic and the in-game interiors are fine.
- If the in-game resolution is set to 640x480, there might be some visual
  glitches in the game. They are very minor (and will disappear as soon as the
  rear view mirror and/or HUD map are visible) and do not happen on any other
  resolution.
- The "widescreening" effect is implemented by effectively stretching the image
  vertically, balancing the horizontal stretching of the wider screen. This
  stretching happens in a visually lossless fashion and properly ignores any
  2D interface elements, but it still means that compared to a 4:3 display, the
  top and lower parts of the 3D image will be cut off; the vertical field of
  view is effectively reduced, the wider the aspect ratio compared to 4:3, the
  more will be cut off. In my opinion, it's not a problem at common wide aspect
  ratios like 16:9, and from a quick check at 21:9, it was playable even at that
  aspect ratio.

Extra Configuration
-------------------
The most commonly necessary configuration option is the `driver` setting,
specifying the actual rendering backend to use. By default, the Direct3D 7
renderer is used since it requires no external dependencies, but switching to
using the Glide renderer is possible (and explained above).

In a few rare situations, it might be necessary to configure the target aspect
ratio manually, generally when the game is set up to not take up the full
(primary) monitor. For details, see the comments in the supplied
`porsche-widescreen.ini` configuration file.

Changelog
---------
* 1.0.1 (1024-12-10)
  - fix the in-game widescreen setting
* 1.0 (2014-07-12)
  - initial release
  - Note: this release doesn't use aggressive build optimisation settings to
    make crash memory dumps created from it more useful, meaning it has more of
    a performance impact than strictly necessary. It should still be negligible
    on any relevant system.

Building from Source
--------------------
The source can be found at https://bitbucket.org/fk/porsche-graphics-hacks.
Visual Studio 2013 Express (or up) is required. See the repository readme for
further information.

Legal
-----
This library (`porschewidescreenz.dll`) is Copyright (c) 2014 Felix Krull.

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.

*Microsoft Visual C++ 2013 x86 Redistributable* is a Microsoft product and is
included according to the "Distributable Code" terms of the Microsoft Software
License Terms for Visual Studio 2013.
