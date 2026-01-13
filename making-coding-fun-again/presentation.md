---
title: Make Coding Fun Again
author: Kam Zhan Yue
theme:
  name: catppuccin-frappe
options:
  end_slide_shorthand: true
---

Presentation Outline
===
# Part 1: A Love Letter to Vim

> An introduction to the wonders of Vim

# Part 2: Self Sufficient Programming

> AKA: Xan goes off the rails for a little while

--------------------------

A Brief History (of me)
===
![image:width:100%](images/chart-1.png)

<!-- speaker_note: Because this is more of a personal presentation, I thought it would be best that I share some personal stuff. After all, I haven't had the chance to talk to some of you before. So what better way to start than with my life story. In my life, I'd say there were four major turning points.
-->
---------------------------

A Brief History (of me)
===
![image:width:100%](images/chart-2.png)

<!-- speaker_note: The first, obviously, was my first time playing Breath of the Wild. It was such an enchanting experience that it fully convinced me to pursue learning game dev. -->
---------------------------

A Brief History (of me)
===
![image:width:100%](images/chart-3.png)

<!-- speaker_note: The second was meeting my now partner, which is primarily the reason why I moved to Japan. She's the best part of my day, every day. -->
---------------------------

A Brief History (of me)
===
![image:width:100%](images/chart-4.png)

<!-- speaker_note: We don't talk about this one. -->
---------------------------

A Brief History (of me)
===
![image:width:100%](images/chart-5.png)

<!-- speaker_note: And finally, LEARNING VIM BABYYYYYYY. Now, I hear you say. Xan, how can a 30 year old plus text editor even equate to those things? Is it because it lets you code with the comfort of never using a mouse again? Or its numerous keybinds that make you feel blazingly fast? Actually, the reason why I treasure Vim so much was because it did something unthinkable.
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

<!-- speaker_note: I never really liked coding. And I still kinda don't. It can be frustrating, draining, and sometimes just feels like a chore. -->
--------------------------

![image:width:100%](images/greentext.png)

<!-- speaker_note: I mean how many of you can relate to this? You spend hours debugging and smacking your head against the wall fixing a bug. But then, when you fix it, it's the best feeling in the world? I love the end result. When you've made something amazing and can see people actually interacting with it the way you imagined. I got that from games. Whenever I shared a creation with someone else and saw them having fun, I felt inspired to keep going. -->

--------------------------

<!-- jump_to_middle -->
<!-- alignment: center -->
_"It was about the destination, not the journey"_
===
I told myself repeatedly.

<!-- speaker_note: Is what I would tell myself each and every day.
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
Why use Vim?
===

<!--pause-->

### The Keyboard is Faster
- If you are able-bodied with two hands, the keyboard is always faster for text-based operations
- Example 1: CTRL+C, CTRL+V for copy pasting instead of right click menu
- Example 2: F12 to go-to-definition instead of scroll click
- Anything your mouse can do, Vim can do better.

<!--pause-->

### Operation Chaining
- Everything in Vim is made to be chained together like natural language.
- `d2w` = delete two words
- `cib` = change in bracket
- `vf.` = visual (select) until find a `.`
- The possibilities are endless!

<!--pause-->

### It's Cool
Real things people have said to me since using Vim (nvim)
<!--pause-->
- _"Holy shit, how did you do that?!"_
<!--pause-->
- _"That's a dope editor"_
<!--pause-->
- _"Touch some grass, you nerd"_

--------------------------

A Vim Demonstration
===

Now you might be asking, how does Vim work anyways? Is it magic?

<!--pause-->

Yes. Vim keybinds are magic.

END OF TALK

--------------------------

An Example - Changing Text in a Bracket
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

To replicate this behaviour in Vim, you can do: 1. Press `v` to enter visual mode 2. Highlight with motions like `hjkl` (move) or `w` (start of word) or `e` (end of word)
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

> Want a quick intro? Do :VimTutor

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
 
_It's not about Vim_
===
<!-- jump_to_middle -->
<!-- alignment: center -->
It never was.
<!--pause-->
I didn't find coding fun all of a sudden just because of a 30 year old text editor.
<!--pause-->
I already enjoyed coding, I had just become tired of it, day-in and day-out.
<!--pause-->
I was burnt out, and I needed something to remind me why I liked coding in the first place.

-------------------------

It's about Learning
===
<!-- jump_to_middle -->
<!-- alignment: center -->
<!--pause-->
It's crunching through text with Vim,

Surgically manipulating branches and commits with jj,

Visualising graph problems in matplotlib,

Optimising renders with rxjs,

And so on...

--------------------------
 
So if you felt the same as me...
===

<!-- jump_to_middle -->
<!-- alignment: center -->
<!--pause-->
Learn the language that's piqued your interest for the longest time,
<!--pause-->
Play around with a new editor (nvim pls) and change things up a bit
<!--pause-->
Learn to love the tools we work with, because that's all we've got sometimes

-------------------------

