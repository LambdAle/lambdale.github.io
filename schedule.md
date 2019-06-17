---
title: Schedule
---
<table id="schedule">
<tbody>

<tr>
  <td class="ba b--black-50">09:00</td>
  <td class="ba b--black-50"><span class="i">Registration</span></td>
</tr>

<tr>
  <td class="ba b--black-50">09:50</td>
  <td class="ba b--black-50"><span class="i">Opening speech</span></td>
</tr>

<tr>
  <td class="ba b--black-50">10:00</td>
  <td class="ba b--black-50"><a href="#keynote" class="b">Keynote - Simon Peyton Jones</a></td>
</tr>

<tr>
  <td class="ba b--black-50">10:45</td>
  <td class="ba b--black-50"><span class="i">Break</span></td>
</tr>

<tr>
  <td class="ba b--black-50">11:00</td>
  <td class="ba b--black-50"><a href="#talk1" class="b">Distributed Tracing in a purely functional world - Tamer Abdulradi</a></td>
</tr>

<tr>
  <td class="ba b--black-50">11:30</td>
  <td class="ba b--black-50"><a href="#talk2" class="b">"Stop ****ing up our language", porting the FP stack to Kotlin - Paco Estevez</a></td>
</tr>

<tr>
  <td class="ba b--black-50">12:00</td>
  <td class="ba b--black-50"><span class="i">Break</span></td>
</tr>

<tr>
  <td class="ba b--black-50">12:15</td>
  <td class="ba b--black-50"><a href="#talk3" class="b">What Happens If You Let The Creator of React Design a Programming Language - Flavio Corpa Ríos</a></td>
</tr>

<tr>
  <td class="ba b--black-50">12:45</td>
  <td class="ba b--black-50"><a href="#talk4" class="b">Picture combinators and recursive fish - Einar W. Høst</a></td>
</tr>

<tr>
  <td class="ba b--black-50">13:15</td>
  <td class="ba b--black-50"><span class="i">Lunch (buffet)</span></td>
</tr>

<tr>
  <td class="ba b--black-50">14:15</td>
  <td class="ba b--black-50"><a href="#talk5" class="b">Functional Programs for 3D Printing - Joseph Warren</a></td>
</tr>

<tr>
  <td class="ba b--black-50">14:45</td>
  <td class="ba b--black-50"><a href="#talk6" class="b">Algebraic programming with Dotty - Lander Lopez</a></td>
</tr>

<tr>
  <td class="ba b--black-50">15:15</td>
  <td class="ba b--black-50"><span class="i">Break</span></td>
</tr>

<tr>
  <td class="ba b--black-50">15:30</td>
  <td class="ba b--black-50"><a href="#talk7" class="b">No Garden of Eden - Adventures in Teaching Haskell to Kids - Peter Berger</a></td>
</tr>

<tr>
  <td class="ba b--black-50">16:00</td>
  <td class="ba b--black-50"><a href="#talk8" class="b">Do Parsers dream of Electric Guitars? - Ju Liu</a></td>
</tr>

<tr>
  <td class="ba b--black-50">16:30</td>
  <td class="ba b--black-50"><a href="#hallway" class="i">Hallway Track</a></td>
</tr>

<tr>
  <td class="ba b--black-50">17:30</td>
  <td class="ba b--black-50"><span class="b">Pub quiz!</span></td>
</tr>

<tr>
  <td class="ba b--black-50">18:00</td>
  <td class="ba b--black-50"><span class="b">Finish</span></td>
</tr>

</tbody>
</table>

## Talks

### Keynote

Title to be confirmed

