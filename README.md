# Overview of my personal projects

Most of my projects are made in C++ and can be compiled with my, cloned as git submodule, Makefile [helper](https://github.com/Lecrapouille/MyMakefile) (because I hate so much CMake ...)
for Linux and MacOS (not for Windows) either as standalone application and/or libraries (so you can include them in your personal project).

I used to worked with [Scilab](http://www.scicoslab.org/) because my [father](https://github.com/jpquadrat/jpquadrat.github.io)
contributed to it. Now Scilab has passed away ... the King is dead, long live the King: Julia! Therefore my simulation projects are made in Julia and run in Jupyter notebook.
AFAIK the display is broken (but this is not my fault).

I always been impressed on how compact Forth interpreters are, I tried to impelement mine as scripting langage for my project but I do not recommend you to use it.

Else I also added my student projects (Delphi Borland) and my LaTeX slides (studies and internship reports) made in years 2001--2007 (mostly for nostalgy ^^). A recurrent theme in my projects was
simulation of city because of this particular project https://github.com/Lecrapouille/SimTaDyn/tree/release-EPITA-2004 mixing geographic system, spreadshet and Forth interpreter.

## Chromium Embedded Framework (CEF)

- https://github.com/Lecrapouille/gdcef : 

  A Godot 3.5 GDNative plugin (C++) using Chromium Embedded Framework to allow you adding a web browser
  in your 2D or 3D applications. Initialy made for the [Stigmee](https://github.com/stigmee) project but
  currently the most liked of all my projects 👋

- https://github.com/Lecrapouille/OffScreenCEF :

  Bind Chromium Embedded Framework with OpenGL and SDL. Proof of concept of feasability binding CEF with
  the Godot Engine.

## System Modeling Tools

- https://github.com/Lecrapouille/Statecharts :

  A Python script parsing PlantUML statecharts (state machine) scripts and generating the C++ code with
  their unit tests.

- https://github.com/Lecrapouille/TimedPetriNetEditor :

  A graphical application and C++ library for editing (timed) petri nets, (timed) graph events
  and GRAFCET. This tool is coupled with (max,+) algebra and can be used with Julia.

- https://github.com/Lecrapouille/MaxPlus.jl :

  Julia package allowing to do computations in the tropical algebra (max,+) and (min,+). An algebra where
  the plus and times operators are replaced by the maximum (minimum) and plus operators. This algebra is 
  used in modeling discrete systems modeling synchronizations as linear systems. This project is a portage
  of the Scilab toolbox.

## City based project

- https://github.com/Lecrapouille/Highway :

  An attempt of a C++ simulator for autonomous driving research.

- https://github.com/Lecrapouille/OpenGlassBox :

  A C++ library implementing the SimCity v5 simulation engine.

- https://github.com/Lecrapouille/SimTaDyn :

  A C++ graphical standalone application manipulating geographic information system like done with a spreadsheet.
  Undone project, I learnt back the C++ with this project, I shall clean it.

- https://github.com/Lecrapouille/Ecstasy :

  3D project made in Borland Delphi of a city with its traffic jam. Vehicle dynamics. Student project.

- https://github.com/Lecrapouille/CiudadSim

  Scilab Traffic Assignment Toolboxes. (I'm not the original author).

## Predictions

- https://github.com/Lecrapouille/GlobalWarming.jl :

  Basic signal processing in Julia about the global temperature to form my own opinion concerning the climate warming.

- https://github.com/Lecrapouille/covid19.jl :

  Implementation in Julia of my father's Covid-19 epidemic model and prediction.

## C++ Libraries

- https://github.com/Lecrapouille/MyMakefile :

  A Makefile helper that I'm using for compiling all my C++ projects.

- https://github.com/Lecrapouille/zipper :

  A C++ library for zipping and unzipping. I'm not the original author but the project was
  abandonned by his author and this repo is a continuation.

- https://github.com/Lecrapouille/OpenGLCppWrapper :

  A C++ library wrapping OpenGL Core profile routines. Based on the idea of Glumpy and Three.js
  projects.

- https://github.com/Lecrapouille/SimForth :

  C++ library for including a Forth interpreter inside your project.

- https://github.com/Lecrapouille/Profiler :

  C++ header file for helping you to profile your code source. Based on the youtuber TheCherno's idea.

- https://github.com/Lecrapouille/TerminalColor :

  C++ header file to allow you printing text in color on the console.

- https://github.com/Lecrapouille/MyLogger :

  Basic C++ logger for my projects.

- https://github.com/Lecrapouille/LinkAgainstMyLibs :

  Continuous integration project for checking if my library project can
  be linked by external project.

## Forth

- https://github.com/Lecrapouille/SimForth :

  My standalone Forth interpreter mostely for learning and used with SimTaDyn.
  It is slow and does not follow correctly the standard.

- https://github.com/Lecrapouille/GraphicsLessonInGforth :

  OpenGL and SDL tutorials for Forth. (I'm not the original author).

## Application projects

- https://github.com/Lecrapouille/ChessNeuNeu :

  C++ and Julia project to make neural network understanding chess rules.
  Undone project.

- https://github.com/stigmee :

  A decentralized and open source web browser and social network 3D.
  I initiate repositories, build system and CEF plugin for Godot. Afaik
  the project has stalled because the initial developpers left the project
  (and so am I).

- https://github.com/Lecrapouille/IslandedBrowser :

  Prototype of tool parsing your exported Firefox bookmarks and
  display them in 2D as a graph strcuture. Prototype for Stigmee project.

- https://github.com/Lecrapouille/Speedway :

  My first 3D game made in Borland Delphi as computer science student.

- https://github.com/Lecrapouille/BacASable :

  Repo for testing stuffs. I prefer grouping them inside a single repo
  than having several GIST files.

- https://github.com/Lecrapouille/MySlides :

  My PDF documents I made when I was a computer science student (in French).

- https://github.com/Lecrapouille/WebSiteGenerator :

  A HTML websites generator based on GNU M4 macros. A saggy ancestor tool totally outdated by the Markdown langage.

- https://github.com/Lecrapouille/MyWebSiteSrc :

  The code source of my website in M4 langage and parsed by WebSiteGenerator.

## My Configs

- https://github.com/Lecrapouille/DotEmacs :

  My Emacs config.

- https://github.com/Lecrapouille/MyBashPrompt :

  My bash prompt decorator.
