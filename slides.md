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

You signed up for a presentation with "yak shaving" in the title. Thank you, ya wierdos. If you are not familiar with the phrase, that's at least twice as weird, but just to make sure we're all on the same page.

---

class: middle, center

> "Any apparently useless activity which, by allowing one to overcome intermediate difficulties, allows one to solve a larger problem."
> -[wiktionary](https://en.wiktionary.org/wiki/yak_shaving)

???

This is a pretty good definition. I don't know about "apparently useless". Did you play Breath of the Wild or Tears of the Kingdom? Code is a lot like that. There's a main quest and that's officially what it's all about. But you spend a lot of time on sidequests. To me, all the auxillary or meta work that you do so you can actually do what people ask for is the yak shaving.

This should be seen as potentially bad, but it's kind of like tech debt in that you need to make peace with a certain amount of it and understand that everything comes at a cost. Be mindful of that.

---

# Things Developer's tend to agree on

1. Repeating yourself is bad
2. Configuration as code is good
3. Bad abstraction is worse than no abstraction
4. This meeting should have been an email
5. Clean Code is an overrated book
6. Neovim is the best text editor of all time
7. Nothing matters less than whitespace but you fill fight anyone who disagrees with your preference

???

Maybe you don't agree with all of those points. Typography is actually very important. 

We have convictions.

We have differences in taste but we share a lot of values, particularly when it comes to the importance/value of efficiency.

---

# Automate all the things

- snippets in your editor and beyond
- shell scripts
- macros (keyboard maestro)

???

When I talk about automation, I'm not talking Unit tests or home kit. I mean anytime you save a few keystrokes by using technology. 

I'll count copy/paste as a crude form of automation, bit I know you're better than that.

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

---

class: middle, center

# Solution
## terminal multiplexer

---

background-image: url(./assets/wat.gif)
background-size: 350px auto

# Multiplexer!?

---

# References

- [stylelint](https://stylelint.io/)
- [stylelint's SCSS standard config](https://github.com/stylelint-scss/stylelint-config-standard-scss)
- [SCSS Docs: Variables](https://sass-lang.com/documentation/variables)
