# Scenes
![image](https://i.pinimg.com/1200x/7b/b7/1f/7bb71f40607d6cbd7267af14fc039c4e.jpg)
![image](https://i.pinimg.com/736x/fd/62/8e/fd628e190b0208d769beaa442e2bccf0.jpg)

Animate people in real-time in a rendered scene

## The idea
| Element | Source/Method | Engine Configuration |
| ------- | ------------- | -------------------- |
| Buildings (Cityscape) | Photogrammetry or Manual 3D Models | Flat Shading + Outline Shader applied to all meshes
| People (Visitors) | Real-Time Segmentation Mask | Cutout Material (solid color fill using the mask as alpha)
| Perspective | Engine Camera/Projection Setup | Calibrate the virtual camera to match the real-world projector's view, ensuring the projected scene aligns with the real ground/walls