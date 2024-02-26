class: middle, center, title

# The Well Groomed Yak

## Thoughts on delightful productivity

### Ryan Parsley and Craig McCoy

#### 2024-02-27

???

Beyond the realm of standard Integrated Development Environments, this presentation uncovers hidden gems like shell scripts and multiplexers, proving that sometimes, the best solutions aren't the most obvious ones. We'll explore how simple tools can turn repetitive tasks into quick wins, saving time and sanity. This isn't just about new tools; it's about rethinking how we approach those pesky, recurring coding problems. Discover how stepping outside the IDE can lead to smarter, more efficient coding practices.

---

background-image: url(./assets/yakShaving.png)
background-size: 450px auto

# Yak Shaving!?

???

You signed up for a presentation with "yak shaving" in the title.

Thank you.

I want to level set what I mean when I say yak shaving because, it's become clear that there's 2 somewhat commonly accepted definitions and I only ever mean one of them. I'll start with what I don't mean when I say "yak shaving"

## Bikeshedding != Yak Shaving

When I say yak shaving, I don't mean bikeshedding.

Cyril Northcote Parkinson Yes, Parkinson's Law Parkinson
"work expands so as to fill the time available for its completion"

**Law of triviality** - people within an organization commonly give disproportionate weight to trivial issues.

## Yak shaving -> productivity you feel bad about

## Bikeshedding -> procrastination you feel good about

---

class: middle, center

