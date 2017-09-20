... WIP ...

# MOTIVATIONS

I worked during 3 years at [INGENICO](https://www.ingenico.com) France, developing apps, webos, bridges for the new [TELIUM TETRA SMART TERMINALS](https://www.ingenico.com/our-solutions/telium-tetra).

The fastest solutions was VanillaJS for sure...

I tried backbone, and the better solution was to use [Exoskeleton](http://paulmillr.com/exoskeleton) with [webpack](https://webpack.github.io) and [chaplinJS](http://chaplinjs.org).

I tried [ReactJS](https://facebook.github.io/react), and the better solution was [MithrilJS](https://mithril.js.org).

The problem was that MithrilJS did not cibling redraw and restart diff from root.

Other VDOM frameworks was slow or did code evaluation and other CSP issues.

That why i plan to create a JavaScript VDOM framework shorthand, tiny, extremely fast, with cibling redraw for development embeds.

But i changed my mind and decide to completly review the project and doing something more flexible, open, atomic and fully customizable...

Anyway the VDOM Framework is under development and will be release soon as a BrickJS project.

# GOALS
## Built-in solution for creating JavaScript projects based on Bricks (library, tools, frameworks, websites ...) for node and browser :
* Using Bricks (brick, projects / sub projects / API...) or whatever you name it.
* Using non BrickJS such as npm modules or other JavaScript code
* Using private and public domain


## Be fast and tiny
* Using old JS methods and good practices, benchmarking all you are doing.
* Using the smallest bundler that not produces useless code.


## Extend / Override / Define Polymorphism
* Using HOOKS (before and after brick)
* Using closure
* Using direct override
* Using importing modules
* Using bundler hooks
* Using bricks or bricks as a brick middleware
* Using extend brick
* Using Events
* Using config file

## Creating projects using included solutions :
* Using included website generator solution
* Using included pre-built configuration files solution
* Using included js code testing solution
* Using included test coverage solution
* Using included benchmark tool
* Using included bundler solution
* Using included custom build generator solution
* Using included boot strapped github apps and third party solutions
* Using a pre-define architecture solution

By the way you can use your own solution, it's up to you!

# WHAT IS A BRICK ?
A brick is simply a module or a set of modules which can contains methods and namespaces.

It is just a "plugin".

# WHAT IS A PROJECT ?
A project is composed by a set of bricks and non bricks (by the way you can convert all into a brick).

A project can contain sub projects.

It can also be your core.

# WHAT IS A SUB PROJECT ?
A sub project is composed by a pre define build of your projects which used a different set of bricks you have choose.

Or just pre define config file.

# THINKING BRICKJS

BrickJS is designed to be used in an atomic way.

That mean you should think like micro services architecture.

Every bricks could be used with each other.

That why your brick has to be splitted in multiple repository with one single method or multiple methods but not too much.

In this case, anyone can reuse your code and just bundle or checkout what he need not else more.

This is very important if you use brickJS as a unique bundle without importing modules manually.


# BUILD MY OWN CORE BASED ON BRICKS AND/OR PROJECTS

# FIND BRICKS

# FIND PROJECTS


# CREATE A BRICK

## Create my first Brick

## Create an advanced Brick


# NEXT

Build BrickJS tools, projects and bricks myself.

Build BrickJS tools, projects and bricks based on community help.

Build your own bricks and projects public or private!


# OBLIGATIONS
Include BrickJS credits and yours in all of your projects.

By the way it is done automatly by the bundler solution (later on).



