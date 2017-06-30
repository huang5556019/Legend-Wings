# iOS Swift Project - Legend Wings - *EverWing's Mini Clone*

**EverWing** is a popular action game. Survive as much you can, earn gold, and upgrade/purchase new characters.

## Videos - Date Recorded: 06/20/2017:
<p>
<img src='https://github.com/woguan/Legend-Wings/blob/master/Angelica%20Fighti/Gif/Intro.gif' title='Intro Video' width='200' height='357' alt='Intro Video' /> <img src='https://github.com/woguan/Legend-Wings/blob/master/Angelica%20Fighti/Gif/selection.gif' width='200' height='357'/> <img src='https://github.com/woguan/Legend-Wings/blob/master/Angelica%20Fighti/Gif/startgame.gif' width='200' height='357'/> <img src='https://github.com/woguan/Legend-Wings/blob/master/Angelica%20Fighti/Gif/midgame.gif' width='200' height='357'/>
</p><br>
PS: Videos are often outdated. Run on your device to check out new stuff!

## Notes:
- Xcode Version: 8.3.3 | Latest iOS 10.3
- Using Xcode's simulator will be a bit laggy. Use Device for best experience.
- Todo list is the feature which I'm working now OR about to start it.
- <b>*Best experience with iPhone 7 Plus. </b>

## TODO list:

- [] "Fix" and find a better logic for the top bar which displays account progress
- [] Re-implement logic to increase enemies' HP and Velocity over time 
- [] Add customized font ttf for Gold Label with OpenGL shader

## Future Implementations:
- [] Add new regular monsters
- [] Add new bullets for characters:
   - [] Add Alpha Bullet Sprites
   - [] Add Beta Bullet Sprites
   - [] Add Celta Bullet Sprites
   - [] Add Delta Bullet Sprites
   - [] Add Class to create custom bullet sprite
- [] Add Purchase Function
- [] Add Upgrade Bullet Function
- [] Display current level of bullet and its image on Character Scene
- [] Add Companions System (Each side with a small minion to assist you) - Sidekicks!
- [] Add Power-Ups
  - [] Imune Item
  - [] Increase Fire Power
  - [] Double Shoot
- [] Add Game Over Scene
- [] Add Unit Test

## Discovered Bugs:
- The top bar is not a bug. I'm just thinking a good approach for displaying them
- It looks like that for smaller devices such as iPhone 5, the monsters are dying quickly.
- HUD displays are not "pretty". I think it's a bit challenging for creating a HUD from sknodes. Thus, in near future, I will replace them with custom OTF/TTF files. I'm still looking for a good software to generate them.
- Characters are too big in smaller devices. This is known issue due for using "fixed" size. It will be fixed later on.

## Main Accomplishments:
- [✔️] Add support for iPhone 5, iPhone 6, iPhone 6 Plus, iPhone 7, iPhone 7 Plus 
- [✔️] Preload Textures
  - [✔️] Add progress bar
  - [✔️] Divide Atlas into smaller atlas
- [✔️] Coin System
- [✔️] Character Selection
  - [✔️] Alpha
  - [✔️] Beta
  - [✔️] Celta
  - [✔️] Delta
- [✔️] Add Backup Logic
- [✔️] Add Progress Track
- [✔️] Add Singleton Global to access all Sprites
- [✔️] Add shader to fonts (OpenGL)
- [✔️] Remove Main.storyboard for faster build time
- [✔️] Add Bomber Boss in-game
- [✔️] Add Pinky Boss in-game - <b>06/28/2017</b>
  - [✔️] Add Pinky Boss Sprites
  - [✔️] Add Pinky Boss Actions
- [✔️] Add Labels in Character Selection - <b>06/28/2017</b>
- [✔️] Add particle effects when selecting character - <b>06/29/2017</b>

  
