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
url: https://creative.nicole.computer/2024-11-08-mouse-walker/
---

# A little memory

- Introduce oversampling
- A simple way to reduce oversampling without putting too much burden on the explorer

---
layout: iframe-left

# the web page source
url: https://creative.nicole.computer/2024-11-08-mouse-walker/
---

# Lévy flight

- Another technique friend has recently learned
- Look around but occasionally take a big jump and go explore somewhere else
- Still get stuck


---
layout: center
---

# Friend gets the gummy

- With enough exploring friend does get the gummy
- It makes them very happy

---
layout: center
---

# Until next time

Someday you get the gummy, somedays you don't
We leave room for both

Be good to one another
