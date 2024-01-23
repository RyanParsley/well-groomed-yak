class: middle, center, title

# The Well Groomed Yak
## Thoughts on delightful productivity
### Ryan Parsley and Craig McCoy
#### 2024-02-26

???

Beyond the realm of standard Integrated Development Environments, this presentation uncovers hidden gems like shell scripts and multiplexers, proving that sometimes, the best solutions aren't the most obvious ones. We'll explore how simple tools can turn repetitive tasks into quick wins, saving time and sanity. This isn't just about new tools; it's about rethinking how we approach those pesky, recurring coding problems. Discover how stepping outside the IDE can lead to smarter, more efficient coding practices.

---

background-image: url(./assets/yakShaving.png)
background-size: 450px auto

# Yak Shaving!? 

???

You signed up for a presentation with "yak shaving" in the title. Thank you. If you are not familiar with the phrase, that's at least twice as weird, but just to make sure we're all on the same page.

---

class: middle, center

> "Any apparently useless activity which, by allowing one to overcome intermediate difficulties, allows one to solve a larger problem."
> -[wiktionary](https://en.wiktionary.org/wiki/yak_shaving)

???

This is a pretty good definition. I don't know about "apparently useless". I guess _apparently_ is a fine word so long as you know know it's inacurate. Did you play Breath of the Wild or Tears of the Kingdom? Software development is a lot like that.

Sure, the epic is about defeating ganon, but you're gonna have to farm a lot of apples along the way. You can't do the main quest without some number of sidequests. And you may find you spend a disproportionate amount of time on the sidequests... That's the gig.

To me, all the auxillary or meta work that you do so you can actually do what people ask for is the yak shaving.

This should be seen as potentially bad, but it's kind of like tech debt in that you need to make peace with a certain amount of it and understand that everything comes at a cost. Be mindful of that.

---

# Things Developer's tend to agree on

1. Repeating yourself is bad
2. Configuration as code is good
3. Bad abstraction is worse than no abstraction
4. Optimization is good
5. Premature optimization is bad
6. This meeting should have been an email
7. Clean Code is an overrated book
8. Neovim is the best text editor of all time
9. Nothing matters less than whitespace but you will go fisticuffs over 8 space tabs

???

Maybe you don't agree with all of those points. Typography is actually very important. 

We have subjective differences but we share a lot of values. This is particularly evident when it comes to the importance/value of efficiency. No one is going to champion "I don't value time". We don't always see eye to eye on which activities are valuable though.

As such this presentation is less about trying to prescribe tools to you and more about drawing your attention to inefficiency you may take for granted.

---

# Automate all the things

- snippets in your editor and beyond
- shell scripts
- macros (keyboard maestro)

???

When I talk about automation, I'm not talking Unit tests or home kit. I mean anytime you save a few keystrokes by using technology. 

I'll count copy/paste as a crude form of automation, but I know you're better than that.

---

# Automate all the things
## but not too soon

???

DRY was here first, but there's a lot to be said for the tempered wisdom of WET

Write
Everything
Twice

Premature optimization is bad. Bad in app architecture and bad in the broader persuit of productivity. Why? Because you are good at a lot of things, but predicting the future isn't one of them.

---
background-image: url(./assets/evolutionOfAutomation.jpg)
background-size: 450px auto

# Evolution of Productivity

???

It's sort of an evolution. It's just that you don't want to race to the right side of this like may be implied.

---

class: middle, center

# Recognition
## out performs Precognition

???

I assert that the skillful persuit of automation is a game about pattern recognition, not precognition. Be frustrated by tedium.

---

class: middle, center
# A lot of tasks are _just_ text manipulation

???

Maybe a good time to talk about how tabular data could not be in excel, but frontmatter in markdown or nod to dataview in obsidian.

---

class: middle, center

# Assume there's a better way

???

As knowledge workers, we mostly deal with constructs of our own design. Code is not limited by physics. You don't need to work by a fire to write code about blacksmithing. If parts of your job feel bad, consider part of your job is to fix that

Anecdote about making throw away apps for a startup and getting good at bootstrapping apps such that the tooling to generate apps was my "product".

---

background-image: url(./assets/efficiency.png)
background-size: 450px auto

# Be mindful of diminishing returns

???

You won't always be able to quantify time saved, but be aware of that critical point where you're simply trading one class of busy work for another.

I say about prettier that the only thing worst than prettier's defaults is not using prettier. Talking about whitespace on the internet is a fine hobby if you're into that, but it's a colossal waste of time in a PR. 

Wire up prettier. 

If you feel passionate about it's defaults, configure them. If you don't feel passionate enough to learn how to configure prettier, you don't feel passionate enough to complain about it.

---

# Problem
## You need to spin up a bunch of tasks when you work on a project 

???

Project is vague here.

Maybe it's "write code for an app".

Maybe it's "document something".

Maybe it's collaborate on a slide deck for a presentation.

Are you context switching to make clacky sounds for a new reason... that counts.

---

class: middle, center

# Solution
## terminal multiplexer

???

For me, this context switching screams "multiplexor" and I'm going to walk you through what I mean by that. 

Maybe you have a cool plugin for VS Code.
Maybe you have a powershell script.

I like "Zellij" 

---

background-image: url(./assets/wat.gif)
background-size: 350px auto

# Multiplexer!?

???

Historically, a terminal multiplexer was a killer app to help with remoting into a server.They allow you to run multiple Linux programs over a single connection. I'm more into the the mulitple programs bit and less about the connection. I use them locally to automate spinning up processes I need to start my day. 

A couple of lines of yaml/json or toml in your home directory and a few keystrokes can drop you into a given directory, open your editor, spin up a dev server and start watching code changess to fire off tests. 

Tmux is by far the most popular solution for this. I've used it for years happily, but currently I'm using an alternative called Zellij. Either is great!

---

# Demo: Multiplexor

TODO: Put a gif or video here.

???

As you can see here, I type a command and I'm ready to write this slide deck. I launch vim, but you can launch your editor of choice just as easy. Note the tab has a dev server hosting the deck locally.

---
# Problem
## Who is responsible for install!?

???
Before we had this script, there was a considerable amount of legwork daily by the build master and build manager to mitigate risk and communicate changes to production.

The build master was on the hook to do more or less the same task every day to facilitate communication around changes. This looks like a job for robots!

---
# Solution
## Shell Script in the pipeline

???

Why stop at shell script?

It was "good enough". You got to know when to hold them and know when to fold them.

There is a trusted source of truth bound to every build. We _could_ do more. We could automate a daily email. We could drop the log into a team chat. We have collected the data and compiled it into something human readable. Should we need more, this is ready to evolve further.

---

# References

- [stylelint](https://stylelint.io/)
- [stylelint's SCSS standard config](https://github.com/stylelint-scss/stylelint-config-standard-scss)
- [SCSS Docs: Variables](https://sass-lang.com/documentation/variables)
- [Zellij](https://zellij.dev/)
- 
