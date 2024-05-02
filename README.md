Research Overview:
---------------------------------------
This research explores user interaction with a mixture of physical and virtual objects in an augmented reality environment, specifically tailored for outdoor settings. The primary aim is to assess whether individuals pay more attention to virtual objects compared to physical ones. By integrating innovative AR technology with traditional environmental cues, the study offers novel insights into human perceptual habits and cognitive processing in mixed realities.

Experimental Design 
--------------------------------------------
The experimental setup includes four separate trials: one dedicated to learning and three for evaluation. Following each trial, a resetting phase is implemented to guarantee that participants begin each segment under uniform conditions. Additionally, the experiment features two types of landmarks: one virtual and one physical, present in the real-world environment. Both the target elements which participant need to memorize are designed to be virtual and physical in outdoor environment.

Learning Trial:
During the learning trial, participants are introduced to the real environment where all landmarks are visible. They commenced the learning phase from a starting location randomly selected to be midway along and aligned with each side of the square. If visualized within a square, these starting positions would be located at the midpoint of each edge of the square. Here, they are tasked with locating and memorizing the position of a yellow post, the target, which is clearly marked and visible. Participants navigate to this post and take the time to observe and memorize its location in relation to the landmarks.

Resetting Procedure:
After the learning trial, participants undergo a resetting procedure to clear the previous spatial setup and prepare them for the testing phase. This procedure involves the participants walking to a blue post, turning to face a red post, and pressing a button on the controller.(we are using hand or voice ). This process serves to reorient the participants within the AR tracking space and ensure that any learning from the previous trial does not directly influence their performance in the subsequent trial.

Testing Trials:
The testing trials consist of three separate tests, each beginning with the resetting procedure. In these trials, participants start the test phase at one of the remaining three starting locations ( if participants started at the southern starting location during the learning phase, they could only start at the east, west, or north locations during the test phase), which was chosen randomly. The goal is to navigate to where they remember the yellow post was, despite it not being visible. Different conditions are applied across the testing trials.


Experimental Design:
------------------
Dependent Variables
Error rates in locating targets
Time taken to complete tasks

Independent Variable
Types of cues (Physical, Virtual, Combined)

Participants' interactions are meticulously logged, and their gaze data collected through AR devices, providing valuable insights into their focus and engagement levels with different types of objects. These insights are crucial for advancing our understanding of augmented reality applications in real-world environments.
How to Run:
----------------------------
Prerequisites
Microsoft HoloLens or compatible AR headset
Appropriate AR software and tracking setups

Setup:
---------------------------

1.2. Open Unity Hub and click on  the "Add" button.

3. Browse to the cloned repository folder and select the Unity project folder.

4. Click on the project in Unity Hub to open it in Unity Editor.

5. In Unity Editor, go to Window -> Package Manager.

2. Install the following packages:
- Microsoft Mixed Reality Toolkit Foundation (version 2.7.3 or later)
- Microsoft Mixed Reality OpenXR Plugin (version 1.4.1 or later)
- TextMeshPro (version 3.0.6 or later)
- Unity XR Interaction Toolkit (version 2.1.1 or later)
- Unity XR Plugin Management (version 4.2.1 or later)

7. Go to Mixed Reality -> Toolkit -> Utilities -> Configure Project for MRTK.

8. In the MRTK Project Configurator window, click on the "Apply" button to configure the project for MRTK.

9. Go to Edit -> Project Settings -> XR Plug-in Management.

10. Enable "OpenXR" and click on the "Install" button if prompted.

11. Go to Edit -> Project Settings -> Player.

12. In the Player Settings window, go to the "Publishing Settings" section and enable "InternetClient" and "Microphone" capabilities.

13. Connect your HoloLens 2 device or start the HoloLens 2 Emulator.

14. In Unity Editor, go to File -> Build Settings.

15. Select "Universal Windows Platform" as the platform and click on the "Switch Platform" button.

16. Configure the build settings as follows:
 - Target Device: HoloLens
 - Architecture: ARM64
 - Build Type: D3D Project
 - Target SDK Version: Latest installed
 - Minimum Platform Version: 10.0.18362.0
 - Visual Studio Version: Latest installed
 - Build and Run on: USB Device or Emulator (depending on your setup)

17. Click on the "Build" button and choose a folder to save the Visual Studio solution.

18. Open the generated Visual Studio solution file.

19. In Visual Studio, change the build configuration to "Release" and the platform to "ARM64".

20. Right-click on the project in the Solution Explorer and select "Deploy".

21. Wait for the deployment process to complete. The application will be installed on your HoloLens device or emulator.

## Dependencies

The project relies on the following dependencies:

- Microsoft Mixed Reality Toolkit (MRTK) - Provides a set of components and features for mixed reality development.
- TextMeshPro - Used for advanced text rendering and formatting.
- Unity XR Interaction Toolkit - Provides a framework for XR interactions and input handling.
- Microsoft Azure Spatial Anchors SDK - Allows for creating and managing spatial anchors.
- Unity XR Plugin Management - Manages XR plug-ins and their settings.

## Troubleshooting

If you encounter any issues during the setup or deployment process, try the following:

- Ensure that you have the latest versions of Unity, Visual Studio, and the required SDKs installed.
- Double-check that you have installed all the necessary packages and dependencies.
- Verify that your HoloLens device is properly connected or the emulator is running correctly.
- Check the Unity Console and Visual Studio Output window for any error messages or logs.
- Refer to the MRTK documentation and Unity forums for additional troubleshooting steps specific to your issue.


## Acknowledgements

- [Microsoft Mixed Reality Toolkit (MRTK)](https://github.com/microsoft/MixedRealityToolkit-Unity)
- [TextMeshPro](https://docs.unity3d.com/Manual/com.unity.textmeshpro.html)
- [Unity XR Interaction Toolkit](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@2.1/manual/index.html)
- [Microsoft Azure Spatial Anchors](https://docs.microsoft.com/en-us/azure/spatial-anchors/)



