# Unreal Programmer Task

## Skateboarding Simulator Game

### Objectives
- Develop a functional Skateboarding Simulator Game in Unreal Engine 5;
- Movement functionality:
    -  Speeding up and slowing down;
    -  Jumping;
-  Small Designed Level with Jumping obstacles;
-  Integrate a Mixamo Skating and Jumping animations;
-  Points system for obstacles jumped over;
-  Design a suitable UI for the prototype.

### Development Process
I started off with UE5's third-person template, utilizing its basic assets while focusing on developing the gameplay mechanics. Assets aside, the Player Character (*BP_ThirdPersonCharacter*) was used as a base, though only a few of the original nodes remain, clearly marked by the dark-colored comments. I took a blueprint-centric approach to facilitate rapid prototyping and iterations.

After importing a Skateboard model from TurboSquid and Skating animations from Mixamo, the next task was to start modifying the animation blueprint (*ABP_Mannequin*). While the overall structure from *ABP_Manny* remains, significant changes were made to accomodate the skate model itself, to blend the skating and jumping animations, and the new controls, while still maintaining feet IK functionality.

Reworking the movement funcionality was a necessity to achieve the proper skateboarding gamefeel, which was accomplished with more deliberate acceleration mechanics, increased momentum, and a wider turn radius. A stamina system was implemented to regulate the frequency of actions like speeding up, each with specific stamina costs, monitored via a new HUD widget.

I then implemented the obstacles and the score system, visually tracked in the HUD. Additionally, basic animations were implemented so the skareboard would react appropriatly to ramps and jumps.

In the final phase, I finished the level blockout, integrating in-world UI indicators for the obstacles and a main menu that presents the controls alongside a game quit option, finishing up the prototype.

### Conclusion
The tight deadline for project pushed me to prioritize gameplay mechanics over aesthetics due to my strengths and the project's scope. So, I focused on the core mechanics like movement, stamina, and scoring. Successfully integrating skateboarding animations under these constraints was a highlight, but level design and aesthetic polish were limited. This approach allowed for a functional prototype that emphasized playability, aligning with the project's objectives.

Overall, I'm pleased with the planning and execution, particularly starting with the less familiar tasks like animations. Despite the project's limitations, it was a valuable learning opportunity, emphasizing the importance of gameplay mechanics and efficient project management under tight deadlines.