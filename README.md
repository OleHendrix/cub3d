# cub3d  

cub3d is a 3D graphics project written in C, inspired by the classic Wolfenstein 3D game. Using the **ray-casting** technique, the project transforms a simple 2D map into an immersive 3D first-person perspective environment. This project demonstrates core concepts of graphics rendering, player interaction, and game development.

## How It Works  

1. **2D Map to 3D World**  
   - The game starts with a 2D map defined in a `.cub` file.  
   - The map consists of walls, empty spaces, and the player's starting position.  
   - Ray-casting is used to calculate how the walls should appear from the player’s perspective.  

2. **Ray-Casting Rendering**  
   - Rays are cast from the player's position and direction to determine wall positions and distances.  
   - The height of the walls in the 3D view is calculated based on their distance from the player, creating a perspective effect.  

3. **Player Interaction**  
   - The player can move forward, backward, and sideways, and rotate their view to explore the environment.  
   - Keyboard input is captured to control movement and interaction.  

4. **Textures and Graphics**  
   - Textures are mapped onto walls to enhance visual realism.  
   - The game uses **MLX42** for graphical rendering, including texture mapping, color shading, and event handling.  

5. **Error Handling**  
   - The program validates the map to ensure it is closed (surrounded by walls) and free of errors.  
   - Handles edge cases such as invalid configurations or missing assets gracefully.  

6. **Performance Optimization**  
   - Efficient calculations are used to minimize lag and maintain smooth rendering, even for complex maps.  

## What I Learned  
- The principles of ray-casting and how it is used in 3D rendering.  
- Working with the **MLX42** library for 2D and 3D graphics rendering.  
- Advanced file parsing to validate and interpret game maps.  
- Implementing real-time player movement and interaction.  
- Debugging graphical applications and handling performance bottlenecks.  
- The foundational concepts behind modern game engines and 3D rendering techniques.  
