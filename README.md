# LearningBlender
Going through tutorials to learn blender

## cheats

* g - "grab" to translate
* g->x - "grab" and translate in x direction
* g->y - "grab" and translate in y direction
* g->z - "grab" and translate in z direction
* r - "rotate"
* alt+g - remove "grab".. 0 out translations
* alt+r - remove "rotate"
* selections
  * 1 - vertices
  * 2 - edges
    * alt+left click will select "edge loops"
  * 3 - faces
  * a - select entire object being edited
* line select: first, have a vertex selected. then select another vertex while holding cmd and it will select all vertices between them in the sortest path
* num pad
  * 5 - change between perspective and orthographic
  * 1 - front view (-y)
  * 3 - side view (+x)
  * 7 - top view (+z)
  * cmd+4 - step viewport left
  * cmd+2 - step viewport down
  * cmd+6 - step viewport right
  * cmd+8 - step viewport up
* working with faces
  * e - "extrude".. basically, make another box that comes off of the current face
  * i - "inset".. basically, splits the current face to have another inside
  * i->b "inset on boundry".. splits the current face but on the boundry
* beveling edge: go to edge mode, cmd+b and slide. mouse wheel up for more splits
* beveling vertex: got to vertex mode, cmd+shift+b and slide. 
* cutting: cmd+r (loop cut). This will try to cut down the middle of quads that loop around a model
  * increase cuts with scroll wheel
  * left click to set once desired amount of cuts
  * right click to have no movement on lines, or move mouse around and left click once in desired place
* cmd+x - disolve selected, without destroying the mesh
* alt+z - toggle x-ray mode
* shift+d - duplicate object
* shift+MMB - pan viewport
* cmd+l - link objects. this allows you to link different modifier/attributes between objects
* k for knife tool. 
* j for joining vertices

* joining objects: 
  * select all objects to join
  * ensure there is an "active" object (highlighted in yellow). this will be the object everything will join to
  * cmd+j: this is the join command

* randomizing
  * select vertices you want to randomize
  * in edit mode
  * select "Mesh" drop down
  * select "Transform" option
  * select "Randomize"

* deforming objects
  * these are ways to can transform and entire object

* render movie basics
  * go to output in properties window
  * output section
  * set output location
  * File Format = FFmpeg Video
  * in Encoding section, Container = MPEG-4
  * in Video section, Output Qualityy = Perceptually Lossless, Encoding Speed = Slowest
  * cmd+F12

* cmd+p to parent one object to another 

* inverse kenimetics
  * make a target and pole bone that do not deform, are not parented, and are:
    * "pole" is where the IK will be pulled to
    * "target" is the end? I think? put this on the last bone of IK
  * on the ending bone that deforms, add the IK modifier on the bone

* attaching bones to mesh
  * for entire mesh: select the mesh to attach, then the armature, then cmd+p and parent with automatic weights
  * for single bone: go into edit mode and select just the single bone you need to attach. Then, object mode, select the mesh and then the armeture, and press cmd+p, but select "bone". blender will remember the bone that is last selected.

* to paint weights on the mesh for armetures, first select the armeture, then the mesh to paint, then go into "weight paint" mode
  * alt+click will allow you to select different bones


## 01-LowPolySword
https://www.youtube.com/watch?v=lgJaWqIYeKM

## 02-LowPolyWell
https://www.youtube.com/playlist?list=PLn3ukorJv4vvMwZPLzlajVII2zJd-_BM-

the hdri is from https://polyhaven.com/a/table_mountain_2_puresky

poly haven is a fantastic resource


## 03-LightHouse

following a tutorial from https://www.gamedev.tv/courses/complete-blender-creator


## 04-ModularDungeon

following a tutorial from https://www.gamedev.tv/courses/complete-blender-creator


## 05-ModularDungeon

following a tutorial from https://www.gamedev.tv/courses/complete-blender-creator


## 06-AnimationBasics

face movie from: https://www.pexels.com/video/abstract-video-4990242/

following a tutorial from https://www.gamedev.tv/courses/complete-blender-creator
