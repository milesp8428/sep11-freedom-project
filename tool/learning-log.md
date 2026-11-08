# Tool Learning Log

## Tool: Q5play

## Project: You are Isaac Newton and there are falling fruit and you can only be hit by the falling apple. 

---

### 10/25/26:
* I found this website to be very useful [q5play]([https://docs.github.com](https://q5play.org/learn/)).
* it lets you lean it though given you challenges
* I click on the physics tab because I thought that that would be interesting and it would have a lot to do with my project.
* I learned how to make a sprit that falls to the ground
```js
  await Canvas(250, 200);
world.gravity.y = 10;

let ball = new Sprite();
ball.diameter = 50;
ball.y = -70;

let floor = new Sprite();
floor.y = 90;
floor.w = 230;
floor.h = 5;
floor.physics = STATIC;
```
* I also learned how to create sprites and change different aspects of them such as there color size and shape. Here is an example of how one looks:
```js
await Canvas(250, 100);

let sprite = new Sprite();
sprite.width = 50;
sprite.height = 50;
```
* 
### 11/7/26:
* I divided that I want ed to try out phaser because I feel like it might be easer for my project.
* I found this code on a redit post for phaser and it is just some very basic code that makes a box that you can move around.
* here is the code:
```js
let player, cursors;

const config = {
  type: Phaser.AUTO,
  width: 600,
  height: 400,
  backgroundColor: '#222222',
  scene: { create: create, update: update }
};

new Phaser.Game(config);

// Runs once when the game starts
function create() {
  this.add.text(10, 10, 'Use the arrow keys', { color: '#ffffff' });
  player = this.add.rectangle(300, 200, 50, 50, 0x00ff88);
  cursors = this.input.keyboard.createCursorKeys();
}

// Runs every frame (about 60 times per second)
function update() {
  if (cursors.left.isDown)  player.x -= 4;
  if (cursors.right.isDown) player.x += 4;
  if (cursors.up.isDown)    player.y -= 4;
  if (cursors.down.isDown)  player.y += 4;
}
```
* What this does is it creates a block then using different aspects of phaser such as ```scene``` and the ```this.input.keyboard.createCursorKeys``` makes it move around. All the if statements at the end diside how fast the block is moving around. The way they chose how fast its moving is though the amount of pixels its able to cover in a given time. Its kind of like Miles per hour but for pixels.

* I also watched this [video](https://www.youtube.com/watch?v=jHTRu4iNTcA) it gave a good introduction to phaser and they are the same people who have this big website that is a really good teaching how to use phaser. 


<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
