---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /cover.jpg
title: Storytime- Friend
info: |
  ## Random Walker

  Presentation about random walkers
# apply unocss classes to the current slide
class: text-center
transition: slide-left
layout: cover
---

# Storytime

A story about Friend

---
layout: image-left
image: /friend-headshot.jpg
---

# This is Friend

Important facts:

<ol>
  <li><v-click>Has a heavy butt</v-click></li>
  <li><v-click>They/them - has no gender</v-click></li>
  <li><v-click>All other creatures that look like them are cousins</v-click></li>
</ol>

<br/>

<v-click>
<p><span v-mark.crossed.red="5">Thank you for coming to show and tell</span></p>
</v-click>


<br/>
<v-click>Let's get to know our hero better.</v-click>


---
layout: iframe-left

# the web page source
url: https://creative.nicole.computer/presentation-friend/watermelon-gummies/
---

# Inside Friends' mind

<ul>
  <li><v-click><p>Friend <b>loves</b> watermelon gummies</p></v-click></li>
  <li><v-click><p>When they were young they followed their cousins in a long line</p></v-click></li>
  <li><v-click><p>Since living with me the candies are harder to find</p></v-click></li>
</ul>

<!--- But how to get them? --->

---
layout: iframe-left

# the web page source
url: https://creative.nicole.computer/presentation-friend/normal-day/

---

# A typical day

<v-click>
```typescript{all|12|2-11|14|all}
update() {
  const availableMoves = [
    "UP",
    "DOWN",
    "LEFT",
    "RIGHT",
    "UP-RIGHT",
    "UP-LEFT",
    "DOWN-RIGHT",
    "DOWN-LEFT",
  ];
  const nextMove = random(availableMoves);

  this.move(nextMove);
}
```
</v-click>

<v-click>
This is called a <a href=https://en.wikipedia.org/wiki/Random_walk>Random Walk</a>.
</v-click>

<!--- Remember to say Friend has no memory, this is just to illustrate; take note of how much they explored (not very much) --->

---
layout: iframe-left

# the web page source
url: https://creative.nicole.computer/presentation-friend/memory/
---

# A little memory 🥦

<v-click>
```typescript{all|1-3|5|8-11|all}
// moves has all available moves
//   without moving Friend off the board
let moves = [...]

moves = moves.filter((move) => {
  const proposedLocation = locationToString(
    this.locationOfMove(move));

  return !history
    .map(locationToString)
    .includes(proposedLocation);
});
```
</v-click>


---
layout: iframe-left

# the web page source
url: https://creative.nicole.computer/presentation-friend/levy-flight/
---

# Lévy flight

```typescript{all|1-6|24|7-14|15-23|all}
if (this.state.type == "explore") {
  availableMoves = this.canMove(width, height);
} else if (this.state.type == "walk") {
  availableMoves = [this.state.move];
}

if (this.state.type === "walk") {
  this.state.timeLeft -= 1;

  if (this.state.timeLeft === 0) {
    this.state = { type: "explore" };
  }
}

if (this.state.type === "explore"
    && floor(random(1, 100)) > 90) {
  this.state = {
    type: "walk",
    timeLeft: 10,
    move: random(["UP", "DOWN", "LEFT", "RIGHT"]),
  };
}

this.move(random(availableMoves));
```


---
layout: iframe-left
url: https://creative.nicole.computer/presentation-friend/happiness/
---

# Finding happiness
<p></p>

<p>Some days you get the watermelon gummy 🍉,<br/>
Some days you don't 😢,<br/>
We leave room for both 🌤️</p>

<p>Until next time 💜</p>

