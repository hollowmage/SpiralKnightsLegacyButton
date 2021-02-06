# Spiral Knights Legacy Button
I miss the old Spiral Knights interface, so I started messing around with CSS and I created an equipment button. Those of you who played this game in the old days will immediately recognize it (even if some details are still missing).

## What is done:
![SK Button states](/preview/states.png)

The equipment buttons have a normal state, an equipped state and hover states for both of those.
There is also a disabled state, if you need:

![Disabled SK Button](/preview/disabled.png)

You can set the number of stars of your equipment from 0 to 5. And you can also set up to 3 Unique Variants.

Now, if you want icons on these buttons, you'll have to figure that out for yourself, there were A LOT of equipment symbols back in the day and the screenshots that I am working with don't give me much to go on.
Still, I guess I can give you a little taste:

![Barbarous Thorn Blade w/ 3 UVs](/preview/btb-example.png)

## How to use?
Check the `sk-btn.htm` file for a quick and dirty example.
You need to import the stylesheet and create a button with the class "sk", like this:
```html
<button class="sk s0 v0">
  <div class="name">Proto Sword</div>
  <div class="UVs"></div>
  <div class="stars"></div>
</button>
```
The classes s0 to s5 correspond to the number of stars, while v0 to v3 correspond to the number of Unique Variants.

## Future things to work on:
(As this is still very much a work in progress...)

* Reduce the amount of HTML code needed to create a button (shadow DOM...?)
* Button backgrounds (the in-game buttons weren't just colors, they had a background texture)

~~* Figure out what software licenses are (since Github was asking me to choose one just a moment ago) and where my work falls under. (As far as I'm concerned you can use these buttons however you see fit while I figure this stuff out...)~~ Figured it out, I chose the MIT License, have fun!
* Maybe convert all images to SVG? Would that be a good thing? I don't know...
