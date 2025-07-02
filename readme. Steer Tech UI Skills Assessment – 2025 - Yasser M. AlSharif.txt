Steer Tech UI Skills Assessment – 2025

Project Title: Intro to Unity UI

This Unity project was created as part of the Steer Elite Internship Program's Tech UI Skills Assessment (2025 Cohort)

The goal of the project is to replicate a given UI layout using Unity’s built-in UI system — focusing on interaction, animation, responsiveness, and layout quality etc...

----------

Features Implemented

UI Layout:

- Three buttons created and organized using a *Vertical Layout Group* inside a `ButtonGroup` container:
  - Play
  - Settings
  - Quit
- Buttons are fully responsive and adapt cleanly to *portrait and landscape modes* using:
  - Anchors
  - `Canvas Scaler` (`Scale With Screen Size`)
  - `Content Size Fitter`
  - `Vertical Layout Group`

----------

Hover Interaction:

- Each button has a *hover effect*:
  - A *hand image* appears on hover or touch
  - Buttons are outlined with a highlight color
- Custom `ButtonHoverHandler.cs` script handles `OnPointerEnter` and `OnPointerExit`

----------

Idle Animation:

- The UI title element (Unity UI sign) features a **looping idle animation** using Unity’s Animator
  - The animation causes a slight floating motion to make the UI feel alive and dynamic

----------

Responsive Design:

- UI layout adjusts automatically based on screen size or orientation
- Buttons remain centered and properly spaced across various aspect ratios
- *Safe Area awareness* is implemented (for devices with camera notches) using a custom `SafeAreaController.cs`

----------

Technical Summary:

| Element | Description |
|--------|-------------|
| Engine | Unity 2022+ (2D Template, Built-in Renderer) |
| UI Framework | Unity UI (UGUI) only – no UI Toolkit or IMGUI |
| Tools Used | Animator, Layout Groups, EventSystem, C# Scripts |
| Platform Tested | iPad Pro Simulator, 1080x1920 Portrait, 1920x1080 Landscape |

----------

Files Included

- `/Assets/Scenes/SampleScene.unity`
- `/Scripts/ButtonHoverHandler.cs`
- `/Scripts/SafeAreaController.cs`
- `/Animations/IdleAnimation.controller`
- All related images, fonts, and layout prefabs

----------

How to Run the Project:

1. Open the project in Unity 2022.3 or newer
2. Open the scene: `Assets/Scenes/SampleScene.unity`
3. Press **Play**.
4. Hover over or tap the buttons to see interactions
5. Resize or rotate the Game view to observe responsive layout behavior

----------


Scrolling Background (RawImage):

- A *RawImage with a repeated texture* is used to simulate a scrolling background (e.g., sky or water)
- This gives the UI a sense of movement and life, enhancing the aesthetic of the main menu
- Scrolling is handled via script by adjusting the `UV Rect` of the `RawImage`, allowing smooth infinite scroll without the need for animating large images

----------

Created By:

*Yasser Mohammed Musaid AlSharif* 
Submission for: *Steer Elite Internship Program 2025* – Tech UI Track  
Email: [Yasset965@gmail.com](mailto:Yasset965@gmail.com)

---

Thank you for reviewing my project!
