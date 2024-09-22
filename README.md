# GameProjectSharing_ProjectNavigation
Build, learn, and make mistakes.
ProjectNavigation Development diary：The inspiration came from a water teaching video reposted on bilibili.
Water surface physics used in the game explained:  
https://github.com/CookieTsang/Unity3D-Simple-ocean-surface-physical-.git.  
  
![wave](https://github.com/user-attachments/assets/74a22c17-e9b1-4cfa-8d44-b9227ecff9e2)
  
I'm actively working on this game, hoping to get to a playable state with interactive NPCS and intense battle scenes.  
2024/9/13:    
Before the surface has been realized, the player body can be manipulated, pointing to the interactive first person, reserving the third person structure, collision optimization, repair the camera through the mold.  
2024/9/14:  
Content optimization:  
Optimize physics, objects should not be affected by buoyancy before contact with water;  
Optimized to grasp objects without rotating on the hand;  
All key operation access InputAction.  

![image](https://github.com/user-attachments/assets/3c0ba805-07f6-4488-92fa-a58f7b988df2)

Function development:  
Grab, drop and throw functions are developed.  
2024/9/15:  
Content optimization:  
Water follows the player, open world water base.
Function development:  
Shift dash key
What's new:  
Simple scenery, add low polygon water Shader, object submerged wave effect, edge wave effect.

![Drop](https://github.com/user-attachments/assets/1f0f5178-dfd9-402e-8c3a-254a6d94b69d)

The next step is to optimize the surface physics of the object; Sailing system, steering system, code function separation.  
Further down the line: develop the player's handheld weapons; Enemy systems (characters, ships); Trading system;  
2024/9/16:  
Replace the sound plugin, map the sound.  
2024/9/17:  
Debug the sound plugin, set up the sound system, distinguish between map sound and collision sound  
Ps: Sinewave Sea is not the final version and will replace GerstnerWave.  
2024/9/21:  
Sunlight scattering effect, day/night time system (unfinished),  
Players operate the item system, drive the ship system, optimize the ship friction, the ship steering system, better sound.  
  
![2](https://github.com/user-attachments/assets/458dfd79-f08a-4f6d-8450-04431451b770)

