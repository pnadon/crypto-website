---
layout: layouts/post.njk
title: A Loop In Time - UPDATED WITH ANSWERS
date: 2020-03-15T02:31:44.226Z
tags:
  - round_3
  - easy
---
![](/images/round_3_easy.jpg)

# Challenge

You and your fellow members of the Cryptography Project were taking a break, when suddenly someone runs up to you, and announces that the project will be performing a screening of members, before we all board the ship and leave Earth. The purpose of the screening is to filter out any aliens who have disguised themselves as humans using an advanced form of alien camouflage.

To screen out aliens, the members of the challenge are passing out a test which only humans should be able to understand, given that aliens don’t seem to understand ciphers very well. A member hands the challenge to you, which looks like the following:

*It wa**s** the year 2020. **M**ost students were **i**nside on accoun**t** of t**h**e terribl**y** **co**l**d** w**e**ather.* 
*It was already **q**uite **d**ark outside. The meeting fo**r** the cryptography club was running late. When every**o**ne was about to leave the rende**z**vous, an unu**s**ual thin**g** happened. All the **f**ire alarm**s** on campus went off at once, everyone's phones started buzzing fro**m** the emer**g**ency alert that was broa**d**cast. The pani**c** was visib**l**e on everyone's faces.*
*The power went off, unsettling d**a**rkness fille**d** every corner and nook of the city. The **d**rea**d**ful n**o**ir was prevale**nt** throughout the **sub**urbs, **t**o**r**menting those who l**ac**ked ba**t**teries.*

# Afterward

As you read over the challenge, you see that certain letters are bolded and stand out from among the other letters. You then realize that this could be a message that was hidden using a variant of Beaufort cipher (the “Smithy Code”), created by judge Smithy in the judgment trial for The Da Vinci Code. You write down all the letters which appear bolded, and see the message:

`smithycodeqdrozsgfsmgdcladddontsubtract`

This seems to form the phrase 

```
smithy code
qdrozsg fs mgdcl
add dont subtract
```

The Smithy Code works by offsetting the letters in the encrypted message using the fibonacci sequence which (if you wanted to decipher the message) you would subtract from the encrypted letter. In this case however, the message seemed to hint at the opposite, and after following these steps you ended up with:

`RETREAT AT NIGHT` 

Clearly, this is a message which hints that the Cryptography Project team should escape tonight, leaving any aliens who couldn’t solve the challenge behind.

The following morning, the group is short of one member, indicating the presence of an alien who was unable to solve the SMITHY CODE.

