# Sonder / Syncrate

Under those names, I've grouped a set of projects I've accumulated during my search for the next tech-stack.
I've tried to recreate similar features using different emerging technologies in an effort to learn and evaluate them.

The functionality could be best described as a social network or reddit-clone with features like:
- posts (creation, viewing, listing)
- comments (creation, nesting)
- authentication

### Clojure + Fulcro
https://github.com/roterski/syncrate-fulcro
+ single language
+ full-stack framework
+ data normalization & serialization solved
+ extensive documentation
+ access to npm & jvm ecosystems

### Clojure + Luminus + Re-frame
https://github.com/roterski/syncrate-luminus-reframe
+ single language
+ functional programing -> less complexity
+ access to npm & jvm ecosystems
+ react components

### Typescript + Node Nest.js + Angular Xplat + RxJs
https://github.com/roterski/sonder-nestjs

https://github.com/roterski/sonder-xplat
+ single language
+ shared codebase for web and native
+ typescript -> great IDE support
+ similar structure for backend (nest) and frontend (angular) components
- RxJs as unifying async abstraction

### Elixir Phoenix + Angular
https://github.com/roterski/sonder-api

https://github.com/roterski/sonder-frontend
+ popularity (Angular)
+ batteries included
+ convention over configuration
- two languages -> more complexity


# Motivation

Tech-stack is the foundational choice of every startup. This initial decision is crucial because it's near impossible to switch it later in the game without investing vast resources required to recreate an existing product from scratch.
While technically, you could build the same functionality in any of Turing-complete programming language, the decisive differentiation lies in cost, time and complexity involved.

The tech stack choice affects:
- product complexity and comprehension
- feature development speed
- maintenance cost
- team, hiring
- scalability, performance

All of these on their own can determine the company's fate.

It's my goal as software engineer to keep my tool-set up to date with latest trends to gain the competitive edge and innovate the ways software is written.


# Goals

### Minimal Complexity
  - consistent abstractions throughout the full-stack
  - single language -> fewer concepts -> better comprehension  -> less communication churn
  - must be suitable for small teams developers
### Short Feedback Loops
  - the shorter the delay between change and observing its effects, the faster and more timely change can be
  - examples: Test Driven Development, REPL-driven development, Agile iteration
### Re-usability
  - composition -> reuse without increasing complexity
  - frameworks -> reuse of architecture
### Multi-platform
  - to compete with big players
  - shared codebase -> sustainable for small teams

# Non-goals

### Familiarity
  - not limiting oneself only to known solutions
### Easy learning curve
  - willing to up-front invest in learning
### Popularity
  - helpful, but not a requirement
  - following masses doesn't give the competitive edge


# My Background

I approach this search from a position of my experience as a Software Developer in 4 startups. Each of them followed diverse technological and organizational decisions and I witnessed first-hand how each choice affects the company, the product, and its market potential. I've always kept my mind open for learning and aimed to understand the big picture with an end goal of starting a successful company of my own.


I started programming in 2012 with C++ in Robotics. Then I have lived through the evolution of web applications from Rails MVC, through first-generation SPA frameworks like Backbone, AngularJs and Meteor to modern Angular, React, Vue.

I have actively tried to stay on top of it - working with Rails and Node in daily jobs, experimenting with Angular and Meteor on weekends and evaluating React, Vue, Ember through their documentation in the meantime.
Following trends closely was a fascinating journey. I witnessed how different ideas compete with each other in an effort to innovate better ways of building applications.

After spending of +4 years working professionally with Ruby on Rails I've grown aware of its limitations. I've spent a long time searching for its successor in my programmer's toolbelt. I've waded through numerous Javascript frameworks yet every one of them proved to disappoint me after taking it for a spin.

I've finally arrived at Clojure at the beginning of 2019 and it has been really refreshing.
I love how well designed the language is, how mature the community is and I am amazed by the quality of the ecosystem.


# Conclusions
Ultimately, Software Engineering is all about managing complexity.

All the practices, conventions and architectures aim at reducing the cognitive load required to control the ever-growing project. The easier it is to make a change, the more flexible the product is. That's a powerful competitive edge.

I believe in the power of frameworks. They provide consistent architecture and abstractions allowing developers to focus on delivering business value. The idea of Convention over Configuration is truly empowering. And that's why I'm currently betting on Clojure's Fulcro.


