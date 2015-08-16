# Project Euler; Scala Solutions
This is a little library to test your [Project Euler](https://projecteuler.net) solutions, using Scala. I put it
together a few years ago but think someone might still find it useful.

Its main feature is that you can run Specs2 to check your answers. It will only test the problems that you
have attempted. So if you only have attempted the first problem it will only test that one.

Since the Specs2 code sat dormant for almost three years everything was out of date and did not work
with the new versions. As often happens, I descended down the rabbit hole trying to figure out what was wrong.
Was it a bug in Specs2? Was it even working right three years ago? I spent far too much time down there and
when I came back up it turned out a simple change up top made the tests work again.

## Build Instructions

This is an SBT build, to run the tests run the SBT task:

    test

## Licensing

You are free to do anything you want with this code