Simon Peyton Jones ([Microsoft Research](https://www.microsoft.com/en-us/research/people/simonpj/))

#### About the speaker

Simon is a major contributor to the design of the Haskell programming
language,[9] and a lead developer of the Glasgow Haskell Compiler (GHC).

<a href="#schedule">^ Back to schedule</a>

<a id="talk1" />

### Distributed Tracing in a purely functional world

Tamer Abdulradi ([@tabdulradi](https://twitter.com/tabdulradi))

Collecting telemetry is crucial to understanding how your code is behaving in
production. However, in order to trace the execution across your system, a
correlation ID must be propagated throughout your systems. This could introduce
lots of boilerplate if done manually, yet doing it automatically remains an open
problem (and also the topic of this talk!)

In this talk, we’ll first introduce Distributed tracing, and explain a few
concepts behind it. Then we will tackle the problem of context propagation,
explaining some techniques to achieve it without much boilerplate. There will be
code samples using Scala, but the concepts apply to other functional programming
languages as well.

#### About the speaker

Tamer is a Principal Data Engineer at Just Eat. He has been building stuff with
Scala since 2012, and has written a few open source libraries. Most recently he
has been working on PureTracing, a library aiming to make instrumenting Scala
libraries easier.

Check Tamer’s tweets under [@tabdulradi](https://twitter.com/tabdulradi) and
posts at [abdulradi.com](http://abdulradi.com)

<a href="#schedule">^ Back to schedule</a>

<a id="talk2" />

### "Stop ****ing up our language", porting the FP stack to Kotlin

Paco Estevez ([@pacoworks](https://twitter.com/pacoworks))

[Arrow](https://arrow-kt.io/) is a Kotlin library that has brought support for
HKTs and type classes into the language. On top of that we have ported a good
chunk of the FP stack including comprehensions, lenses, recursion schemes, and a
blazing fast effects system. This enables experimenting with Haskell papers that
you can seamlessly run on your phone.

The other aspect of Arrow is that it’s already widespread in the industry and is
being used by startups and banks. It works on top of the vanilla Kotlin toolset,
so it is safe to bring into your JVM programs. Bring your favorite FP constructs
onto your day-to-day job!

#### About the speaker

On my day job at Facebook I collaborate with the best people in the business to
make the work more open and connected for the next billion users. In the past
I’ve worked experimenting with early prototypes and bleeding edge software,
at-scale video services, and a bit of video game development. One of these
challenges was applying functional concepts in the limited Android mobile space
to improve our workflows; and thanks to Kotlin we can have a great development
experience!

<a href="#schedule">^ Back to schedule</a>

<a id="talk3" />

### What Happens If You Let The Creator of React Design a Programming Language

Flavio Corpa Ríos ([@FlavioCorpa](https://twitter.com/FlavioCorpa))

React has come to stay, no doubt about it, and all the functional programming
concepts it brought back to life are getting traction not only in JavaScript,
but in other programming languages as well! Now, imagine if you could bring to
your React knowledge the advantages of a type safe, 100% functional language?
What would happen if you allow the creator of React.js to design a new
programming language? The answer to both question is: ReasonML, a new language
built on top of OCaml that will shake the foundations of modern frontend! We’ll
have an intro to Reason and see why it is a great idea!

#### About the speaker

Front-End Architect at European Union Intellectual Property Office (aka EUIPO)
enjoying some React + Redux. Contributor to many Open Source projects, such as
React/Angular 2/Babel. JavaScript Enthusiast and Passionate about new
technologies and frameworks.

<a href="#schedule">^ Back to schedule</a>

<a id="talk4" />

### Picture combinators and recursive fish

Einar W. Høst ([@einarwh](https://twitter.com/einarwh))

This is a live coding session based on a classic 1982 paper by Peter Henderson.
The paper shows the decomposition and reconstruction of Escher’s woodcutting
“Square Limit”, a beautiful recursive tessellation of interleaving fish, using
functional programming. If we think of a picture not as a collection of colored
pixels but rather as a function from a bounding rectangle to a rendering, we can
define very simple yet powerful picture combinators that allow us accomplish our
task with ease and elegance. Using Elm as the implementation language, we will
follow in Henderson’s footsteps to create a replica of Escher’s Square Limit as
an SVG.

#### About the speaker

Einar W. Høst is a computer at NRK, the Norwegian public broadcaster. He thinks
that programs should be written for people to read and also for machines to
laugh at.

<a href="#schedule">^ Back to schedule</a>

<a id="talk5" />

### Functional Programs for 3D Printing

Joseph Warren ([@hungryjoewarren](https://twitter.com/hungryjoewarren))

If you have access to a 3d printer, you will want to design printable objects.
As software developers, you may want to be able to design those objects in code.

This has a number of advantages. It is easy to version control, compared to
traditional modeling frameworks. It is also parameterisable, so you can have a
simple set of inputs that can be changed to quickly modify the object.

.While programmable CAD frameworks exist, such as OpenSCAD, they have
limitations. Objects in OpenSCAD are not first class and as such it isn’t
possible to use an object as a function’s argument, or to inspect the state of
an object, for example the size or position.

In this talk, I will introduce how and why I built my own Haskell library for
designing 3d objects, and what I learnt.

This talk will cover Constructive Solid Geometry (CSG); the form of solid
modeling used in this library. CSG defines complex objects by adding,
subtracting and intersecting simple ones.

The talk also discusses Binary Space Partitioning (BSP) Trees, a data structure
that makes implementing Constructive Solid Geometry functions easy.

When I started, I was hoping that Haskell’s lazy infinite lists could be
extended to define infinite objects. This turned out not to be practical, but
Haskell turned out to be a good choice for a number of reasons. Pure functional
languages are great for specifying solids, you can just write a description of
an object without worrying about side effects affecting it.  Using Haskell also
lets you define type classes on BSP trees. CSG operations such as
addition/intersection are associative; and thus CSG solids can be treated as a
monoid in two different ways.

#### About the speaker

I’m a software developer at Deliveroo. Writing Scala for money, and Haskell for
fun. I discovered coding ten years ago, and 3D printing two. I print everything
from plant pots to robots.

<a href="#schedule">^ Back to schedule</a>

<a id="talk6" />

### Algebraic programming with Dotty

Lander Lopez ([@landerlo](https://twitter.com/landerlo))

The talk will present ways in which FP languages could become more algebraic,
beyond ADTs, making product and coproduct composition extend to functions,
function application and the whole program structure.

The goal is to reduce boilerplate and make FP syntax more approachable and
expressive without compromising on any of the statically typed pure FP features
we love, parametricity, HKTs or effect systems.

In the example we analyse a common code pattern in Scala&Haskell where the
beginner needs to resort to Monad Transformers. We will show an “algebraic”
alternative with a much flatter learning curve and better type level
expressivity.

The code will be Scala Dotty, as it provides a good platform to showcase the
ideas in this talk, thanks to the new union and intersection type features.

#### About the speaker

A veteran of corporate software development, he found the FP way through Scala.

Since, he’s discovered many esoteric languages and developed a passion for
programming language theory.

<a href="#schedule">^ Back to schedule</a>

<a id="talk7" />

### No Garden of Eden - Adventures in Teaching Haskell to Kids

Peter Berger ([@peterb](https://twitter.com/peterb))

In his perhaps lighthearted 1975 paper “How do we tell truths that might hurt?”,
Edsger W. Dijkstra penned the aphorism “It is practically impossible to teach
good programming to students that have had a prior exposure to BASIC: as
potential programmers they are mentally mutilated beyond hope of regeneration.”
Whether intended humorously or not, this attitude is frequently echoed with a
straight face by some advocates of functional programming techniques or
languages; the idea being that if people find functional programming techniques
difficult, it is because they have been ruined, in some sense, through prior
exposure to imperative languages and practices.

As an experienced software engineer who regularly volunteers at local schools
introducing programming to teens and pre-teens, this question has some
significance to me. It’s a troubling attitude from a pedagogical standpoint,
because it suggests that it’s possible to “ruin” a young mind by choosing the
wrong technology, and also because it’s probably an impossible hypothesis to
either confirm or disprove. My instinct going in was that it probably takes a
lot of effort to ruin a young person’s ability to program, but it might take a
lot less effort to ruin their interest in programming. I wanted to know what
effect introducing “FP first” would have on both of these.

Every year for a number of years running I have volunteered and run workshops at
schools introducing kids to programming concepts via simple projects in
languages such as JavaScript, Lua, and Python. I set out to hold several similar
workshops solely using functional languages (notably Elm and Haskell) and
focusing on simple functional techniques. While the outcomes of these workshops
are by their very nature anecdotal, they resulted in a number of interesting
conversations with the young people about the strengths and weaknesses of the
languages, from their perspectives. Some of their observations are thoughtful, a
few are painful, and many are funny. I was also able to observe directly which
aspects of the languages, especially Haskell, were the biggest stumbling blocks.

I will present these findings in a conversational - and hopefully entertaining! - form,
suggest possible avenues for introducing functional techniques to young
learners, and call out the biggest risks of walking this path.

<a href="#schedule">^ Back to schedule</a>

<a id="talk8" />

### Do Parsers dream of Electric Guitars?

Ju Liu ([@arkh4m](https://twitter.com/arkh4m))

As a guitarist, I’ve always been fascinated by chords and their infinite
variations. In this talk, we’ll see how we can build a program that reads a
chord sheet, understands chords on a deeper level and finds ergonomic ways to
play them on a real guitar. We will do this using a simple parser using Elm and
show how much more powerful it is compared to a good old regular expression.
Then, we’ll see what it takes to teach our program how to play the ukulele. By
the end of the talk, you will have learned more of both music theory and
functional programming!

#### About the speaker

Ju was born in China, moved to Italy as a kid, grew up eating a lot of pasta,
and started messing around with computers. He now lives in London and works for
NoRedInk. He loves to solve interesting problems and build amazing products.
When he’s not doing that, he’s probably rock climbing.

<a href="#schedule">^ Back to schedule</a>

<a id="hallway" />

## Hallway Track

This year we are experimenting with an unconference-style session which we have
dubbed "Hallway Track". It will work as follows:

1. Everybody writes down a few topics that they are interested in. These could
   be programming languages, paradigms, libraries, etc.
2. We stick them all on a wall
3. Using highly sophisticated clustering techniques and consensus algorithms, we
   discover a few popular topics
4. Each topic is assigned a table, where people can gather to discuss
5. If any discussion runs its course, we'll replace it with a new topic
6. Before you know it, it'll be time for the pub quiz!

The most important rule is that you should Vote With Your Feet:

* Anyone is **free to join** any discussion, even if only as a listener.
* Everyone is **free to leave** a discussion and move elsewhere at any time.

<a href="#schedule">^ Back to schedule</a>

