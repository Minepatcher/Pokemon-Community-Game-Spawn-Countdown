# Pokemon-Community-Game-Spawn-Countdown
My version of the HTML for the Pokemon Community Game Spawn Countdown Extension on Twitch

##### [CodePen Example](https://codepen.io/mine-patcher/pen/VwJqyoe)

## How to Use:
1. Download the File [PokemonCommunityGame.html](/PokemonCommunityGame.html) or use https://minepatcher.github.io/pokemon-community-game/
2. Setup an OBS Browser Source in OBS.

    ![image](https://github.com/user-attachments/assets/fa1ef8aa-a391-4ecb-bef5-a92fee580228)
- `Local file` : `uncheck`
- `URL` : `file://<file location>?<param>&<param>` or `https://minepatcher.github.io/pokemon-community-game/`
- `Height` : `160`
- `Width` : `160`
- `Control audio via OBS` : `check` ***IF USING AUDIO PARAM***
- `Custom CSS` : `optional`
## Params
- `spawn` : `[gif/pic/hide]`
    - Default : `pic`
- `timer` : `[true/false]`
    - Default : `true`
- `audio` : `[true/false]`
    - Default : `false`
    > Please be sure to select ***`Control audio via OBS`*** to stream the audio. *Else only the creator will hear it.*
 
## CSS Stylings
- *Before Catch Period*
    - Default :
      ``` CSS
      legend:after { content : "Next Pokemon" }
      ```
- *During Catch Period*
    - Default :
      ``` CSS
      legend.catchPokemon:after { content : "!pokecatch" }
      ```

## Param Examples
### Default
```
?spawn=pic&timer=true
```
![PCG_2](https://github.com/user-attachments/assets/436133db-6c3a-46ec-b39f-29abd01e02ef)

### No Timer
```
?spawn=pic&timer=false
```
![image](https://github.com/user-attachments/assets/3dcc80ff-1aed-43df-8954-c96cef8c6850)

### GIF
```
?spawn=gif&timer=true
```
![PCG_3](https://github.com/user-attachments/assets/bed95381-ec4e-4771-8a23-fee66b154f57)

### Only Timer
```
?spawn=hide&timer=true
```
![image](https://github.com/user-attachments/assets/29241c6c-974a-427d-bfc6-4fb80019af93)
