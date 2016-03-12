===========================
Sketch.js
===========================

------------
API Overview
------------

*Prototypes*

Sketch_

Sketch2D_ //to be obsolete

Picture_ //probably will go away

FreehandSketch_ //is inside of Sketch


******
Sketch
******

The sketch class is an object, with functions:

* xyzs() //what does S mean? does it return the Z paramater or 1?
* adjustD() //adjust depth? returns depth or z times depth
* adjustX() //returns either x or z times x + x ===== X is the dimension of what? the clipspace?
* adjustY()
* adjustXY() //why does it just return [x, y]?
* unadjustD() //what does it mean? multiplying d by the inverse?
* unadjustX()
* unadjustY()
* unadjustXY()
* arrowBegin() //pushes x y coordinates onto the arrow stack and a null z position
* arrowDrag() //what are we doing to the last point of the arrows array?
* arrowEnd() //What is the difference between sketchpage and sketchbook (sketchbook is the collection of sketchpages)? and why is the second column of arrows a sketch?
* arrowFade() //what is an arrow?
* arrowRemove()
* fade() //start fading
* fadeAlpha() //returns the value of the current fade
* upload() //uploads a file to the server
* computeStrokesBounds() //populates _S with the curve bounds of each sketchTrace, whatever all these things are
* drawStretchValues() //getting the scaling (stretching) and then drawing that value to the screen, either in 'value' (-1, 1) or in pixels
  * valueToPixels()
  * pixelsToValue()
* is3DSketch() //returns whether it is a 3D sketch or not
* isGlyph() //so if there is no _S, then returns true? it wants to make sure that this._S is not null, but strictly undefined
* isOnScreen() //checking if it is within the clipspace
* model() //if the model doesnt exist, it creates a new model, sets the sketch to it //is the model a scene? //you load the model
* modelBeginFrame() //magic number on line 266 //set up all the model parameters
* modelEndFrame() //actually draw the model
* setColorId()
* setRenderMatrix()
* toFreehandSketch()
* transformX2D()
* transformY2D()
* untransformX2D()
* untransformY2D()
* duringSketch()
* afterSketch()
* computeCursorPoint()
* doSwipe()
* extendBounds()
* clearPorts()
* addPort()
* setPortLocation()
* clone()
* computePixelSize()
* contains()
* cx()
* cy()
* delete()
* deleteChar()
* drawBounds()
* drawLabel()
* drawValue()
* drawText()
* evalCode()
* findInLink()
* getAlpha()
* getDefaultFloat()
* getDefaultValue()
* getInFloat()
* getInIndex()
* getInValue()
* getInValueOf()
* getPortIndex()
* getLabel()
* hasBounds()
* hasPortBounds
* insertText()
* intersectingSketches()
* intersects()
* isAfterSketch()
* isDefaultValue()
* isInValue()
* isInValueAt()
* isNullText()
* isParsed()
* isSimple()
* m2s()
* m2x()
* m2y()
* mScale() //scale a fraction in relation to the sketch
* moveCursor()
* moveLine()
* offsetSelection()
* portXY()
* lastStrokeSize()
* indexOfLastStroke()
* pixelToPoint()
* pointToPixel()
* removeLastStroke()
* renderWrapper()
* scale() //internal routine that should be hidden to the user
* outPortIndex()
* recenter3DSketch()
* setOutPortValue()
* setOutValue()
* setSelection()
* selectionWeight()
* setDefaultValue()
* setSketchText()
* setTextCursor()
* sketchTextsMouseDown()
* sketchTextsMouseDrag()
* sketchTextsMouseUp()
* onRotate()
* updateSelectionWeights()
* setText()
* setUniform()
* standardView()
* standardViewInverse()
* toPixel()
* toTrace()
* translate()
* tx()
* ty()
* useInputColors()
* xform()
* xformInverse()
* makeXform()
* enableFragmentShaderEditing()
* _updateMesh()
* renderStrokeInit()
* renderStrokeSetColor()
* renderStroke()
* drawTransform()
* morphToGlyphSketch()


********
Sketch2D
********

* sketch2D()


*******
Picture
*******


**************
FreehandSketch
**************
