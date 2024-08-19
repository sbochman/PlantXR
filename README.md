# PlantXR 
PlantXR is a virtual and mixed-reality application for the Varjo XR-3 powered by Unity. This app contains a tutorial level, Sundial Garden VR scene, and Sundial Garden MR scene. 

The Sundial Garden tree layout is an optimised layout adhereing to several constraints such as minimum credit count of evergreen trees, spacing requirements, cost, and many more. The optimisation is done using the genetic algorithm, and the code can be found here: https://github.com/sbochman/PlantingOptimization


# Running This Application
To run, simply download and run the main application with a .exe file type. This project can also be downloaded and imported directly into Unity. To run, ensure that the Varjo plugin is set in the project manager, which can also be downloaded here: https://github.com/varjocom/VarjoUnityXRPlugin

Additionally, install the Ultraleap library here: https://github.com/ultraleap/UnityPlugin#Installation

The assets folder needs to have the LiDAR scan pasted in as well, which can be found at this link: https://drive.google.com/file/d/1EvGPU5wXKwfUozKjiJKoI5oGzM26CskS/view?usp=drive_link

# Dependencies
  * XR Plugin Management 4.5.0
  * XR Interaction Toolkin 2.5.4
  * Ultraleap Tracking 7.0.0
