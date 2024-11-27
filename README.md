Test the project :
- Launch the default scene when opening the project (LevelSelection)
- Choose the level of your choice with the buttons (functional with the controller and mouse)
- You will be taken to a test map, to return to the level choice : press Escape or the menu button on the controller to pause the game and display the pause menu (functional with the controller and mousse)


Where to find Blueprints :
- For the first person camera (Ghostrunner) : Content\FirstPerson\Blueprints
![Capture d’écran 2024-11-27 142259](https://github.com/user-attachments/assets/cbd74491-13c1-41ab-b581-3fab777db4be)
![Capture d’écran 2024-11-27 142131](https://github.com/user-attachments/assets/8ee09b9c-b57b-4741-b170-630d51fafc62)
- For the third person camera (Monster Hunter) : Content\MonsterHunterTPS\Blueprints
![Capture d’écran 2024-11-27 141554](https://github.com/user-attachments/assets/1ca1cba7-0fd0-4dfc-87ed-206efd188525)
- For the 2.5D camera (Chants of Sennaar) : Content\ChantsOfSennaar
In the BP_ThirdPersonCharacter, the logic for movement using the current BP_FixedCamera's vector

![Screenshot 2024-11-28 005207](https://github.com/user-attachments/assets/2e5bd928-6c23-466c-8d30-1b369a1afe1b)

In the BP_FixedCamera, the logic for detecting the player on overlap with a collider, and for setting this Camera as the nex ActiveCamera

![Screenshot 2024-11-28 005048](https://github.com/user-attachments/assets/7077dec9-5246-4c90-abc9-959b3a777cf1)
![Screenshot 2024-11-28 004956](https://github.com/user-attachments/assets/c23b10cc-71f8-4985-8dc8-4060a55f1386)

In the BP_FixedCamera, the logic for moving along a spline as the player moves between two specified points

![Screenshot 2024-11-28 004842](https://github.com/user-attachments/assets/57ecb972-c321-4fac-a22f-c976da2e57a6)
![Screenshot 2024-11-28 004920](https://github.com/user-attachments/assets/fa61e0ae-663e-4a74-83c4-f40aad9e6149)
 
 
Modifiable variables :
- For the first person camera (Ghostrunner) : in the BP_FirstPersonCharacter, the categories "Movement", "WallRun", "Dash" and "Camera" contain the variables modifiable by the game designer

![Capture d’écran 2024-11-27 143456](https://github.com/user-attachments/assets/f0419cbd-10e3-4423-a1e2-c2506d9f1cb2)
- For the third person camera (Monster Hunter) : in the BP_MHCharacter, the "Camera" categories, “Aiming” and “PlayRate” contain variables that can be modified by game designers

![Capture d’écran 2024-11-27 142953](https://github.com/user-attachments/assets/50d05ff4-6254-4132-8e2d-11694f730733)
- For the 2.5D camera (Chants of Sennaar) : 

How to play :
- For the first person camera (Ghostrunner)
-        - Movement : Z,Q,S,D / Left Thumbstick
         - Camera : Mousse / Right Thumbstick
         - Jump : Space Bar / Face button Bottom
         - Dash : Left Shift / RB (hold to bullet time)
         - Slide : Left Ctrl / Face button Right
- For the third person camera (Monster Hunter)
-        - Movement : Z,Q,S,D / Left Thumbstick
         - Camera : Mousse / Right Thumbstick
         - Aim : Right mousse button / RT
         - Lock camera : A / Right Thumbstick button
         - Reset camera position : Left Ctrl / LB
- For the 2.5D camera (Chants of Sennaar)
-        - Movement : Z,Q,S,D / Left Thumbstick

