Babylon JS Material Editor v 1.0 beta
================================

An AngularJS based typescript project for real-time in browser material editing using BabylonJS (http://babylonjs.com)
This is the first release of the material editor, with a simple UI using twitter's bootstrap.

Demo
-------

http://materialeditor.raananweber.com/

About the code
----------
The typescript files are located at MaterialEditor.

Vendor contains external libraries which I used:
* BabylonJS https://github.com/BabylonJS/Babylon.js
* Angular Color Picker https://github.com/buberdds/angular-bootstrap-colorpicker
* Angular Slider directive https://github.com/PopSugar/angular-slider

application.js is a rendered javascript from the typescript source. Generated by Visual Studio 2013.

Roadmap V.1
----------------------
* ~~Exporting the material as javascript / babylonjs material~~ - Done
* ~~Allow uploading the canvas images to a server~~ - Done (No CubeTexture Support at the moment)
* ~~New UI~~ - Done
* ~~Change light properties~~ - Done
* ~~Adaptation to BabylonJS 2.0~~ - Done
* ~~Upload your own object~~ - Done
* ~~Multimaterial support~~ - Done
* ~~Supporting further types of textures (like mirror)~~ - Done : Mirror supported.
* ~~Support cube projection for reflections~~ - Done

Roadmap V.2
--------------------------
* Video support
* Shaders / Effects
* ~~Displacement maps~~ - Possible but will not be done at the moment. This is actually a change of the geometry. Maybe in future versions.


MIT License
------------------

http://raananw.mit-license.org/
