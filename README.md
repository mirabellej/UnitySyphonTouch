# UnitySyphonTouch
GLSL texture sharing between Touchdesigner and Unity using Syphon / KlakSyphon

Allows for GLSL texture sharing between TouchDesigner and Unity using KlakSyphon. 

Instructons for use: 
1. Download KlakSyphon at: https://github.com/keijiro/KlakSyphon
2. Drag Unity client from this repo into the KlakSyphon Assets folder.
3. Open TouchDesigner. Make certain your webcam is streaming by selecting the correct video input in the VideoDeviceIn TOP. 
4. Open the Unity project. Texture sharing should occur automatically. If not, check that the video stream is working in TouchDesigner and that the client and server have the same name (in this case TouchDesigner). 

To use something other than a video stream, attach a shader, Movie File Out TOP, Ramp TOP to the Syphon Out TOP. 
