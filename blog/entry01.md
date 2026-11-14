# Entry 1
##### 11/14/26

## Content
The tool I've decided to choose is Phaser because it seems to be extremely good at making fun and interactive games. Originally, I had chosen Q5.play as my tool, but after tinkering with it for a while, I realized I didn't think it would be a good fit for my project. My partner came to the same conclusion, and then we switched to Phaser. Because of this, we only started tinkering with Phaser last week. I have tinkered with my tool by watching YouTube videos such as this one [video](https://www.youtube.com/watch?v=jHTRu4iNTcA), along with using this interactive Phaser website [phaser](https://phaser.io/). Something that helped me a lot was a Reddit post that had some basic starter code for Phaser. I was able to run it in JS Bin and see how it worked. My biggest takeaway was from this specific part of the code because I will need to know how to use it for my project.
```js
function update() {
  if (cursors.left.isDown)  player.x -= 4;
  if (cursors.right.isDown) player.x += 4;
  if (cursors.up.isDown)    player.y -= 4;
  if (cursors.down.isDown)  player.y += 4;
}
```
What this does is make it so your keyboard arrows control something on the screen. This is essential to my project because I'm making a game where you're Isaac Newton, and there are different falling fruits where you have to move around and can only get hit by the apples.



[Next](entry02.md)

[Home](../README.md)
