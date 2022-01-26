# Get to Know MakeCode Arcade 


```ghost
let mySprite: Sprite = null;
mySprite.startEffect(effects.spray)
controller.A.onEvent(ControllerButtonEvent.Pressed, function () {
    game.showLongText("The little unicorn walked into the meadow.", DialogLayout.Top)
    scene.cameraShake(4, 500)
})
scene.setBackgroundColor(9)
scene.setBackgroundImage()
mySprite.x += 0
effects.confetti.startScreenEffect()
effects.confetti.endScreenEffect()
mySprite.setPosition(70, 80)
for (let index = 0; index < 4; index++) {
    controller.moveSprite(mySprite)
    music.setVolume(20)
    music.playMelody("- - - - - - - - ", 120)
}
game.onUpdateInterval(5000, function () {
    if (game.askForString("Continue?") == "Y" || game.askForString("Continue?") == "y") {
        mySprite.say(":)")
    }
    game.splash("")
})

```

### @explicitHints true

## Introduction @unplugged

![Psyched Monkey](/static/skillmap/interface/monkey.png "Psyched Monkey is Ready!" )

**Are you ready to start coding your own games?**

Complete this tutorial to learn how to:
- follow tutorial prompts
- find blocks in the toolbox
- build code in the workspace
- run your game on the built-in simulator 

Before you know it, you'll have an arcade game of your very own!

## step 1 

1. Add a background color to this project! Open the **[Scene]** code block menu, drag a **[set background color to]** block inside the **[on start]** container block, then click the gray bubble to select a color from the menu. 

Click ▶ under the MakeCode game controller to see the color appear on the screen!

#### ~ tutorialhint 
```
❓ Did you drag the **[set background color to]** block inside the **[on start]** container block?
[Image goes here]
```

## step 2

2. Add a sprite to this project! A sprite is any character or object in MakeCode. Open the **[Sprites]** code block menu and drag a **[set sprite to]** block inside the **[on start]** container block. Then click the gray box and select a sprite from the Gallery tab. 

Click ▶ to see your sprite appear on the screen!


#### ~ tutorialhint 
```
❓ After clicking the gray box, did you select the Gallery tab from the top menu?
```


## step 3

3.  Add a block to move the sprite to a different position! Open the **[Sprites]** code block menu and drag a **[set sprite position to]** block underneath the **[set sprite to]** block inside the **[on start]** container block.

#### ~ tutorialhint 
```
❓ Did you drag the [set sprite position to] block underneath the [set sprite to] block?
```



## step 4

4. Now, pick the sprite’s position! Click in the white bubbles to change the x and y coordinate values. The x value will move the sprite left or right, the y value will move the sprite up or down.

Click ▶ to see the position of your sprite.

#### ~ tutorialhint
```
❓ Did you try both larger and smaller values for the x and for the y to see how it changes the sprite’s position?  
```


## step 5

5. Make the sprite say something! Open the [Sprites] code block menu and drag a [sprite say] block underneath the other blocks inside the [on start] block. Click in the white bubble and type something for the sprite to say. 

Click ▶ to see what the sprite says on screen.

#### ~ tutorialhint
```
❓ Did you drag the [sprite say] block underneath the [set sprite to] block?
```