<!-- jump_to_middle -->
<!-- alignment: center -->
Self Sufficient Programming
===
-------------------------

Disclaimer
===

<!-- jump_to_middle -->
<!-- alignment: center -->
> Everyone has their own goals and values in programming. It is good to have different values and debate. My way of thinking is not the only way of thinking and it does not have to apply to you.

-------------------------
A Thought Experiment
===

<!--pause-->
> Imagine you are on a 12 hour flight with nothing but your laptop. You want to code on a project you've been meaning to start for the longest time. You have no wifi, no AI tools, no one to ask for help. Can you do it?

<!--pause-->

My reaction:
- React? (maybe until i touch react-hook-form)
- Django? (i regularly forget how to iterate a dict)
- Core UI / CSS? (💀)
<!--pause-->
- A Unity Game? With my eyes closed.
<!--pause-->

But why?

<!--speaker_note: A month ago when I thought about this, I realised. If it were React or Django-related, honestly probably not. I relied on search engines and AI to help answer questions. But then I realised. I can probably make a Unity game in my sleep. I've done almost a hundred times, I can do it again. But why? -->

-------------------------
Cognitive Offloading
===

> Cognitive offloading involves using external tools to reduce the cognitive load on an individual’s working memory. While this can free up cognitive resources, it may also lead to a decline in cognitive engagement and skill development.

<!--pause-->

Examples include:
- Storing phone numbers in a Contacts app
- Using Google Maps to navigate back home
- Using a search engine to find research papers

<!--pause-->

Cognitive offloading is <span style="color: green">GOOD</span>
- We no longer worry about doing the menial things
- We can focus on more difficult, attention-demanding tasks
- We can achieve more, and at a faster rate

<!--pause-->

Excessive cognitive offloading is <span style="color: red">BAD</span>
- We begin to rely on remembering where to find information, not the information itself
- We intuitively blindly trust our devices
- We lose chances to practice honining our critical thinking

-------------------------
Rock Climbing and Programming
===

In rock climbing, things that help you climb are known as "aid".

"Aid" in programming essentially help with <span style="color: yellow">cognitive offloading</span>, abstracting problems away so you can focus on other things.

Evidently, I over-relied on "aid", to the point where I could not code without them.

-------------------------
LSPs
===

![image:width:80%](images/climbing-shoes.jpg)
- Help you navigate the cracks of the wall (codebase)
- Indispensable for modern climbing

-------------------------
IDEs
===

![image:width:80%](images/climbing-harness.jpg)
- Tries to prevent you from failing
- Extra safety features to keep you on the wall

-------------------------
Search Engines, Web Forums
===

![image:width:80%](images/belayer.jpg)
- Literally another person to assist you
- May shout good / bad advice at you

-------------------------
LLMs
===

<!-- jump_to_middle -->
<!-- alignment: center -->
_Literally climbs the wall for you._

-------------------------
God I wish that were me
===

![image:width:80%](images/alex-honnold.jpg)

-------------------------
An Aside - LLMs: The Worst Offender
===
Clearly, LLMs are the worst offenders of cognitive offloading and "aid".

<!--pause-->

| Feature | Implication |
| - | - |
| Writes code for you | You lose the muscle memory of syntax. | 
| Vibe <-> Review Cycle | You will not have the capacity to review everything. |
| Analyses the code structure for you | You lose the chance of discovering other functions and side-effects |

<!--pause-->

### Will does a good job of warning against AI usage already, but I want to emphasise:
> If you delegate too much thinking, you might just lose the ability to think.

-------------------------
You don't need aid.
===
<!--pause-->
## November 2024: Removed the file tree and tabs from my editor

<!--pause-->
- Forced to internalise file structure and tab management
- Built a stonger mental model of the codebase.

<!--pause-->
## December 2024: Uninstalled Claude Code, Copilot CLI, and deleted my ChatGPT account
- Syntax and patterns became second nature again
- Felt more comfortable coding independently and even offline

<!--pause-->
## January 2025: Learning to code without LSPs in Python and Rust
- Type hints from in-progress code adds visual noise and distractions
- Compiler and test output gives remarkable insight


-------------------------
Coding is fun again (for me).
===

- My code editor <span style="color: yellow">only has code</span>. No distracting windows, buttons, or popups.
- I'm not urged to <span style="color: yellow">search online for an answer immediately</span> after seeing something wrong.
- Most importantly, I'm <span style="color: yellow">enjoying the journey as well</span> as the destination. I love coding with my restrictions.

-------------------------
Make coding fun (for you).
===

You might have disagreed with everything I just said.

<!--pause-->
> And that's okay.

<!--pause-->

- Find values that resonate with <span style="color: yellow">YOU</span>
- Learn tools that interest <span style="color: yellow">YOU</span>
- Make code the way <span style="color: yellow">YOU</span> want

<!--pause-->

Coding is all we do, so we might as well have some fun doing it.

-------------------------
<!-- jump_to_middle -->
<!-- alignment: center -->
Thank You
===
