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
### X/X/XX:
* Text


<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
