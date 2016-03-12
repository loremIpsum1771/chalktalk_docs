======================
g.js
======================

------------
API Overview
------------

Global Namespace for Graphics Context


******************************
G - Refers to Chalktalk Object
******************************

g.js offers helper functions:

* FakeContext() is a class used when we don't want to render a frame
* S(i) //???
* stretch(name, value)

****************
global variables
****************

* arrowNearCursor
* backgroundColor
* bgClickCount
* bgClickX
* bgClickY
* viewForwardMat
* viewInverseMat
* defaultFont
* defaultPenColor
* glyphTrace
* preglyphSketch
* isAltKeyCopySketchEnabled
* isAltPressed
* isCasualFont
* isCatchingRenderExceptions
* isDrawingSketch
* isFinishedLoadingSketches
* isFog
* isMouseOverBackground
* isOverviewMode
* isScreenView
* isShowingToolTips
* isShowingPresenterView
* isTelegraphKeyPressed
* isTextMode
* isTouchDevice
* isTutorialMode
* margin
* meshOpacityOverVideo
* overview_alpha
* sketchPadding
* sketchTypeLabels
* sketchTypes
* sketchTypesToAdd
* videoBrightness
* xmlWriteEnabled

*  sketchActionEnd()

FUNCTIONS

* moveWand()
* width()
* height()
* clickSize()
* sfs()
* sfpx()
* scrimColor()
* fadedColor()
* fadedRGB()
* overlayScrimColor()
* overlayFadedColor()
* bgScrimColor()
* panX()
* panY()
* initEventHandlers()
 * touchResponse()
 * enableTouchEvents()
* lineWidth()
* _g_beginPath()
* _g_fill()
* _g_lineTo()
* _g_moveTo()
* _g_stroke()
* _g_text()
* _g_sketchTo()
* resampleTrace()
* buildTrace()
* isVideoLayer()
* meshOpacity()
* addSketchType()
* loadSketches()
* addTypeNameToSketchCode()
* importSketch()
* onRemoteSketchesFinishedLoading()
* gStart()
* e2s()
* This()
* startCanvas()
* addSketchOfType()
* sketchTypeToCode()
* registerSketch()
* sg()
* computeLinkCurvature()
* drawPortData()
* drawPossibleLink()
* findOutSketchAndPort()
* findNearestOutPort()
* findNearestInPort()
* findNearestPortAtCursor()
* findOutPortAtCursor()
* isFreehandSketch()
* finishDrawingUnfinishedSketch()
* finishSketch()
* isFinishedDrawing()
* isFinishedDrawing()
* isMouseNearCurve()
* setTextMode()
* toggleTextMode()
* findGlyph()
* strokesComputeBounds()
* strokesNormalize()
* unregisterGlyph()
* registerGlyph()
* shift()
* glyphIndex()
* addGlyph()
* bgActionDown()
* bgActionDrag()
* bgActionUp()
* bgDragGesture()
* bgUpGesture()
* bgClickGesture()
* bgDragGestures = []
* startSketchDragAction()
* doSketchDragAction()
* endSketchDragAction()
* assignCollection()
* unassignCollection()
* addCollectionGlyph()
* sketchClickActionName()
* doSketchClickAction()
* isHover()
* isk()
* nsk()
* sk
* dsk()
* clear()
* image()
* annotateStart()
* annotateEnd()
* ttTick()
* tryToSelectSketchAtCursor()
* createArrowCurve()
* ttUpdate()
* tick()
* isSketchInProgress()
* isShowingOverlay()
* fillPath()
* fadeArrowsIntoSketch()
* deleteSketch()
* selectSketch()
* copySketch()
* addSketch()
* computeCentroid()
* drawCrosshair()
* GeometrySketch()
* addPlaneShaderSketch()
* addSphereShaderSketch()
* addTorusShaderSketch()
* createMesh()
* addGeometryShaderSketch()
* computePreglyphSketchBounds()
* geometrySketch()
* SketchTo3D()
* setMeshUpdateFunction()
* bgMaterial()
* penMaterial()
* setPage()
* insertTemplate()
* resizePadding()
* row()
* column()
* content()
* textElement()
* imageElement()
* videoElement()
* loadGlyphArray()
* unloadGlyphArray()
