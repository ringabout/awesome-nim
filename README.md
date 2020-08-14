# Awesome Nim [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome [Nim](https://nim-lang.org) frameworks, libraries and software. Inspired by other [awesome lists](https://github.com/bayandin/awesome-awesomeness).

## Contents

<details open >
  <summary title="Hide/Show">Table of contents</summary>

- [Async IO](#async-io)
- [Build Systems/Package Management](#build-systemspackage-management)
- [Byte Size](#byte-size)
- [CheckSums](#checksums)
- [Database](#database)
    - [Driver](#driver)
    - [ORM](#orm)
- [Date Time](#date-time)
- [Deep Learning](#deep-learning)
- [Design](#design)
- [Embedded](#embedded)
- [Game Development](#game-development)
- [GUI](#gui)
- [Editor](#editor)
- [Implementations](#implementations)
- [Macros](#macros)
- [Package Repositories](#package-repositories)
- [REPL](#repl)
- [Scripting](#scripting)
- [Services](#services)
- [IO](#io)
- [Text Processing](#text-processing)
    - [Translation](#translation)
    - [Template Engines](#template-engines)
- [Web](#web)
    - [HTTP server](#http-server)
    - [Websocket](#websocket)
    - [Web Frameworks](#web-frameworks)
    - [Parsing HTML](#parsing-html)
    - [Generating HTML](#generating-html)
- [Development Tools](#development-tools)
    - [Binding Generators](#binding-generators)
    - [Command-Line Interface Automation](#command-line-interface-automation)
- [Resources](#resources)
    - [Books](#books)
    - [Blogs](#blogs)
    - [Community](#community)
    - [Websites](#websites)
    - [Videos](#videos)
- [Contributing](#contributing)

</details>

## Async IO
* [nim-chronos](https://github.com/status-im/nim-chronos) - An efficient library for asynchronous programming. [MIT]

* [cps](https://github.com/disruptek/cps) - Continuation-Passing Style for Nim. [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

## Build Systems/Package Management

* [ChooseNim](https://github.com/dom96/choosenim) - Installing and switching between Nim versions (à la rustup, pyenv). [MIT]
* [Nake](https://github.com/fowlmouth/nake) - Describe your Nim builds as tasks. [MIT]
* [Nawabs](https://github.com/Araq/nawabs) - A build system that throws away version numbering in favor of git hashes. [MIT]
* [Nimble](https://github.com/nim-lang/nimble) - Nimble can be used as a build system. [BSD]
* [nimph](https://github.com/disruptek/nimph) - Nim package hierarchy manager from the future. [MIT]
* [nimby](https://github.com/treeform/nimby) - Nimby is a very simple and unofficial package manager for nim language.

[**&DoubleUpArrow;**](#contents "Go to the top")

## Byte Size

* [nim-bytes2human](https://github.com/juancarlospaco/nim-bytes2human#nim-bytes2human) - Calculate all Byte units from an integer, with precision from Bytes to Yottabytes, and return a human friendly string representation. [LGPL]

[**&DoubleUpArrow;**](#contents "Go to the top")

## Checksums

* [nim-crc32](https://github.com/juancarlospaco/nim-crc32#nim-crc32) - CRC32 for Nim, 2 proc, just pass the thing you want to do CRC. [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

## Database

### driver

* [nimongo](https://github.com/SSPkrolik/nimongo) - Pure Nim lang MongoDB driver. [MIT]


### orm

* [ormin](https://github.com/Araq/ormin) - Prepared SQL statement generator , A lightweight ORM.

* [nim-allographer](https://github.com/itsumura-h/nim-allographer) - A query_builder/ORM library inspired by Laravel/PHP and Orator/Python for Nim. [MIT]

* [nim-gatabase](https://github.com/juancarlospaco/nim-gatabase) - Connection-Pooling Compile-Time ORM for Nim. [MIT]

* [norm](https://github.com/moigagoo/norm) - Norm is an object-oriented, framework-agnostic ORM for Nim that supports SQLite and PostgreSQL.

[**&DoubleUpArrow;**](#contents "Go to the top")

## Date Time

* [nim-datetime2human](https://github.com/juancarlospaco/nim-datetime2human#nim-datetime2human) - Calculate date & time with precision from seconds to millenniums. Human friendly date time as string. ISO-8601. [LGPL]

[**&DoubleUpArrow;**](#contents "Go to the top")

## Deep Learning

* [Arraymancer](https://github.com/mratsim/Arraymancer) - A fast, ergonomic and portable tensor library in Nim with a deep learning focus for CPU, GPU, OpenCL and embedded devices. [Apache-2.0]
* [NimTorch](https://gitlab.fragcolor.xyz/fragcolor/nimtorch) - PyTorch - Python + Nim. A Nim front-end to PyTorch's native backend, combining Nim's speed, productivity and portability with PyTorch's latest implementations. [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

## Design

* [nim-random-font-color](https://github.com/juancarlospaco/nim-random-font-color#nim-random-font-color) - Random curated Fonts, pastel Colors and Seamless CSS3 Patterns for your UI/UX design, design for non-designers, poors man design. [LGPL]

[**&DoubleUpArrow;**](#contents "Go to the top")

## Embedded

* [msp430f5510](https://gitlab.com/jalexander8717/msp430f5510-nim) - Run Nim on MSP430f5510 micro-controller (6KB of RAM).
* [stm32f3](https://github.com/mwbrown/nim_stm32f3) - Run Nim on STM32F3 micro-controller (16KB of RAM).
* [ardunimo](https://github.com/gokr/ardunimo) - Nim wrapper for Arduino + LinkIt ONE SDK by Mediatek.
* [ardunimesp](https://gitlab.com/NetaLabTek/Arduimesp) - Nim wrapper for Arduino ESP8266 framework + A tool for flash, compile and make the nim project into an Arduino project.

[**&DoubleUpArrow;**](#contents "Go to the top")

## Game Development

* [frag](https://github.com/zacharycarter/frag) - 3D Game Engine.
* [SDL2](https://github.com/Vladar4/sdl2_nim) - Wrapper for SDL 2. [MIT]
* [GLAD](https://github.com/Dav1dde/glad) - Multi-Language Vulkan/GL/GLES/EGL/GLX/WGL Loader-Generator based on the official specs. [MIT]
* [nim-glm](https://github.com/stavenko/nim-glm) - Port of the popular glm C++ library to Nim. [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

## GUI

* [ui](https://github.com/nim-lang/iup) - Wrapper for IUP - Beginnings of what might become Nim's official UI library.
* [nim-kdialog](https://github.com/juancarlospaco/nim-kdialog#nim-kdialog) - Nim [Kdialog](https://techbase.kde.org/Development/Tutorials/Shell_Scripting_with_KDE_Dialogs) Qt5 Wrapper for Desktop. [LGPL]
* [nimAntTweakBar](https://github.com/krux02/nimAntTweakBar) - Wrapper for AntTweakBar.
* [nimx](https://github.com/yglukhov/nimx) - Desktop, Mobile & Web GUI framework in Nim.
* [NiGui](https://github.com/trustable-code/NiGui) - cross-platform, desktop GUI toolkit [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

## Editor

* [moe](https://github.com/fox0430/moe) - Command line based editor. [GPL]

* [paravim](https://github.com/paranim/paravim) - A Vim-based editor for Nim. [Unlicense]

* [nim-noise](https://github.com/jangko/nim-noise) - Nim implementation of linenoise command line editor. [MIT]

* [editor](https://github.com/pseudo-random/editor) - A simple text editor written in Nim. [MIT]

* [Aporia](https://github.com/nim-lang/Aporia) - Text editor to get started with Nim easily (not maintained anymore).

* [Editor Integration](https://github.com/nim-lang/Nim/wiki/editor-support) - Official list of editor plugins for Nim.

* [Nim Playground](https://play.nim-lang.org/) - Code and run Nim online.


[**&DoubleUpArrow;**](#contents "Go to the top")

## Implementations

* [Nim](https://github.com/nim-lang/Nim) - Nim (formerly known as "Nimrod") is a compiled, garbage-collected systems programming language which has an excellent productivity/performance ratio. Nim's design focuses on efficiency, expressiveness, elegance (in the order of priority). [MIT] [website](http://nim-lang.org/)
* [Nlvm](https://github.com/arnetheduck/nlvm) - LLVM backend for Nim. [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

## Macros

* [cascade](https://github.com/citycide/cascade) - Method & assignment cascades for Nim, inspired by Smalltalk & Dart. [MIT]
* [gara](https://github.com/alehander42/gara) - Macro-based pattern matching library. [MIT]
* [pipe](https://github.com/5paceToast/pipe) - Pipe operator for Nim, as seen in functional languages. [MIT]
* [unpack](https://github.com/technicallyagd/unpack) - Sequence/object unpacking/destructuring. [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

## Package Repositories

* [Nim packages](https://github.com/nim-lang/packages) - List of packages for Nimble.
* [Nim package directory](https://nimble.directory/) - This service allows you to explore Nim packages known to Nimble.
It tests package installation and generates documentation using "nim doc".

[**&DoubleUpArrow;**](#contents "Go to the top")

## REPL

* [INim](https://github.com/AndreiRegiani/INim) - Interactive Nim Shell. [MIT]
* [jupyternim](https://github.com/stisa/jupyternim) - A Jupyter kernel for nim. [MIT]

## Scripting

* [Nimcr](https://github.com/PMunch/nimcr/blob/master/README.md) - Running Nim code with Shebangs.

[**&DoubleUpArrow;**](#contents "Go to the top")

## Services

* [Luntic](https://github.com/xxlabaza/luntic) - Lightweight REST in-memory discovery service. [Apache-2.0]

[**&DoubleUpArrow;**](#contents "Go to the top")

## IO

* [ioselectors](https://github.com/xflywind/ioselectors) - ioselectors plus for Nim. [Apache-2.0]
* [wepoll](https://github.com/xflywind/wepoll) - Windows epoll wrapper for Nim. [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

## Text Processing

* [regex](https://github.com/nitely/nim-regex) - Pure Nim regex engine with linear time match. [MIT]
* [glob](https://github.com/citycide/glob) - Pure library for matching file paths against Unix style glob patterns. [MIT]
* [nim-datauri](https://github.com/juancarlospaco/nim-datauri#nim-datauri) - Data URI Base64 UTF-8. [LGPL]

[**&DoubleUpArrow;**](#contents "Go to the top")

### Translation

* [nim-tinyslation](https://github.com/juancarlospaco/nim-tinyslation#nim-tinyslation) - Text string translation from free online crowdsourced API. [LGPL]

### Template Engines

* [smalte](https://github.com/roquie/smalte) - It is a dead simple and lightweight template engine. Specially designed for configure application before start in Docker. [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

## Web

### HTTP server
* [httpx](https://github.com/xflywind/httpx) - Cross platform web server for Nim. [Apache-2.0]
* [httpbeast](https://github.com/dom96/httpbeast) - A highly performant, multi-threaded HTTP 1.1 server written in Nim. [MIT]
* [GuildenStern](https://github.com/olliNiinivaara/GuildenStern) - Genuinely multithreading integrated HTTP/1.1 + WebSocket v13 Server for POSIX-compliant OSes. [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

### Websocket

* [websocket.nim](https://github.com/niv/websocket.nim) - Websockets for nim.
* [ws](https://github.com/treeform/ws) - Simple WebSocket library for nim.


### Web Frameworks

* [Jester](https://github.com/dom96/jester) - The sinatra-like web framework for Nim. Jester provides a DSL for quickly creating web applications in Nim. [MIT]

* [prologue](https://github.com/planety/prologue) - Full-Stack Web Framework written in Nim. [Apache-2.0]

* [rosencrantz](http://andreaferretti.github.io/rosencrantz/) - DSL to write web servers, inspired by [Spray](http://spray.io/) and its successor [Akka HTTP](http://akka.io).

* [whip](https://github.com/mattaylor/whip) - Simple fast http server for nim based on httpbeast and nest for high performance routing.

* [basolato](https://github.com/itsumura-h/nim-basolato) - A fullstack web framework for Nim based on Jester.


* [Karax](https://github.com/pragmagic/karax) - Framework for developing single page applications in Nim.

* [oauth](https://github.com/CORDEA/oauth) - OAuth library for Nim. [Apache-2.0]



[**&DoubleUpArrow;**](#contents "Go to the top")

### Parsing HTML

* [Nimquery](https://github.com/GULPF/nimquery) - Library for
  querying HTML using CSS selectors, like Javascript's
  `document.querySelector`. [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

### Generating HTML

* [HastyScribe](https://github.com/h3rald/hastyscribe) - Self-contained markdown compiler generating self-contained HTML documents. https://h3rald.com/hastyscribe

[**&DoubleUpArrow;**](#contents "Go to the top")

# Development Tools

## Binding Generators

* [Nimpy](https://github.com/yglukhov/nimpy) - Gen Python wrappers, call python from nim. [MIT]
* [Pymod](https://github.com/jboy/nim-pymod) - Gen Python C-API wrappers. [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

## Command-Line Interface Automation

* [cligen](https://github.com/c-blake/cligen) - Infer & generate command-line interace/option/argument parsers [MIT]
* [docopt.nim](https://github.com/docopt/docopt.nim) - Command-line args parser [MIT]
* [commandeer](https://github.com/fenekku/commandeer) - Provides a small command line parsing DSL (domain specific language) [MIT]

[**&DoubleUpArrow;**](#contents "Go to the top")

# Resources

## Books

* [Nim in Action](https://www.manning.com/books/nim-in-action) - Nim's first book
* [Nim Days](https://github.com/xmonader/nimdays) - A project to document my journey with nim with mini applications, libraries documented from A to Z and also to provide new Nim users with some extra in depth information.
* [Nimbus Handbook](https://status-im.github.io/nim-beacon-chain/auditors-book) - A comprehensive introduction to the Nim programming language.

[**&DoubleUpArrow;**](#contents "Go to the top")

## Blogs

* [Nim Blog](http://nim-lang.org/blog.html) - Official Nim blog.
* [Goran Krampe](http://goran.krampe.se/nim/) - Wrapping C, arduino, performance, links.
* [HookRace](https://hookrace.net/blog/nim/) - Blog with multiple articles on Nim.
* [Rants from the Ballmer Peak](https://gradha.github.io/tags/nim.html) - Posts on Nim and other languages.
* [Yuriy Glukhov's blog](https://yglukhov.github.io/) - Making and shipping a game in Nim
* [Araq's Musings](https://nim-lang.org/araq) - Blog on Nim from the creator himself.

[**&DoubleUpArrow;**](#contents "Go to the top")

## Community

* [The Nim forum](http://forum.nim-lang.org/)
* [The Nim IRC channel](http://webchat.freenode.net/?channels=nim)
* [The Nim Gitter channel](https://gitter.im/nim-lang/Nim)
* [The Nim Discord channel](https://discord.gg/ptW3Rb3)
* [The Nim mailing list](http://www.freelists.org/list/nim-dev)
* [The Nim SubReddit](http://reddit.com/r/nim)
* [The Nim Telegram](https://t.me/nim_lang)
* [The Nim Telegram on Spanish](https://t.me/NimArgentina)

[**&DoubleUpArrow;**](#contents "Go to the top")

## Websites

* [Nim Basics](https://narimiran.github.io/nim-basics/) - Tutorial for beginners and people just starting with Nim.
* [How I start](https://howistart.org/posts/nim) - Great guide going from 0 to a bf interpreter and then a bf to Nim compiler.
* [Learn Nim in Y minutes](https://learnxinyminutes.com/docs/nim/) - Whirlwind tour.
* [Nim by Example](https://nim-by-example.github.io) - Series of pages and examples for learning the Nim programming language.
* [Nim for Python programmers](https://github.com/nim-lang/Nim/wiki/Nim-for-Python-Programmers) - Guide to Nim for people with experience in Python.
* [Rosettacode:Nim](https://rosettacode.org/wiki/Category:Nim) - 100s of solutions for various tasks using Nim (Implementations available in other languages as well).
* [dev](https://dev.to/t/nim) - Nim blogs in `dev.io`.

[**&DoubleUpArrow;**](#contents "Go to the top")

## Videos

* [Nim official Channel](https://www.youtube.com/channel/UCDAYn_VFt0VisL5-1a5Dk7Q/videos) - Official videos introduce the powerful and interesting part in Nim language.

* [Nim for beginners][https://www.youtube.com/user/kiloneie/playlists] - This is a video series meant to teach people programming in Nim to people who have never programmed before, or are new to Nim.

* [Make a website with Nim](https://www.youtube.com/watch?v=ndzlVRWqT2E&list=PL6RpFCvmb5SGw7aJK1E4goBxpMK3NvkON) - This is a video series meant to teach people make a website with Nim
using `jester`.

* [araq twitch](https://www.twitch.tv/araq4k) - The live broadcast regarding Nim language.

* [disruptek twitch](https://www.twitch.tv/disruptek) - The live broadcast regarding Nim language.

[**&DoubleUpArrow;**](#contents "Go to the top")

# Contributing

Contributions are very welcome!

Please have a look at [CONTRIBUTING](https://github.com/VPashkov/awesome-nim/blob/master/CONTRIBUTING.md) for guidelines.

[**&DoubleUpArrow;**](#contents "Go to the top")
