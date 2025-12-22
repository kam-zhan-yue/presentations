---
title: Make Coding Fun Again
author: Kam Zhan Yue
theme:
  name: catppuccin-frappe
options:
  end_slide_shorthand: true
---

A Brief History (of me)
===
![image:width:100%](images/chart-1.png)

<!--
speaker_note: |
Because this is more of a personal presentation, I thought it would be best that I share some personal stuff. 
After all, I haven't had the chance to talk to some of you before. So what better way to start than with my life story.
In my life, I'd say there were four major turning points.
-->
---------------------------

A Brief History (of me)
===
![image:width:100%](images/chart-2.png)

<!--
speaker_note: |
The first, obviously, was my first time playing Breath of the Wild. It was such an enchanting experience that it fully convinced me to pursue learning game dev.
-->
---------------------------

A Brief History (of me)
===
![image:width:100%](images/chart-3.png)

<!--
speaker_note: |
The second was meeting my now partner, which is primarily the reason why I moved to Japan. She's the best part of my day, every day.
-->
---------------------------

A Brief History (of me)
===
![image:width:100%](images/chart-4.png)

<!--
speaker_note: |
We don't talk about this one.
-->
---------------------------

A Brief History (of me)
===
![image:width:100%](images/chart-5.png)

<!--
speaker_note: |
And finally, LEARNING VIM BABYYYYYYY.
Now, I hear you say. Xan, how can a 30 year old plus text editor even equate to those things?
Is it because it lets you code with the comfort of never using a mouse again?
Or its numerous keybinds that make you feel blazingly fast?
Actually, the reason why I treasure Vim so much was because it did something unthinkable.
-->
---------------------------

<!-- jump_to_middle -->
<!-- alignment: center -->
_Vim made coding fun again._
===

--------------------------

<!-- jump_to_middle -->
<!-- alignment: center -->
I never liked coding.
===
I still kinda don't.

<!--
speaker_note: |
I never really liked coding. And I still kinda don't. It can be frustrating, draining, and sometimes just feels like a chore.
-->
--------------------------

![image:width:100%](images/greentext.png)

<!--
speaker_note: |
I mean how many of you can relate to this? You spend hours debugging and smacking your head against the wall fixing a bug.
But then, when you fix it, it's the best feeling in the world?

I love the end result. When you've made something amazing and can see people actually interacting with it the way you imagined.
I got that from games. Whenever I shared a creation with someone else and saw them having fun, I felt inspired to keep going.
-->

--------------------------

<!-- jump_to_middle -->
<!-- alignment: center -->
_"It was about the destination, not the journey"_
===
I told myself repeatedly.

<!--
speaker_note: |
Is what I would tell myself each and every day.
-->
--------------------------

<!-- jump_to_middle -->
<!-- alignment: center -->
_That was until... I learned Vim_
===

--------------------------

Xan glazes Vim for 10 minutes
===

<!--pause-->

# What is Vim?

<!--pause-->
 
Vim is a glorified text editor with keybinds you can intuitively chain together to make powerful combinations.

Before Vim, there was Vi (Visual Interface). Vim is simply Vi, IMproved.

![image:width:60%](images/vim-meme-1.jpg)

> DISCLAIMER: I don't use Vim, I use Neovim (and Vim motions, which are the powerful keybinds)


------------------------
# Why use Vim?

<!--pause-->

### The Keyboard is Faster
- If you are able-bodied with two hands, the keyboard is always faster for text-based operations
- Example 1: CTRL+C, CTRL+V for copy pasting instead of right click menu
- Example 2: F12 to go-to-definition instead of scroll click
- Anything your mouse can do, Vim can do better.

<!--pause-->

### Operation Chaining
- Everything in Vim is made to be chained together like natural language.
- `d2w` = delete word
- `cib` = change in bracket
- `vf.` = visual (select) until find a `.`
- The possibilities are endless!

<!--pause-->

