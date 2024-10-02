# Pokemon-Community-Game-Spawn-Countdown
My version of the HTML for the Pokemon Community Game Spawn Countdown Extension on Twitch

##### [CodePen Example](https://codepen.io/mine-patcher/pen/VwJqyoe)

## How to Use
1. Download the File [PokemonCommunityGame.html](/PokemonCommunityGame.html) or use https://minepatcher.github.io/pokemon-community-game/
2. Setup an OBS Browser Source in OBS.

    ![image](https://github.com/user-attachments/assets/fa1ef8aa-a391-4ecb-bef5-a92fee580228)
- `Local file` : `uncheck`
- `URL` : `file://<file location>?<param>&<param>` or `https://minepatcher.github.io/pokemon-community-game/`
- `Height` : `160`
- `Width` : `160`
- `Control audio via OBS` : `check` ***IF USING AUDIO PARAM***
- `Custom CSS` : `optional otherwise leave blank`
## Params
The following are the params available.
- `spawn` : `[gif/pic/hide]`
    - Default : `pic`
- `timer` : `[true/false]`
    - Default : `true`
- `audio` : `[true/false]`
    - Default : `false`
    > Please be sure to select ***`Control audio via OBS`*** to stream the audio. *Else only the creator will hear it.*
 
## CSS Stylings
You can create your own wording choices with the CSS Stylings down below!
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
### PIC W/ TIMER
```
?spawn=pic&timer=true
```
![Default](https://github.com/user-attachments/assets/b5f5fc5e-4118-4e06-8400-5bede2bf3493)
![Catch_Default_PNG](https://github.com/user-attachments/assets/dbd65bf3-394f-45d6-a195-93378164df54)

### PIC W/O TIMER
```
?spawn=pic&timer=false
```
![Default_Spawn](https://github.com/user-attachments/assets/bef67938-ed00-493a-ae2a-f6c92777fc70)
![Catch_Spawn_PNG](https://github.com/user-attachments/assets/9b6883a1-d5d8-4c4c-93f2-bb8f21726c8a)


### GIF W/ TIMER
```
?spawn=gif&timer=true
```
![Default](https://github.com/user-attachments/assets/d75c0183-8de2-4457-bc87-3c39bf63155d)
![Catch_Default_GIF](https://github.com/user-attachments/assets/7c90d9ad-d9e4-4ff3-82a8-260b16bf36c2)

### GIF W/O TIMER
```
?spawn=gif&timer=false
```
![Default_Spawn](https://github.com/user-attachments/assets/5acd196c-a789-496b-8319-ca05daa6c6d1)
![Catch_Spawn_GIF](https://github.com/user-attachments/assets/7357e1e0-0899-40b7-ae58-07a0f73b3d80)


### TIMER ONLY
```
?spawn=hide&timer=true
```
![Default_Timer](https://github.com/user-attachments/assets/af85089b-0e21-4869-9197-9315b3324469)
![Catch_Timer](https://github.com/user-attachments/assets/b21f4125-9519-404e-8684-60e497d2e4c7)
