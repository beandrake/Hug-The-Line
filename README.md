# Hug The Line
During my internship at the Digital Future Lab, I worked as part of a small team developing the proof of concept for a new game and a Java API that could be used to make similar games.

<img align="center"  src="https://beandrake.com/resources/img/htl/htl_final.png" alt="An image of the game screen, showing UI elements and critters traveling a path with nearby wizards." />
<sup>An image of the game screen, showing UI elements and critters traveling a path with nearby wizards.</sup>

### Table of Contents ###
- [The Overall Team's Goal](#the-overall-teams-goal)
- [The Programming Team's Goals](#the-programming-teams-goals)
- [The Proof of Concept](#the-proof-of-concept)
- [The Java API](#the-java-api)
- [What is in this repository?](#what-is-in-this-repository)
- [Running the Game](#running-the-game)
- [Using the API](#using-the-api)
- [Credits](#credits)

## The Overall Team's Goal ##

Our team had an idea for a non-violent tower defense game, but would it work the way we envisioned?  More importantly, would it be fun?  Before moving into full-scale production, we set out to validate this vision by creating a proof of concept.  Our focus was to create a single simple level containing the game's fundamental mechanics.

Over the course of 9 months, our Agile team designed, implemented, and iterated on Hug The Line's gameplay and aesthetic.  Experimentation and rapid iteration were core aspects of our process, with potential features being prototyped and evaluated in sprints lasting only a few days.  This allowed us to fail fast and move on to more promising solutions.  Due to what we learned throughout these experiments, the overall project made numerous fundamental pivots over the course of development, each one a stepping stone towards better realizing the project's goals.

In the end, the proof of concept was considered a success.  The Digital Future Lab continued to develop the project towards a retail release under the new title SEED.

## The Programming Team's Goals ##

Hug The Line's programming team had two concurrent goals:

1. Work with the rest of our multidisciplinary team to produce the proof of concept for a game.
2. Design and implement a Java API that would allow others to easily make similar games.

Pair programming was employed for the majority of development.  The API was built on top of a rudimentary Java game engine, and the playable Hug The Line proof of concept was built using the API we created.  We also ended up making some improvements to the core functionality of the game engine, such as adding a visual layering system.

Both goals were successfully completed.

## The Proof of Concept ##

Hug The Line (HTL) is an inverted tower defense game where the player is tasked with preserving the lives of migrating Squibbles by strategically positioning helpful Wizards.

## The Java API ##

While Hug The Line subverts key elements of the tower defense genre, the Tower Defense API we programmed allows for the creation of any kind of tower defense game.  The API was planned to be used as part of early programming students' curricula, enabling instructors to guide students through basic programming concepts while providing the students with results that would be more engaging than a typical Hello World experience.

## What is in this repository? ##

This repository contains project files for:

- The proof of concept for the game Hug The Line, located in the `HugTheLine` directory.
- The Tower Defense Java API, located in the `HTL` directory.
- The improved game engine, located in the `GameEngine` directory.
- Several simple example projects that make use of the API, located in the `UserGame0` directories.

Notably, this repository is *not* the repository that was used during development, and it only contains the final release versions of the project files, rather than the full version history for the project.  The original development repository contained a variety of private data, so unfortunately it cannot be publicly shared.

## Running the Game ##
If you want to play the game, follow these instructions:

1. You'll need [`git`](https://git-scm.com/), [`the Java Development Kit`](https://www.oracle.com/java/technologies/downloads/), and [`Eclipse`](https://www.eclipse.org/downloads/packages/release/2026-03/r/eclipse-ide-java-developers), so install those if you need them. 

2. Make a local clone of this repository via your preferred method.

3. Open Eclipse.  If you are asked to select a directory for a Workspace, choose any directory or simply use the default.

4. Select `File` -> `Open Projects from File System...`

5. In `Import source`, navigate to the directory you cloned earlier (`Hug-The-Line`, by default) then click `Select Folder`.

6. You'll see a list of folders; unselect `Hug-The-Line`, then click `Finish`.  All of the important directories are now open in the Eclipse IDE under the `Package Explorer` tab.

7. To run the proof of concept of Hug The Line, under `Package Explorer` selet `HugTheLine`, then in Eclipse's menu select `Run` -> `Run`.

## Using the API ##
The UserGames are extremely simple tech demos intended to demonstrate different ways the Tower Defense API can be used.  If you've been able to run Hug The Line per the above instructions, you can use those same steps to highlight one of the `UserGame0` directories and run these demos.

The programming logic for UserGame01 can be found by navigating to `UserGame01\src\UserGame01.java`, with the other demos having their logic in similar locations.  Feel free to mess around and see what you can make!

The Javadoc documentation for the API can be read [here](https://beandrake.com/htl-api-documentation/), or you can peruse the files in their GitHub repository [here](https://beandrake.github.io/htl-api-documentation/).

## Credits ##

- **Creative Director:** Jason Pace
- **Producers:** Aina Braxton, Christina Jugovic, Hannah Kane
- **Design Leads:** Elliott White, Emmett Scout
- **Art Lead:** Nathan Evers
- **Lead Game/API Programmers:** Rachel Horton, Branden Bean Drake, Sandy Chau
- **Game Engine Programmers:** Jabediah Pavelas, Jack Chang, Daniel Azus, Fernando Arnez
- **Audio:** J.C. Ignacio
- **QA:** Cora Walker, Derek DeLizo
- **Project Coordinator:** Aina Braxton
- **Game API Advisor:** Michael Panitz, Kelvin Sung
