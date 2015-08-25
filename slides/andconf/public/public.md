!SLIDE

# &:conf recap

### Anne DeCusatis, August 2015

##### @precisememory

!SLIDE

# What is &:conf? 

!SLIDE

&:conf, pronounced "and conf," is a 

## code retreat 

 and an 

## unconference 

 for 

## intersectional feminist 

programmers

###### (via https://www.andconf.io/)

!SLIDE

# code retreat

### Conway's Game of Life
### Pair programming
### Test-driven development
### 45 minute sessions, delete code after
### Arbitrary constraints

!SLIDE 

# unconference

###### talk about technologies, programming, careers, and culture. (via andconf.io)

### Proposed/voted on by attendees
### Four roles
#### Facilitator - lead the discussion
#### Gatekeeper - solicit feedback from quiet people (what if we did this in meetings?)
#### Timekeeper
#### Note-taker

!SLIDE

# intersectional feminist

##### Cultural patterns of oppression are not only interrelated, but are bound together and influenced by the intersectional systems of society. 
##### discrete forms and expressions of oppression are shaped by one another
###### (via Wikipedia)

!SLIDE

# why did I want to go? 

### I'm an intersectional feminist programmer
### I guessed (correctly) that a lot of people going to &:conf would be involved with Double Union
###### (Double Union is a feminist hackerspace in San Francisco. Three months ago, I started a Meetup group for MergeSort, a feminist hackerspace in New York.)


!SLIDE

# Day 0: Thursday, August 13

###### (My plane landed in SF in the early afternoon, and then)
### I visited Double Union & talked with people there.

!SLIDE

# Day 0 takeaways

##### When organizing a feminist hackerspace...

### Make spreadsheets to do cost analysis
### Don't go it alone
### Make your space inviting

!SLIDE

# Day 1: Friday, August 14

### I took a bus to the redwood forests of northern California, where &:conf was held

!SLIDE

### The highlight of Day 1 was that evening, the

# 90-second lightning talks. 

!SLIDE

## Some quick things I learned about on Friday night...

!SLIDE

Accessibility helps everyone - curb cut effect

!SLIDE

Belief in hard work is more of a predictor of success than belief in innate talent

!SLIDE

Outreachy 

!SLIDE

We Read Too 

!SLIDE

If you maintain a repo, give all PR contributors pull access - if you step down, the project doesn't die

!SLIDE

It's better to make a new Ruby gem that does exactly what you want than adapt one

!SLIDE

Appropriation, Assimilation, Appreciation, Allyship

!SLIDE

Let's incentivize solving hard socially important problems that aren't lucrative

!SLIDE

# Day 2: Saturday, August 15

### Pair programming

!SLIDE

# Conway's Game of Life

A zero-player game.

#### A grid of square cells, can be alive or dead based on:

##### A live cell with <2 neighbors dies
##### live, 2 <= neighbors <= 3 continues to next round
##### live, neighbors > 3 dies
##### dead, neighbors == 3 comes to life

!SLIDE

# Pair programming and test-driven development 

Ping-pong method: Your pair would write a failing test, you'd make it pass, then write a test for them. 

!SLIDE

# 45 minute sessions, delete code after

Five sessions, each self-contained with a new pair. 
(Not expected to finish the problem.)

!SLIDE

# Arbitrary constraints 

to get you to think about the process of writing code and collaborating.

!SLIDE

## "zombie cell" - last minute requirement added

!SLIDE

## no methods over three lines long and no if statements

!SLIDE

## No speaking to your pair - look at their code and how they write it

!SLIDE

## Evil pair - make your pair's tests pass in the least helpful way possible.

!SLIDE

# Takeaways from others

!SLIDE

"If it's hard to name something, your code's probably wrong." 

!SLIDE

"Senior devs without juniors make ugly choices - being forced to explain your rationale for doing things is helpful."

!SLIDE

"It was easier to accept a diversity of habits. Whitespace choices didn't matter, what mattered was the code."

!SLIDE

# Personal thoughts

!SLIDE

Pair programming was difficult for me because I was one of only two Java devs there, and we had to switch pairs each time. I ended up working in JavaScript and Python as well as teaching others how to use JUnit. 

!SLIDE

I think we should consider incorporating pair programming into our process. I found it really valuable, and in our current environment sometimes I feel bad about asking for someone's time to pair with me. 


