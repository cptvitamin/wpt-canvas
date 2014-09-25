wpt-canvas
==========

The W3C web platform tests mirror system is currently down, which prevents us from reviewing tests internally using the wpt-runner system without everyone checking out my PR and running wpt-runner locally.  I will post static versions of the tests here for review by the Canvas TF before we request they be merged with web-platform-tests.

Many of these tests are currently -manual.  Some may be converted to automated tests (anything that doesn't have to do with AAPI verification).  However, the automated tests are a little more difficult to review.  Once we agree the test is sound, we can convert them.

This effort is being organized by the Canvas TF here: http://www.w3.org/wiki/HTML/Canvas_Task_Force/CR-Test

* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/2d.drawFocusIfNeeded.defaultpathcompositing-manual.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/2d.drawFocusIfNeeded.defaultpathdescendenthasfocus-manual.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/2d.drawFocusIfNeeded.defaultpathhasfocus-manual.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/2d.drawFocusIfNeeded.defaultpathhasfocusclipping-manual.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/2d.drawFocusIfNeeded.defaultpathhighcontrast-manual.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/2d.drawFocusIfNeeded.nofocusnotdescendent-manual.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/2d.drawFocusIfNeeded.zerosubpaths-manual.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/canvas_focus_drawCustomFocusRing_001.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/canvas_focus_drawFocusIfNeeded_AAPI_001-manual.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/drawFocusIfNeeded_001.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/drawFocusIfNeeded_002.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/drawFocusIfNeeded_003.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/drawFocusIfNeeded_004.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/drawing-paths-to-the-canvas/drawFocusIfNeeded_005.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/hit-regions/addHitRegion.IDNotNullNewHitRegion-manual.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/hit-regions/addHitRegion.IDNotNullPreviousHitRegion-manual.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/hit-regions/addHitRegion.emptyIDPath-manual.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/hit-regions/addHitRegion.nullIDControl-manual.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/hit-regions/addHitRegion.nullpathvalidID.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/hit-regions/addHitRegions-NotSupportedError-01.html
* http://cptvitamin.github.io/wpt-canvas/2dcontext/hit-regions/hitregions-members-exist.html
