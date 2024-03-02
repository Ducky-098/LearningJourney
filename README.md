# The Journey

| :zap: This document is meant for my own reference, you may read through it just know that it's probably not the easiest to read |
|---------------------------------------------------------------------------------------------------------------------------------|

## Step 1. The plan

The goal of the journey is to learn application development and software engineering through a series of projects that will expose me to a variety of software engineering practices.
So far the projects I have in mind are:

1. Note taking app
2. Website
3. Simple 2D Game
4. A LAN Chat service
5. Simple 3D Game
6. A discord bot

This is specifically ordered so I can use the previous project with the next one. The note taking app is first so I can take notes of my learning for reference on the next project. I could use other apps but none of them have the specific features I want (vim motions baked into the core navigation and not just a plugin, minimalist ui that hides unless a key is pressed).

The website will lead into the 2D Game because if I use Godot I can compile it to wasm and host it on the website. Same with the chat service I could then incorporate it into the 3D game and then I understand how multiplayer games with a chat work. 

The discord bot idea came about when I saw some of the cool rpg style discord bots where you're playing inside discord they looked fun.

---
## Step 2. The scope

One thing I need to be constantly aware of is making the scope of these projects too large. Right now they serve as a way to learn and practice my abilities to create software,
something I don't want to do is get hung up on adding advanced vim motions into the note taking app for example.

I should also take note of different technologies that I can use to trivialize a lot of the creation process, It would probably be very easy for me to download a library or engine that
could take away 90% of the problem solving and effort required. A good example of this would be the game engines of today I wouldn't need to learn how to make animations play on the screen,
or a framework like next.js that could prewrite the majority of the base code that I should learn.

---
## Step 3. The languages

I will be using a different language / technology for each project here. I want to expose myself to the intricacies of each language and understand what the best use of each one is.
At the moment I have decided on these languages:

* Rust - Note taking app
* Html/Css/Js - Website (no surprise there although once I have sufficient js knowledge I will be using typescript). I will be looking into other languages and frameworks as I progress I've been interested in Laravel for a while and some other backends like Django and Springboot
* C# - 2D Game (Godot or Monogame)
* Undecided - Lan Chat service (I'm tempted to try out OCaml here)
* Zig - 3D Game (No engines here, most likely using Raylib or SDL2)
* JS (Or a language that transpiles to JS) - Discord bot (I think you have to make discord bots in JS I haven't researched enough into it)

I'm not going to be using C/C++/Python/Go for the following reasons:
* C -- It's just a fair bit dated now and I've learned enough of it to understand the basics of memory management which imo is it's main usefulness now.
* C++ -- I don't like the lack of good build systems for the C siblings and I'd rather bash my head against the current problem than the not so great documentation of CMake 
* Python -- I like my delimiters and curly brackets and types they provide a good structure in my head when I'm working on a problem. Also indentation is just not my jam add on the fact that it's interpreted and I just can't see myself using python for anything but as a learning resource. Although I can see myself trying it out when I have a look at Django and I do want to dabble in machine learning, maybe I check out Mojo since they heavily market it as Python with types for use with ml 🤷
* Go -- I like Go and will return to it at a later date, I'm not using it for now mainly just because I haven't found a project I want to make with it.

---

## Step 4. The motivation

Right now my main motivation is to learn, I should really be focused on getting a job but for some reason I just can't seem to find the motivation to sit and study when I'm thinking about a job but I can focus for hours when I'm thinking about creating something interesting that I can use and play with. So instead of adding some arbitrary pressure on myself like "ohh I haven't learned enough the interviewer is gonna shoot me down instantly" I can instead go "I've made this part and it looks good, I'm finally putting something together", I feel like this will lead to a better and more productive journey. That isn't to say I shouldn't still keep the job search going I do need money after all and I can't be a slouch forever, I just need to keep the balance of pressure and sanity.

One thing I should be mindful about is my tendency to veer off into my thoughts, I need to put together some plan or tool that can be used to snap my focus back onto what I'm doing, too often I read a line of text which reminds me of a line in a comic or film or game and I'm suddenly going through the whole scene in my head and that just leads to guilt for not focusing and lack of productivity.

---
## Step 5. This document

This document will be the go to for accountability and a kick up the ass when needed. The repo will be public and although nobody will likely find it, the idea that people can come and see that I have been slacking off should be the push I need to keep at it. Another useful use of this readme is that as I learn more and more things I can come back and add my thoughts to it i.e. I might not like Zig or something and I can write down why and explain what I shall be using instead for that project, I will also format this document better as I learn more and more Markdown tags
