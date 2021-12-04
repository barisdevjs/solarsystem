# This is a Solar System Demonstration  by pure Javascript
---
[ LIVE  Demo](https://practical-poincare-351188.netlify.app/)

## Below you will see the page of a game

![alt text](https://github.com/barisdevjs/solarsystem/blob/main/screenshot.jpg)

---

---

- Game stars with a random quetion of 4 questions.
- When you answer correctly, your background and answer will turn green.
- When you choose a  wrong answer, your background and answer will turn red.
- Start and Next buttons will be placed according to the game flow.
- Game will be played until you answer every question
- Good Luck
---

### This game logic is build by the help of ` functions && objects && Math functions` 

```
  const neptune = {
    speed: Math.random() * 0.01 + 0.002,
    theta: Math.random() * 2 * Math.PI,
    radius: 180,
    el: document.querySelector('.neptune')
  }
```