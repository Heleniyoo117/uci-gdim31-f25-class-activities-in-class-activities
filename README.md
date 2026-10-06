# in-class-activities
## Devlogs
### W1
1. When I moved the Camera out of the Cat GameObject, the Camera no longer followed the Cat when I run the game. This is because the Camera was originally a child of the Cat, so it inherited the Cat’s movement. After I moved it out of the Cat hierarchy, the Camera became independent and stayed in its own position while the Cat moved.
2.https://qishu-huang.itch.io/games-a-piece-of

### W2
1. The r, g, and b variables are floats because they need to store decimal values, such as 0.1, 0.5, or 1.0. They are used for the red, green, and blue color values, so we need values between 0 and 1. A float is appropriate for this. Microsoft Learn
2. The _bounce variable is an int because it counts the number of times the ball bounces. The number of bounces should be a whole number, such as 0, 1, 2, or 3. It does not need decimal values, true/false, or text. Microsoft Learn
3. The error told me that the line of code was missing a semicolon at the end. In C#, statements need to end with a semicolon, so the code could not compile until I added ;. This helped me understand that small syntax mistakes can cause compiler errors.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