### It's Cool
Real things people have said to me since using Vim
<!--pause-->
- _"Holy shit, how did you do that?!"_
<!--pause-->
- _"That's a cool looking editor"_
<!--pause-->
- _"Touch some fucking grass, you nerd"_

--------------------------

A Vim Demonstration
===

Now you might be asking, how does Vim work anyways? Is it magic?

<!--pause-->

Yes. Vim keybinds are magic.

<!--pause-->

### An Example - The `d` operator

Let's take a look at one of the most commmon Vim keybinds -> the `d` operator. As you might infer, `d` stands for `delete`.

<!--pause-->

Pressing `d` does nothing by itself. It needs other operators in order to function.

<!--pause-->

Maybe you're editing text and have the following train of thought:
1. This is the wrong word, I need to delete it.
2. Oops, I have to delete the next 2 words.
3. Ah shoot, this whole sentence blows, let's delete until the end.

<!--pause-->

In Vim, it would be:
1. `dw` = "delete word"
2. `d2w` = "delete 2 words"
3. `df.` = delete until you find a `.`

You can create endless chains of commands to accomplish the most detailed goals you have in your mind.

And the best part, there's not just one way to do things in Vim. 

--------------------------
 
Another Example - Changing Text in a Bracket
===

This is something that we as programmers do on a daily basis. Whether it's changing function parameters, text, markdown links, etc. Brackets are a part of our life.

<!--pause-->

```
obfuscate_text("A super secret password!", Encryption.CAESAR)
```

Let's say you want to change the arguments to this function. Without Vim, this is what you'd probably do:
1. Shift your hand from the keyboard the mouse / trackpad
2. Highlight the text
3. Replace / Delete

<!--pause-->

To replicate this behaviour in Vim, you can do:
1. Press `v` to enter visual mode
2. Highlight with motions like `hjkl` (move) or `w` (start of word) or `e` (end of word)
3. Press `c` to change

<!--pause-->

Or, chain commands together and skip steps entirely
`cib` => change in bracket

```
obfuscate_text()
```

<!--pause-->
What if you just wanted to change the text? Easy.
<!--pause-->
`ci"` => change in quotes `"`
```
obfuscate_text("", Encryption.CAESAR)
```

--------------------------
 
<!-- jump_to_middle -->
<!-- alignment: center -->
Finally, I can get to my point.
===

<!--
speaker_note: |
After that long explanation, I can finally get to the point I've been wanting to communicate this entire time.
-->
--------------------------
 
<!-- jump_to_middle -->
<!-- alignment: center -->
_It's not about Vim_
===
It never was.
<!--pause-->
I didn't find coding fun all of a sudden just because of a 30 year old text editor.
<!--pause-->
I already enjoyed coding, I had just become tired of it, day-in and day-out.
<!--pause-->
I was burnt out, and I needed something to remind me why I liked coding in the first place.

-------------------------

<!-- jump_to_middle -->
<!-- alignment: center -->
The Feeling of Learning Something New
===
It's the feeling of doing something you weren't able to do before.
It's the feeling of understanding something that you couldn't get before.

<!--pause-->
I believe that the most important value for an engineer is their curiosity to learn.

<!--pause-->
Even if you view programming as just a job, we're all engineers at the end of the day.

<!--pause-->
We admire a good cached recursive solution in linear time.
<!--pause-->
We adore type safety and cringe whenever we see `any`
<!--pause-->
We code for the love of the game.

-------------------------
 
<!-- jump_to_middle -->
<!-- alignment: center -->
Don't Stop Learning 
===

<!--pause-->
Learn the language that's piqued your interest for the longest time.
<!--pause-->
Play around with a new editor (nvim pls) and change things up a bit
<!--pause-->
Learn to love the tools we work with, because that's all we've got sometimes
<!--pause-->
--------------------------

<!-- jump_to_middle -->
<!-- alignment: center -->
Thank You
===
--------------------------
