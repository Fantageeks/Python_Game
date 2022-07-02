# PYTHON GAMES: 自己創造的小遊戲

1. **參考資料**
    1. Pygame Page:   http://pygame.org
    2. documentation: http://pygame.org/docs/ref/
    3. ~~XXXXXXX 忘記了~~ <br><br>
 ------

**_2. What is Pygame_**:
  * Pygame提供Display, Sound, Music, Image, Text, Event幫助製作遊戲
  * Pygame可以做出2-D小遊戲
  * Pygame偵測使用者使用Keyboard, joystick, mouse控制遊戲
  * Pygame提供許多內建的game objects來製作遊戲 <br><br>

**_3. PYGame Basics Code_**:
| Code | Description |
|:-----:|:----------:|
| _1.py_ | Create my game surface, game loop and drawing.|
| _2.py_ | Blit text, font, sound and image objects.   |
| _3.py_ | Getting user keyboard and collision dection.|

**_4. Code snippet_**
```python
#Create game display
WINDOW_WIDTH, WINDOW_HEIGHT = 1000, 600
displayscreen = pygame.display.set_mode((WINDOW_WIDTH, WINDOW_HEIGHT))
pygame.display.set_caption("Feed the Angry Bird!")

```
```python
#Blit image object and setting its rec.
player_image = pygame.image.load("angry_bird.png")
player_rect  = player_image.get_rect()
player_rect.left = 32           
player_rect.centery = WINDOW_HEIGHT//2
displayscreen.blit(player_image, player_rect)
```
**_5. Game Assets:_** <br>
[Icon Archive:](https://iconarchive.com/) 網站提供很多遊戲角色下載 <br>
[Leshy SFMaker:](https://www.leshylabs.com/apps/sfMaker/) 網站可以下載遊戲特效，也可以簡單自己製作音效

 
![2.py 程式截圖](https://github.com/Fantageeks/PYGAME_basics/blob/main/1.PNG)