!SLIDE

### Saturday evening, there were more

# 90-second lightning talks. 

###### (I gave one, too, on my Github project Gender Amender.)

!SLIDE

Take time to fix your tools so that you can do your best and most efficient work.

!SLIDE

Write specs, not tests. Tests connote failure, which is a loaded word. Tests are optional, specs aren't.

!SLIDE

Heisenbug - exists until observed

common law feature - "a bug your users have come to depend on"

smug report

shrug report

!SLIDE

"What if everyone falls asleep and I'm hungry??" Don't waste time worrying about things that might never happen, live in the present.

!SLIDE

Create a blameless culture where you can learn from your mistakes. Give an award to the best mistakes - e.g. Etsy's three-armed sweater.

!SLIDE

What's the path to advancement in technology without moving to management? We need people building who have been building for over ten years. 

!SLIDE

"Agile is just dudes high-fiving themselves because they've figured out communication matters to writing software!"

!SLIDE

# Day 3: Sunday, August 16

### Unconference 

###### I went to eight half-hour sessions.

!SLIDE

## How to stop thinking of yourself as a junior dev

###### The difference between a junior and senior dev isn't years, it's attitude. Recrimination vs confidence, knows when to ask for help

###### Having more abstract guidelines for seniority ("takes the lead") than specific years of experience was a good sign. 

!SLIDE

## Building technology that can understand inclusive naming

###### "Computers are really good at microaggressions" - they can deadname you over and over.

###### Many people don't have a legal ID that matches their preferred name.

###### This isn't some weird edge case that only affects trans people. Even if it was, still worth fixing.

###### Marginalized people online splinter their identity for safety reasons/don't have one "authentic self"

!SLIDE

## Inclusive naming, pt 2: suggestions

###### If you have to show legal name proof, only require it once, and don't keep copies of the ID after.

###### restrict frequency of name changes for trust/safety - harassment avoidance tools == tools for harassment

###### Don't separate first and last name in different text fields, don't try to parse it

###### Allow infinite length

###### Write a test suite for names

!SLIDE

## Staying technical as you advance

###### Dual ladder track/"architect" role available at large companies

###### Experienced devs can go into consulting, but they shouldn't have to deal with that if they don't want to

###### Do small companies need to solve the kind of hard problems that require an architect?

###### Management is different than architect because management involves people-paperwork and architect is about inter-team collaboration = a different kind of people skills

###### Having a higher title ("architect") might lead to more respect

!SLIDE

## Making big codebases less scary

###### What makes a codebase scary? Not just size

###### GHE search & grep, README, documentation can help (if it's a culture that supports documentation!)

###### tests are documentation, as are type annotations

###### Refactor inline to clean up things as you touch the code, teach new people by having them refactor

!SLIDE

## Functional programming

###### Elm -> compiles down to JavaScript

###### No secrets, no hidden state

### Resources

###### MIT intro to Racket/Lisp

###### Little Schemer (Scheme/Lisp)

!SLIDE

## What makes a great tech company?

#### Culture (management on your side, supportive env, autonomy over work, unlimited/min vacation day policy)

#### Social good

#### Business good (interesting problems vs work/life balance as a dichotomy)

### Good is determined by actions, isn't a binary state. 

### Good != perfect.

!SLIDE

## Finding culture fit when interviewing

###### Argumentative vs learning styles in PRs

###### Pair program on a one-day (paid) contract 

###### Talk to the people you'll be working with in interviews! 

###### "What does your typical workday look like?" "How do you get feedback on your work?" etc.

!SLIDE

## Diversity and Inclusion in the Workplace

###### Abstract out/appeal to a third party: "What if there was a guest?"

###### "listen first" culture

###### Express what you want as a win/win situation. Address problems sooner rather than later and in the least damaging way possible.

###### Be polite/politic. Ask for help from allies.


!SLIDE

# Final thoughts...

&:conf was a really valuable opportunity for me and I learned a lot there. 
I'm hopeful that we can have more discussions at my workplace on pair programming, writing tests and documentation, and creating a culture where everyone can thrive.

!SLIDE

# Acknowledgements

Thanks to Meetup for sponsoring this trip! Specific thanks to Jose and Dayna for logistical help!

Thanks to Lillie, Emily, and Stella for running &:conf!

Thanks to Jake for making sure nothing caught fire without me in the office!