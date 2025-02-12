#

<p align="center">
  <a href="https://flame-engine.org">
    <img alt="flame" width="200px" src="https://raw.githubusercontent.com/flame-engine/forge2d/master/design/with-text.png">
  </a>
</p>

<p align="center">
  Forge2D - A Dart port of the Box2D physics engine
</p>

<p align="center">
  <a title="Pub" href="https://pub.dartlang.org/packages/forge2d" ><img src="https://img.shields.io/pub/v/forge2d.svg?style=popout" /></a> <img src="https://github.com/flame-engine/forge2d/workflows/Test/badge.svg?branch=master&event=push" alt="Test" /> <a title="Discord" href="https://discord.gg/pxrBmy4" ><img src="https://img.shields.io/discord/509714518008528896.svg" /></a>
</p>

The Box2D physics engine is a fairly famous open source physics engine and this is our Dart port of
it.

You can use it independently in Dart or in your [Flame](https://github.com/flame-engine/flame)
project with the help of [flame_forge2d](https://github.com/flame-engine/flame/tree/main/packages/flame_forge2d).

Some documentation of how to use it together with flame can be found
[here](https://flame-engine.org/docs/#/forge2d).


## Timeline

Box2D was first written in C++ and released by [Erin Catto](https://github.com/erincatto) in 2007,
but it is still maintained.

It was then ported to Java (jbox2d) by [Daniel Murphy](https://github.com/dmurph) around 2015.

Then from that Java port it was ported to Dart by [Dominic Hamon](https://github.com/dominichamon)
and [Kevin Moore](https://github.com/kevmoo).

A few years after that [Lukas Klingsbo](https://github.com/spydon) refactored the code to better follow the
Dart standard, since it still had a lot of reminiscence from C++.
After this refactor, we renamed it to Forge2D, as the upstream wasn't maintained to take in our
PRs.

There has also been countless other contributors which we are very thankful to!


## Credits

 * The [Flame engine team](https://github.com/orgs/flame-engine/people) who is continuously working
   on maintaining and improving Forge2D.
 * Special thanks for [Lukas Klingsbo](https://github.com/spydon), a Flame team member which took
   this project under his wing and greatly improved the project!
 * The Dart port of [Box2D](https://github.com/google/box2d.dart).
