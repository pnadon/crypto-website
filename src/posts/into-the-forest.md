---
layout: layouts/post.njk
title: Into the Forest  - UPDATED WITH ANSWERS
date: 2020-02-22T07:02:51.261Z
tags:
  - round_2
  - medium
---
![](/images/find_ship.jpg)

*If you haven’t done the Round 2 Easy challenge first, please do so for the story to make sense!*

A team from the Cryptography Project has just found the coordinates of a planet that could possibly help save the human race. You decide to camp at the outskirts of a nearby forest to avoid any dangers of being in the open. It has been multiple days without any activity, and you ponder upon what should be done next. It begins raining and you seek shelter under the branches of a fallen tree.

"Hey, did you hear about the rumours of a crazy old man who lives in this forest? Spends his days rambling about secret codes and spaceships..." One of your members says. Just then you notice something written on the bark of the tree:

`AVLIIEAUNFTVEVSEEOEINHFREITBSS`

Just below the writing is a weird drawing, carved deep into the tree:

![](/images/railfence.jpg)

"Yep, that old man is nuts!" Another member adds, laughing. "Hold on..." You reply, "Maybe we could check it out. Who knows, the old man could know something we don't!"

Since there is currently nothing else to do, your team decides to pursue this idea. You wonder what the message signifies and keep a record of it in your journal. You continue going deeper into the forest and come across a small clear area without trees or plantation. It is midday now and the sun is right above you. You see the sunlight pointing towards the centre of the clearing as if almost made to do so. You go to the centre and find an oddly out-of-place sign:

![](/images/amazon_logo.jpg)

The sign appears to have a weird line of characters in its lower-right corner:

`KBGIH DKHFDIBF LGHF NBKCM BGHI`

"I know it's been a while since Amazon was around, but there's something weird about this Amazon logo, something different..." You say. Confused as to how to proceed with this information, you confer with the other surviving members and try to crack what the code could mean…

# Afterward

You see the photo of the rail tracks and notice there are 7 tracks in it. You realize the first message is likely a **Railfence Cipher** with a key of `7`. Decoding the cipher, you get:

`A INVERSE IS FIVE TEN IS THE VALUE OF B`

You and your fellow humans get down to work and notice that the 2 keys (a^-1 = 5 and b = 10) most likely correspond to an `Affine Cipher`. Using the provided photo, you take the hint that **only letters from A to N** are used in this cipher and it uses **mod 14 instead of mod 26**. You do the necessary calculations and after a serious amount of work, you get:

`ALIEN HANDHELD FIND BLACK LINE`

You open the alien handheld device and notice that it is picking up some weird distortions, which appear as wavy lines of a multitude of colours, one of which is a faint, black line. You begin following the black line, and as the line gets thicker you reach a crater like clearing. After you clear the last few bushes between you and the valley, you see a large shed-like object. As you approach it, the alien handheld flies away from your hand and gets attached to the outside of the hangar while simultaneously unlocking it.

You look inside and see what appears to be a spaceship, one like you have never seen before. You enter the spaceship and try to start it. Unfortunately the spaceship beeps and a gauge-cluster shows multiple missing items. The cryo-sleep capsules that could help long-distance travel are one of the many things missing. You look around in the hangar and find many broken items including a few fuel capsules that are empty. Rejoiced by this, a tiny sliver of hope awakens in your group and you contemplate your next steps. 
