# One-Pager: Media Management

## Common Uses of Media Items for Similar Games
Games similar in media usage to my game, ‘A Cat’s Quest,’ include Stardew Valley and Stray, utilizing certain media items to add to the cozy, exploration atmosphere. 
**Background Music**: This includes various music options that continuously loop, changing based on the scene to fit, such as a softer beat to fit a forest vibe, and a more upbeat one to fit a town. 
**Sound Effects**: Integration of player sound effects to add to the game’s ambiance and make the player feel as if they are in the environment, including paw steps, opening of doors, rustling of bushes, and item pickup, for example. Additionally, background sounds such as chirping birds, leaves rustling, or water flowing down a river make the world feel more immersive. 
**Text-box Dialogue**: For my game, a similar approach to dialogue is inspired by Stardew Valley, where I plan to use text boxes for dialogue rather than voice acting. When the player interacts with an NPC or has a thought, a text-box dialogue would appear and would cater to the speaker using certain fonts, text typing style, and character headshots. 

## Two Strategies to Integrate Media
**1. Drag-and-Drop** A common strategy of media integration for small-scale games in the Unity engine involves dragging and dropping assets into the corresponding library, creating .anim clips for animations, and dragging audio and sound clips directly into the project and assigning a corresponding audio clip.
**Pros**: Easy to integrate and simple to use for prototyping, perfect for persistent objects like BGM.
**Cons**: Can result in many performance issues as the game gets larger, becomes disorganized, and can create lots of dependencies in one scene.

**2. Media Manager System**: Creating a manager script for audio, sprites, etc, to manage all components in a single central manager makes for a globally accessible option. 
**Pros**: Organized and can result in less risk of performance issues, allows for more complex logic, and is more efficient. 
**Cons**: Requires more coding knowledge and takes a significant amount of time to set up. 

## Summarize Approach to Integrate Media
For my prototype, I’ve been using the drag-and-drop integration throughout my project and plan to continue using it, as it is the simplest and fastest way to complete a small-scale prototype. 
As I continue to scale up my game and include more assets and media, I may consider using the manager system media integration for the final project, depending on how performance is affected, and to make it more scalable and organized.
