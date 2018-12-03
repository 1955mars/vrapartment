# Build an Apartment
Starter project for the Udacity [VR Developer Nanodegree](http://udacity.com/vr) program.

- Course: VR Scenes & Objects
- Project: Build an Apartment


### Versions Used
- [Unity LTS Release 2017.4.4f1](https://unity3d.com/unity/qa/lts-releases?version=2017.4)
- [GVR SDK for Unity v1.100.1](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.100.1)


### Directory Structure
- The Unity project is the child directory of the repository and named according to the associated lesson.
- The Unity project is 'cleaned' and includes the `Assets` folder, the `ProjectSettings` folder, and the `UnityPackageManager` folder.


### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is included.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.100.1, make sure you accept any API update pop-up prompts triggered by Unity. Alternatively, you can manually run the API updater (Unity menu `Assets` > `Run API Updater...`) after the import has completed.


### Related Repositories
- [VR Scenes and Objects - Game Objects](https://github.com/udacity/VR-Scenes-and-Objects_Game-Objects/releases)
- [VR Scenes and Objects - Animations](https://github.com/udacity/VR-Scenes-and-Objects_Animations/releases)
- [VR Scenes and Objects - Cameras](https://github.com/udacity/VR-Scenes-and-Objects_Cameras/releases)
- [VR Scenes and Objects - Lights](https://github.com/udacity/VR-Scenes-and-Objects_Lights/releases)
- VR Scenes and Objects - Build an Apartment



### Tested Platforms
	- Android [Submitting the same build]


###My Feedback :)

I enjoyed this project very much for the reason that all the requirements made me to put the knowledge I gained into practice.
I spent close to a week on this working 1 to 2 hours each day. Listing out here the major things I have taken away

1) Coming up with a plan about the selection and placement of 3D objects took almost 50% of the overall time. This is the challenging part as I have to visualize the 3D space with objects before bringing them into it. Finally when I saw the apartment taking shape as per my design, I felt excited.

2) Selection of lights, color and their placement is the second major thing that I felt challenging as well as exciting. I understood the process of baking as lightmaps with much clarity.
I tried the baking with very low lightmap resolution, the lighting appeared to be very dull. When I increased to 40 and finally 80, the lighting appeared visually pleasing. When I turned on shadows for each light the objects appeared much realistic. 
