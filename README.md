# Pokemon-Community-Game-Spawn-Countdown
My version of the HTML for the Pokemon Community Game Spawn Countdown Extension on Twitch

CodePen: [Here](https://codepen.io/mine-patcher/pen/VwJqyoe)

## How to Use:
1. Download the File <PokemonCommunityGame.html> or use URL (https://minepatcher.github.io/pokemon-community-game/)
2. Setup an OBS Browser Source in OBS.
![PCG_1](https://github.com/user-attachments/assets/241d7ec0-8db0-4c62-8d65-cb128bb02954)
- URL: file://&lt;PokemonCommunityGame.html Location&gt;?&lt;Parameters&gt;
- Height: 180
- Width: 180
### Params:
- spawn: [gif/pic/hide]
    - Default: pic
- timer: [true/false]
    - Default: true
- audio: [true/false]
    - Default: false

### Examples:
1.  Default: ?spawn=pic&timer=true

![PCG_2](https://github.com/user-attachments/assets/436133db-6c3a-46ec-b39f-29abd01e02ef)

2. No Timer: ?spawn=pic&timer=false

![image](https://github.com/user-attachments/assets/3dcc80ff-1aed-43df-8954-c96cef8c6850)

3. GIF: ?spawn=gif&timer=true

![PCG_3](https://github.com/user-attachments/assets/bed95381-ec4e-4771-8a23-fee66b154f57)

4. Only Timer: ?spawn=hide&timer=true

![image](https://github.com/user-attachments/assets/29241c6c-974a-427d-bfc6-4fb80019af93)
