# AnimationGenerator
Satellite animation generator with randomized position, orientation, textures, etc.

## Parameters
- Start Frame: starting frame for animation
- End Frame: last frame to render
- Frame Step: desired steps between each interval
- Model ID: various textures, materials, and patterns
- Current Models: list of all comleted models

## Consistency with OpenCV
The generated animation also returns translation and rotation coordinates in a rotation matrix. Converting the euler angles specified in Blender to a rotation matrix and flipping the y and z-axes makes sure the model is consistent with the OpenCV cooordinate system. 

![](SatGif.gif)