> "Any apparently useless activity which, by allowing one to overcome intermediate difficulties, allows one to solve a larger problem." -[wiktionary](https://en.wiktionary.org/wiki/yak_shaving)

???

# Apparently

This is a pretty good definition.

Don't be misslead by **apparently**. It apears to be what it is not.

The key point is it "appears to be useless" while it's actually critical to success.

I guess _apparently_ is a fine word so long as you know know it's inacurate.

It's now always _critical_ to yak shave, but it can make the bigger task easier, faster, or simply more interesting.

# Delightful is valid

There's a strong assumption baked in to the premise of this.

- I genuinely enjoy shipping code.
- Wasting time is a bummer.

## You need to be sensitive to the difference between work and effort.

You may be busy, but are you getting work done?

That's what we're after here, this idea of delightful productivity.

## No one asked for this directly... but there's an implication.

To me, all the auxillary or meta work that you do so you can actually do what people ask for is the yak shaving.

# Value implied requirements

If you undervalue the importance of yak shaving it will bum you out. Burn out is real. Implied requirements arepart of the gig, celebrate those as you would shipping code because you can't ship code without these side quests.

# Knowledge work

I'm not intimately familiar with **Peter Drucker's** work directly, but it's cited a lot in content I consume.

Knowledge work can be differentiated from other forms of work by its emphasis on "non-routine" problem solving that requires a combination of **convergent and divergent thinking**.

---

# Things Developers tend to agree on

1. Repeating yourself is bad
2. Configuration as code is good
3. Bad abstraction is worse than no abstraction
4. Optimization is good
5. Premature optimization is bad
6. This meeting should have been an email
7. Repeating yourself is bad
8. Clean Code is an overrated book
9. Neovim is the best text editor of all time
10. Nothing matters less than whitespace but you will go fisticuffs over 8 space tabs

???

Maybe you don't agree with all of those points. Typography is actually very important.

# "My time is worthless" --No one, ever

No one is going to champion "I don't value time". We don't always see eye to eye on which activities are valuable though.

# Narcissm of minor differences

We have subjective differences but we share a lot of values. This is particularly evident when it comes to the importance/value of efficiency.

# Build your own lightsaber!

As such this presentation is less about trying to prescribe tools to you and more about drawing your attention to inefficiency you may take for granted.

Similar to Craig's last skill up on Personal Knowledge Management, make it personal. Collect tools that work for you. Then, passionately share your system for extracting yaml from markdown. I'm curious to see what you're into!

## Viva is not recommended for personal goals

You're on your own, and that's for the better. You do you!

---

# Automate all the things

- macros (keyboard maestro)
- window management
- snippets in your editor and beyond
- templates
- shell aliases
- shell scripts
- language scripts (rust, python)
- dotfiles

???

When I talk about automation, I mean anytime you save a few keystrokes by using technology.

I'll count copy/paste as a crude form of automation, but I know you're better than that.

Don't throw your hammer away because you get a drill, there will always be nails.

---

background-image: url(./assets/optimization.png)
background-size: auto 500px
background-position: 75% 80%

# Automate all the things

## but not too soon

???

DRY was here first, but there's a lot to be said for the tempered wisdom of WET

Write
Everything
Twice

Premature optimization is bad. Bad in app architecture and bad in the broader persuit of productivity.

Why? Because you are good at a lot of things, but predicting the future isn't one of them.

---

background-image: url(./assets/evolutionOfAutomation.jpg)
background-size: 450px auto

# Evolution of Productivity

???

Natural selection is considered the main mechanism that causes evolution.

Delight & Productivity should drive the evolution of your tools.

Replacing mindless monotony with a delightful script is a win even if the script doesn't save you a tone of time.

You're more engaged with the task at hand, you probably understand it better.

Just don't go overboard and remember that all of this is in service of shipping code people actually asked for.

---

background-image: url(./assets/gwh.jpeg)
background-size: auto 450px
background-position: 50% 80%

# Delightful Productivity

## the good stuff

???

When you can have both, that's the good stuff.

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

# Obsidian is good inspiration

If you're not familiar, checkout what the obsidian community is accomplishing with markdown.

- task management
- habit tracking
- journalling
- kanban boards feuled by yaml frontmatter

## I like my GUI

"But, editing a table in markdown is hard" Yes, so don't do that. Build the table from a csv or yaml something that's easy to maintain. Then, automate the generation of a table or chart.

## Does that web app have an api?

Azure devops has a CLI and REST API such that you can automate most of what you do via the webapp.

- Do you do similar things daily?

---

class: middle, center

# Assume there's a better way

???

# Laws of Thermodynamics do not apply to me!

As knowledge workers, we mostly deal with constructs of our own design. Code is not limited by physics. You don't need to work by a fire to write code about blacksmithing.

## Defining your job is part of your job

If parts of your job feel bad, consider part of your job is to fix that

Anecdote about making throw away apps for a startup and getting good at bootstrapping apps such that the tooling to generate apps was my "product".

# It's hard to document mouse interactions

1. do the thing
2. take a screenshot
3. draw a box around the important part
4. repeat indefinitely

---

background-image: url(./assets/efficiency.png)
background-size: 450px auto

# Be mindful of diminishing&nbsp;returns

???

# Balance, though

Sometimes there's a better way and you shouldn't chase it.

## Sayre's law

"In any dispute, the intensity of feeling is inversely proportional to the value of the issues at stake"

# Days of coding can save hours of planning

You won't always be able to quantify time saved, but be aware of that critical point where you're simply trading one class of busy work for another.

# I am not passionate about whitespace

I say about prettier that the only thing worst than prettier's defaults is not using prettier. Talking about whitespace on the internet is a fine hobby if you're into that, but it's a colossal waste of time in a PR.

Wire up prettier.

# If you're not passionate enough to change the defaults, make peace with them

If you feel passionate about it's defaults, configure them. If you don't feel passionate enough to learn how to configure prettier, you don't feel passionate enough to complain about it.

---

background-image: url(./assets/productivityTradeoffs.excalidraw.png)
background-size: 700px auto

# Be mindful of tradeoffs

???

# You make tradeoffs you're not aware of

The small sharp tools at the top of this chart are sort of the standard lib of productivity. You can count on them being on most computers or it's trivial to assure that they are.

As you move down to the yellow zone, you're mostly just abstracting over the previous toolset. Nx generate is a presumptuous set of opinions to turbo charge templates.

# There is power in tight coupling

Being tightly coupled is often assumed to be bad, but it can be very powerful... but at a cost.

# Replacing a tool is not a failure

Every time you have gained value from a tool is not rendered null should you no longer be able to use it

All that benefit from your past is in the bank and changing your mind robs you of nothing.

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

???

As you can see here, I type a command and I'm ready to write this slide deck. I launch vim, but you can launch your editor of choice just as easy. Note the tab has a dev server hosting the deck locally.

---

# Problem

## Who is responsible for install!?

???
One bit of friction with anytime installs is communicating what's changing and who is on the hook for validation. For a while, Match had a considerable amount of legwork daily by the build master and build manager to mitigate risk and communicate changes to production.

The build master was on the hook to do more or less the same task every day to facilitate communication around changes. This looks like a job for robots!

---

background-image: url(./assets/whoIsResponsible.png)
background-size: 450px auto

# Solution

## Shell Script in the pipeline

???
The final result looks like this. Every successful build has a chunk in the logs that lists the developers that commited code since the last deploy.

This started off with me automating the process for myself. If I was going to be occasionally responsible for this context, I wanted to get it easily and fast. Once I wrote a shell script that did what I needed locally, It made sense to remove myself as a bottleneck for this data.

At first, I taught some devs how to run the script, but then it became obvious that there was a lot of value in having this information associated with any given build.

Why stop at shell script?

It was "good enough". You got to know when to hold them and know when to fold them.

There is a trusted source of truth bound to every build. We _could_ do more. We could automate a daily email. We could drop the log into a team chat. We have collected the data and compiled it into something human readable. Should we need more, this is ready to evolve further.

---

background-image: url(./assets/commitsInProd.png)
background-size: 750px auto

# Implementation

???

A thing that took hours a day to collect and communicate is added to every build in about a second

---

background-image: url(./assets/releaseChecklistTime.png)
background-size: 450px auto

# Checklist

## Pipeline performance impact

???

The return on investment for such a change is exponential.

---

# Problem

## inconsistent node versions

???

There's a class of issues that come up when the same version of node isn't used.

This could range from false positive and negative builds, tests, and failures locally or in pipelines.

---

background-image: url(./assets/nvmrc.png)
background-size: 97%

# Solution

## .nvmrc -> nvm -> pipeline yml -> automated

???
It starts with recognition (people not using same versions of node, struggles, ci/cd, etc)

Someone writes down which version to use in wiki and communicates it to the team _see the copy and paste!_

You move to codifying version in .nvmrc

Everyone uses version locally with command (hey run nvm use! hey did you run nvm use?)

(use version in Ci/CD) (finally we have parity! we could stop here!)

automatically switch locally when changing folders (I Switch projects often)

---

background-image: url(./assets/nvmrc-combined.png)
background-size: 850px auto

???

Think about how we evolved in this example.

How did recognition drive our evolution?

---

# References

## Craig's templates

- [Recognition Template](./assets/problem-tracking.md)
- [Recognition Template - Obsidian](./assets/problem-tracking-obsidian.md)

## Tools I use

- [Zellij (multiplexor)](https://zellij.dev/)
- [Stow (helps manage dot files)](https://www.gnu.org/software/stow/manual/stow.html)
- [mise (polyglot version manager)](https://mise.jdx.dev/getting-started.html)
- [WezTerm (terminal emulator)](https://wezfurlong.org/wezterm/index.html)
- [Neovim (editor)](https://neovim.io/)
- [Remark (markdown powered slides)](https://github.com/remarkjs/remark)
- [Nushell (alternative shell)](https://www.nushell.sh/)

???

The real treasure was the yak we shaved along the way.

---

# See Also

- [Bikeshedding/ Law of Triviality](https://en.wikipedia.org/wiki/Law_of_triviality)
- [Narcissism of Small Differences](https://en.wikipedia.org/wiki/Narcissism_of_small_differences)
- [Knowledge Worker](https://en.wikipedia.org/wiki/Knowledge_worker#:~:text=Knowledge%20workers%20are%20workers%20whose,%22think%20for%20a%20living%22.)
- [A list of eponymous laws](https://en.wikipedia.org/wiki/List_of_eponymous_laws)
