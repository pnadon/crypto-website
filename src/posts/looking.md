---
layout: layouts/post.njk
title: Secret in the Abandoned City - UPDATED WITH ANSWERS
date: 2020-02-22T07:01:41.273Z
tags:
  - round_2
  - easy
---
![](/images/find_planet.jpg)

# Challenge

Humanity is hanging by the last thread. Survival is getting more and more difficult everyday. You are now a part of ‘The Cryptography Project’, a project which is made up of a few people still alive. You have been split into teams, and the one that you are part of has been assigned to look into the recent findings of a strange scientist, Doc. Vader. Doc. Vader claims to have found some information regarding an inhabitable planet from some ancient texts of the year 2025, which could potentially offer a solution to humanity’s bleak present.

Doc. Vader resides in the old Lab in the ‘Abandoned city’, which is the only surviving structure that still holds some of the pre-apocalypse texts and information. After travelling for three days, hiding and running from the aliens, you reach the Lab at midnight to meet Doc. Vader.

As you walk in, you see a number plate and see a set of 6 characters changing fluidly:

`74SDL7...Z4SDLZ...ZRSDLZ...ZRS9LZ...`

You keep walking further, and see Doc. Vader in a pool of blood.

> I don't have much time left, so listen carefully! The number plate may change, but in reality it is always the same! It is the secret to uncovering my secret, which is written here..." 

He whispers, and moves his hand towards you, which holds a piece of paper. Doc. Vader coughs, and then with his last breath, mumbles

> “Not A to Z... From A to T, then 0 to 9...”

After a moment of silence, you open his hand and find a ciphertext written on it:

`B0JE 2QR N8ST H6N T2`

It doesn’t make any sense at all. However, this piece of information is your last hope. Now you and your teammates have to find a way to decode this message and accomplish your mission.

# Afterward

You have two encrypted messages to solve and one clue each to solve them. You need to work step by step to get the information you need. 

Firstly, you have,

`74SDL7...Z4SDLZ...ZRSDLZ...ZRS9LZ...`

Doc Vader had indicated that the number plate changes, yet remains the same. You realize that all these combinations of numbers and letters are indeed the same. They are encrypted using the Homophonic cypher!

Using the table, you got the following:

```
7, Z → E
4, R → S
S →    C
D, 9 → A
L →    P
7, Z → E
```

Decrypted Key is: `E S C A P E `

The next clue you have is:

> “Not A to Z... From A to T, then 0 to 9...”

It sounds like Doc vader was trying to tell you that he had made some changes to a pre existing cipher to hide his message. Interesting… What cipher could originally use letters A to Z for decryption? You decide to try the Polyalphabetic vigenere cypher. Instead of using letters from A to Z, you use letters from A to T and then use numbers from 0 to 9 to make a table.

With `ESCAPE` as key, you end up with the following decrypted message:

`FILE H01 BASE LAB 12`

Yes! Finally you and your team cracked the encryption and retrieved the whereabouts of the coordinates of the habitable planet! They are in `FILE H01` in the `BASE LAB 12` in the Abandoned City! You have accomplished your mission!

