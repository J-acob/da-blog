---
title: "My First Post"
date: 2022-09-19T22:31:21-07:00
draft: false
---

### First post

This is my first post ever. I've always wanted a blog. But the idea of posting random musings to the internet where essentially no one might read them was always *weird* to me.
This site is generated using [Hugo]("https://gohugo.io/") which is really cool so far. Ideally I'll actually be able to post a bunch of weird and funny stuff here that has to do
with software development. I want to learn a new language really badly, and not just to learn something new. But to learn something USABLE.

### A new language to learn??

I value a few *simple* things in a language

- **Easy to use**
  - The language should be easy to spin up a new project on if I'm just goofing around with a new project. ALSO it should scale well if it needs that.
- **Good Module/Plugin/Package/ETC Support**
  - I'm thoruougly uninterested in reinventing the wheel. So having a nice package manager which is full of nice resources and capabilities is a must.
- **Static Typing AND Type inference**
  - Ever since trying out [Typescript]([typescript](https://www.typescriptlang.org/)) for making a Roblox project, the ease of use that an algebraic type system can provide to my development workflow is uncanny.
  - Working in dynamically typed languages scares me. I really do feel like a fish out of water without the ability to see what the form of some data type is easily.
  Not being able to just click on the type of a variable and see exactly what is
  just not fun at all. I'm all for the fun and games of a dynamically typed language. But this just doesn't scale well in my experience.

- **Speed**
  - Admittedly, I don't care *that* much about speed. I don't often find myself working with systems low enough level to warrant serious speed considerations. Most high level languages will get the job done.
  Again, I care about the scaleability of a language a lot. Writing "hello world" should be (relatively speaking) just about as non-painful and easy to mentally work through as writing a parser in the language.
  - But, I do like speed. I shouldn't have to sit waiting for something to compile for ages, nor should I feel the hiccups and bumps from a goofy garbage collector during runtime.

### What languages then?

I *personally* have four langauges on my rader at the moment that I feel seriously strong about exploring as "driver language".

- ### Rust

  - I mean, really? This barely deserves a reasoning here. I wrote an implementation of [MapReduce](https://en.wikipedia.org/wiki/MapReduce) in Rust during undegrad and I had a lot of fun learning about the borrower model.
    I also worked a lot with C in undergrad and so I'm *very* familiar with essentially living in gcc and all the horrifying results of pointer arithmetic. So, the idea that there's a language this low level that can
    provide memory safety and a ton of other features (pattern matching, concurrency, etc) is totally insane to me. Recently [Linus torvalds announced Rust will be in the Linux Kernel](https://www.zdnet.com/article/linus-torvalds-rust-will-go-into-linux-6-1/). There's not a lot of other 'gold stars' a language can get beyond being given a place in the linux kernel. Not even c++ had that honor.
  - I really feel as if I'm seeing Rust pop up more and more every day. I really do need to sit and invest time and energy into this language to 'future-proof' myself for a future where Rust has scuttled itslf into
    Many places of the software engineering world.

- ### GO

  - Go seems cool. I think It's a good 'Driver' language since it has the capability to spin things up QUICK and allow rapid prototyping of new stuff. I don't know a ton about it if I'm being honest.
  But, I am excited and really like the gopher mascot they have.
  - Also, the tool I used to make this blog is built on top of GO! Very cool.. Very cool...

- ### Elixir

  - The functional programming bug bit me hard when I was taking a class about programming language fundamentals in undergrad. We learned a lot about functional programming by using [Elm](https://elm-lang.org/).
  Elm has a special place in my heart because of this. For most people, their first love is Haskell. But Elm had enough "crazy" features for me to fall head over heels. Things like pattern matching, [Maybe](https://package.elm-lang.org/packages/elm/core/latest/Maybe), function piping, etc showed me just how simple programming could really get.
  - All of that is to say that I really like well integrated functional language features, *alot*. So, elixir being a functional, fearlessly concurrent, and highly distributed programming languages is enticing as hell to me.
  - I haven't really been able to come up with any personal projects which would *need* this type of fault tolerance. But I'm sure I could find an excuse to use Elixir (and by extension, the popular [Phoenix Framework](https://www.phoenixframework.org/)).

- ### C\#

  - After all the excitment of the last three languages. It might be weird to see a language like C# here. But, this language is **Battle Tested**. Very much so. One of my favorite games, Terraria, was written in C# using the help the XNA game framework!
  - There's so many things that are written in C#. But it's missing a lot of features you might expect me to get excited about. So, for now I'll cautiously figure out where C# lives on my own personal stack.
  - Mainly, I want to try out [Blazor](https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor). This looks so cool. I also would need to learn .NET at some point as well, which is a whole other commitment to a language as well.
