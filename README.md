# genie-bubble-pop-creator

Ability to generate levels for the Genie component - Bubble pop.
<img width="1216" alt="Screenshot 2023-05-24 at 12 29 11" src="https://github.com/aerstudios/genie-bubble-pop-creator/assets/17544779/98ceacba-d08e-4c5d-8aae-ea09420d2fb4">


## Balls Config

Below is how the balls get loaded into this file. If you wish to add your own ball images and code then update this default snippet.
Placing the images in the same folder as the index.html file
```
[{"dataId":"R","imgSrc":"red_ball.png"},{"dataId":"G","imgSrc":"green_ball.png"},{"dataId":"B","imgSrc":"blue_ball.png"},{"dataId":".","imgSrc":"white_ball.png"}]
```
A ball has 
 - dataId this is the output of the ball in the grid
 - imgSrc this is the destination of the file

<img width="491" alt="Screenshot 2023-05-23 at 17 21 39" src="https://github.com/aerstudios/genie-bubble-pop-creator/assets/17544779/ceecaa2c-80b7-4996-ae2b-200bb30e2337">


## Grid Config

By default the grid is empty. When you start dragging balls into the grid this will automatically update. Once you are done you
can just copy this field and paste it into the relevant level.

### Grid size

Looking at the previous themes all the grids have be 12 rows x 20 columns. This setup mimics that. Should this need to be changed please contact myself (Darren Torchia).

### Loading a saved level

Before loading a saved level please ensure the balls config has been loaded in.
You will be able to paste the level grid code in the textarea and hitting the generate button.

This is the output of the grid. Copy and paste this into the level configuration
<img width="490" alt="Screenshot 2023-05-23 at 17 23 01" src="https://github.com/aerstudios/genie-bubble-pop-creator/assets/17544779/ac62c181-06b5-432e-9f60-da53ab069fd8">
