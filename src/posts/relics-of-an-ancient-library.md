---
layout: layouts/post.njk
title: Relics of an Ancient Library - UPDATED WITH ANSWERS
date: 2020-03-15T02:33:01.508Z
tags:
  - round_3
  - hard
---
![](https://i.pinimg.com/originals/86/57/13/8657132b076c9d91823c1329584d934b.jpg)

# Challenge

If you haven't done the Round 3 Easy and Medium challenges first, please do so for the story to make sense!

**Congratulations!! It's awesome that you could make it this far. Unfortunately a last leg of deciphering is still left, So welcome to the final chapter!!!**

Members of the cryptography project have received an intel that the last piece of the puzzle, the fuel for the ship, is hidden inside an ancient library. You being the smartest have been chosen to complete this task. After travelling for 3 days you finally find the library. The moment you walk in, you observe greek letters on the walls which looks like a direction to something. You follow the path and find a telephone directory. You observe that the book is something more than just a directory so, you read the title out loud to understand what it means:

> "The triplets
> **laala allal laaaa aaaaa aalll
> allaa aalaa laall alaaa alaaa alall
> alaal aalaa laala laall laall alaaa alall**
> together is a path to an ancient method."

What kind of a title is this, you think?
You open the book and a folded page slips down. You pick up the page and observe that it has numbers and dots embedded on it which are aligned symmetrically. You look carefully and see something like this:

```
 5     4     3     3     4     7     6     8     2     5     
...   ...   ...    ..   ...   ....   ..    .     .    ...  

9     2     9     7     3     2     7     9     2     8  
.     .    ...   ....   ..    .    ....  ...    ..    ..     

8     4     8     7     7     4     6     7     5     3
.    ...    .   ....  ....   ...    .     .    ...    ..  
```

After brainstorming for a while, you note down what the title and the numbers might decipher to and move forward.
The greek letters on the wall further lead you to a giant vault which presumably has what you were looking for, the fuel!!
You then notice a small message on the front panel of the vault which says:

> "Encryption is the key to where everything started and how it happened." 

What is this message, is it some kind of hint or a path to crack the password of the vault?
 
You are one step away to escape the doomed earth. Now it is all about making the right choice and thinking out of the box. You understand that at this point everything may not make sense and things might mislead but it is what it is, so you need to be confident about your approach.

Hint: Check out the submission form first, it will help walk you through the challenge! Keep in mind also that this is a hard challenge, **BUT** you can get partial points for completing some of the questions in the form!

# Afterward

In the library you find a telephone directory with the title

> "The triplets
> **laala allal laaaa aaaaa aalll
> allaa aalaa laall alaaa alaaa alall
> alaal aalaa laala laall laall alaaa alall**
> together is a path to an ancient method."

When you closely observe the text you see that the sequences of a's and l's correspond to a Bacon cipher which decrypts to `torah, neuiim, ketuvim` which are the triplets. You research and find that these words are parts of the Hebrew Bible. Since the words together lead to an ancient method, it leads you to one of the oldest ciphers known to humanity: `The Hebrew Cipher/ Atbash Cipher`.

Then a page slips from the book on which a sequence of numbers and dots are written. 
You get a hint that since the book is a telephone directory, numbers can be telephone numbers and dots somehow connect to that number. You research and find that the text is encrypted using the `Telephone Cipher/Phone Keypad Cipher`.

![](/images/keypad.jpg)

Upon decrypting using Telephone Cipher, each line results in the following:

The first line: `l i f e i s n t a l`

The second line: `w a y s e a s y b u`

The third line: ` t i t s s i m p l e`

Which combines to form the phrase `life isnt always easy but its simple`.

`Simple` seems to be a keyword from this phrase, and so you then look to the next hint:

>"Encryption is the key to where everything started and how it happened."

You think for a while and figure out that the phrase means encrypting `SIMPLE` using the Atbash Cipher, which is the key to the message `Lighthouse` (where everything started) and you need to decipher the message using the `Polyalphabetic Cipher` (how it happened). Following these steps you get the following:

Key: `HRNKOV`
Encrypted Message: `Lighthouse`
Cipher to use: `Polyalphabetic`
Password to the vault: `ERTXFMHDFU`

You test your answer by entering the combination on the keypad next to the vault, and sure enough it opens. That was definitely a hard challenge! You walk into the vault and see that the fuel is there, and close the vault again to go report your findings.