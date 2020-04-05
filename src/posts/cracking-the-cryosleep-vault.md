---
layout: layouts/post.njk
title: Cracking the Cryosleep Vault - UPDATED WITH ANSWERS
date: 2020-03-15T02:32:10.268Z
tags:
  - round_3
  - medium
---
![](/images/cryosleep_capsule.jpg)

# Challenge

If you haven’t done the Round 3 Easy challenge first, please do so for the story to make sense!

About 3 weeks ago, members of the Cryptography Project had uncovered another ship, although this one was damaged beyond repair aside from some fully-charged cryosleep capsules (battery-sized tubes which provide the freezing agent used for the cryosleep pods). Since the ship we found in the previous round was missing cryosleep capsules, some members began moving the capsules into an old underground vault which had been secured by a voice-activated password (which had been discovered by accident), so that they can later be loaded into the ship when it is time to go.

Unfortunately, the members responsible for moving the cryosleep to the vault went missing, presumably caught by some aliens. For safety’s sake the password to the vault was never written down or mentioned to any other members, however a clue was left behind near the vault.

You have been sent out to try and decipher this clue, and report back so that members may begin loading the capsules into the functional ship.
When you arrive at the site, you look around for the clue, until you notice a phrase written in the ceiling:

`difficult to glean info? even that oddness must mean somethin... no one asks why he came from, oh and where did he go to, that cotton eye joe, so elusive and so mysterious, lest joe come hither and explains thoroughly…`

Followed by a strange sequence of numbers:

`13 21 14 33 23 43 21 13 23 43 12 42 23`

Determined to crack this puzzle, you sit down and begin to think…

# Afterward

After reading the message over and over, you think over the meaning of “even that oddness must mean somethin’”. 

> Why is ‘somethin’ spelled so weirdly? Although strangely worded, this appears like a normal phrase, maybe something is encoded into a pattern within the sentence? Even, oddness… maybe it’s a pattern of even and odd-length words…? If there is one cipher I would use to encode a binary pattern, it would be Bacon’s cipher!

You begin to write out numbers corresponding to the evenness or oddness of the length of the words, 0 for even, 1 for odd:

`10100 01000 01010 00011 10000 01101 10001 00100`

This sequence happened to correspond to the word “WILDROSE”

> “Wildrose”

You say out loud, but nothing happens. 

>Hmmm, maybe it’s the key for that sequence of numbers below…

The numbers appears to be grouped into pairs of two, presumably each representing a letter.

> All the numbers seem to range from 1-5, and since they are in pairs, this does resemble the Polybius Cipher quite a bit. Let’s see if I can decipher these numbers using this key.

The “WILDROSE” key translates into the alphabet:

`WILDROSEABCFGHKMNPQTUVXYZ`

You then place the letters into a 5x5 grid, where the row number corresponds to the first number, and the column number corresponds to the second. Applying this to the encoded message results in the word:

`lodgepolepine`

>"Lodgepole pine” 

You say out loud. Suddenly, you start to hear a rumbling, and the door to the vault begins to open. You did it! You quickly switch the lever to close the door again, and then begin heading back to the secret base of the Cryptography Project so that you may begin moving the cryosleep capsules to your ship.



