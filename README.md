# Image to lego pixel art
Convert image into a buildable LEGO pixel art by transforming it into a grid of LEGO bricks.
![image](https://github.com/user-attachments/assets/6c8e3870-f313-4e08-902e-43936cd60d8d)

## Features

- Convert images into pixelated LEGO art :
Find the best lego piece using nearest neighbour
- Customizable output size (e.g., 32×32, 64×64 bricks)  
- Supports various image formats  
- (Future) Optimized brick count and color accuracy

## Setup of Inputs:
  - Image path
  - Target size of LEGO art
  
## Note:
Be aware that the number of LEGO pieces increases rapidly as the target size grows:
  - 32 × 32 = 1,024 pieces
  - 64 × 64 = 4,096 pieces
  - 128 × 128 = 16,384 pieces

## Future improvements:
  - Reduce the number of blocks used
  - Increase contrast
  - Use a better LEGO color palette
  - Create a LEGO order with all the pieces
