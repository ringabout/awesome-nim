# <a href="https://nim-lang.org"><img src="asset/awesome-nim-logo.svg" alt="Awesome-nim-logo" width="600"/></a><a href="https://awesome.re"><img align="right" src="https://awesome.re/badge.svg"></a>

> A curated list of awesome Nim frameworks, libraries, software and resources.

[Nim](https://nim-lang.org/) is a statically typed compiled systems programming language. Good for everything from shell scripting to web front & backend, to ML, HPC, and embedded.

## Contents

- [Async IO](#async-io)
- [Threading](#threading)
- [Build Systems/Package Management](#build-systemspackage-management)
- [System API](#system-api)
- [Web Application](#web-application)
- [Cryptographic](#cryptographic)
- [Parsers](#parsers)
- [Serialization](#serialization)
- [Database](#database)
    - [Driver](#driver)
    - [ORM](#orm)
- [Date Time](#date-time)
- [Benchmarking](#benchmarking)
- [Randomization](#randomization)
- [Data Processing](#data-processing)
- [Image](#image)
- [Audio](#audio)
- [Math](#math)
    - [Symbolic](#symbolic)
    - [FFT](#fft)
    - [Vector](#vector)
    - [Matrix](#matrix)
- [Deep Learning](#deep-learning)
- [Design](#design)
- [Embedded](#embedded)
- [Game Development](#game-development)
- [Logging](#logging)
- [Window](#window)
- [UI](#ui)
- [GUI](#gui)
- [Plot](#plot)
- [Terminal](#terminal)
- [Editor](#editor)
- [Implementations](#implementations)
- [Macros](#macros)
- [Package Repositories](#package-repositories)
- [Protocols](#protocols)
- [REPL](#repl)
- [Scripting](#scripting)
- [Services](#services)
- [IO](#io)
- [Compression](#compression)
- [Tests](#tests)
- [Text Processing](#text-processing)
    - [Translation](#translation)
    - [Template Engines](#template-engines)
- [Web](#web)
    - [UDP](#udp)
    - [RPC](#rpc)
    - [MQTT](#mqtt)
    - [HTTP server](#http-server)
    - [Websocket](#websocket)
    - [Web Frameworks](#web-frameworks)
    - [Parsing HTML](#parsing-html)
    - [Auth](#auth)
- [Markdown](#markdown)
- [Development Tools](#development-tools)
    - [Binding Generators](#binding-generators)
    - [Command-Line Interface Automation](#command-line-interface-automation)
- [Resources](#resources)
    - [Books](#books)
    - [Blogs](#blogs)
    - [Community](#community)
    - [Websites](#websites)
    - [Videos](#videos)


## Async IO
- [nim-chronos](https://github.com/status-im/nim-chronos) - An efficient library for asynchronous programming.
- [cps](https://github.com/disruptek/cps) - Continuation-Passing Style for Nim.


## Threading

- [weave](https://github.com/mratsim/weave) - A state-of-the-art multithreading runtime: message-passing based, fast, scalable, ultra-low overhead.


## Build Systems/Package Management

- [ChooseNim](https://github.com/dom96/choosenim) - Installing and switching between Nim versions (à la rustup, pyenv).
- [Nake](https://github.com/fowlmouth/nake) - Describe your Nim builds as tasks.
- [Nawabs](https://github.com/Araq/nawabs) - A build system that throws away version numbering in favor of git hashes.
- [Nimble](https://github.com/nim-lang/nimble) - Nimble can be used as a build system.
- [nimph](https://github.com/disruptek/nimph) - Nim package hierarchy manager from the future.
- [nimby](https://github.com/treeform/nimby) - Nimby is a very simple and unofficial package manager for Nim.


## System API

- [winim](https://github.com/khchen/winim) - Nim's Windows API and COM Library.


## Web Application

- [nitter](https://github.com/zedeus/nitter) - Alternative Twitter front-end.


## Cryptographic

- [nimcrypto](https://github.com/cheatfate/nimcrypto) - Nim cryptographic library.
- [nimAES](https://github.com/jangko/nimAES) - Advanced Encryption Standard, Rinjdael Algorithm written in Nim.
- [nim-crc32](https://github.com/juancarlospaco/nim-crc32#nim-crc32) - CRC32 for Nim, 2 proc, just pass the thing you want to do CRC.


## Parsers

- [parsetoml](https://github.com/NimParsers/parsetoml) - A Nim library to parse TOML files.
- [NimYAML](https://github.com/flyx/NimYAML) - YAML implementation for Nim.


## Serialization

- [nim-toml-serialization](https://github.com/status-im/nim-toml-serialization) - Flexible TOML serialization `not` relying on run-time type information.
- [nim-serialization](https://github.com/status-im/nim-serialization) - A modern and extensible serialization framework for Nim.
- [frosty](https://github.com/disruptek/frosty) - Marshal native Nim objects via streams, sockets.
- [nim-protobuf-serialization](https://github.com/status-im/nim-protobuf-serialization) - The nim-protobuf-serialization.
- [protobuf-nim](https://github.com/PMunch/protobuf-nim) - Protobuf implementation in pure Nim that leverages the power of the macro system to not depend on any external tools.


## Database

### Driver

- [nimongo](https://github.com/SSPkrolik/nimongo) - Pure Nim lang MongoDB driver.
- [asyncpg](https://github.com/cheatfate/asyncpg) - Asynchronous PostgreSQL driver for Nim.
- [anonimongo](https://github.com/mashingan/anonimongo) - Another Nim pure Mongo DB driver.
- [redis](https://github.com/nim-lang/redis) - Official redis wrapper for Nim.
- [amysql](https://github.com/bung87/amysql) - Async MySQL Connector write in pure Nim.
- [mycouch](https://github.com/hamidb80/mycouch) - Multisync CouchDB driver for Nim.


### ORM

- [ormin](https://github.com/Araq/ormin) - Prepared SQL statement generator , A lightweight ORM.
- [nim-allographer](https://github.com/itsumura-h/nim-allographer) - A query_builder/ORM library inspired by Laravel/PHP and Orator/Python for Nim.
- [nim-gatabase](https://github.com/juancarlospaco/nim-gatabase) - Connection-Pooling Compile-Time ORM for Nim.
- [norm](https://github.com/moigagoo/norm) - Norm is an object-oriented, framework-agnostic ORM for Nim that supports SQLite and PostgreSQL.


## Date Time

- [nim-datetime2human](https://github.com/juancarlospaco/nim-datetime2human#nim-datetime2human) - Calculate date & time with precision from seconds to millenniums. Human friendly date time as string. ISO-8601.
- [timezones](https://github.com/GULPF/timezones) - Nim timezone library compatible with the standard library.


## Benchmarking

- [golden](https://github.com/disruptek/golden) - A benchmark for compile-time and/or runtime Nim.
- [timeit](https://github.com/xflywind/timeit) - Measuring execution times written by Nim.
- [criterion](https://github.com/disruptek/criterion) - Statistic-driven micro-benchmark framework.


## Randomization

- [nim-random](https://github.com/oprypin/nim-random) - Random number generation library for Nim.
- [sysrandom.nim](https://github.com/euantorano/sysrandom.nim) - A Nim library to generate random numbers and random ranges of bytes using the system's PRNG.


## Data Processing

- [NimData](https://github.com/bluenote10/NimData) - DataFrame API written in Nim, enabling fast out-of-core data processing.


## Image

- [nimPNG](https://github.com/jangko/nimPNG) - PNG (Portable Network Graphics) decoder and encoder written in Nim.
- [nimpdf](https://github.com/jangko/nimpdf) - PDF document writer, written in Nim.
- [NimSvg](https://github.com/bluenote10/NimSvg) - The Nim-based DSL allowing to generate SVG files and GIF animations.
- [inumon](https://github.com/dizzyliam/inumon) - A high-level image I/O and manipulation library for Nim.
- [flippy](https://github.com/treeform/flippy) - Flippy is a simple 2d image and drawing library.
- [imageman](https://github.com/SolitudeSF/imageman) - Image manipulation library.


## Audio

- [paramidi](https://github.com/paranim/paramidi) - A Nim library for making MIDI music.
- [omni](https://github.com/vitreo12/omni) - A DSL for low-level audio programming.


## Math

### Symbolic

- [symbolicnim](https://github.com/HugoGranstrom/symbolicnim) - A symbolic library written purely in Nim.


### FFT

- [impulse](https://github.com/SciNim/impulse) - Impulse will be a collection of primitives for signal processing (FFT, Convolutions).


### Vector

- [vectorize](https://github.com/SciNim/vectorize) - SIMD vectorization backend.
- [vmath](https://github.com/treeform/vmath) - Math vector library for graphical things.


### Matrix

- [neo](https://github.com/unicredit/neo) - A matrix library.


## Deep Learning

- [Arraymancer](https://github.com/mratsim/Arraymancer) - A fast, ergonomic and portable tensor library in Nim with a deep learning focus for CPU, GPU, OpenCL and embedded devices.
- [NimTorch](https://gitlab.fragcolor.xyz/fragcolor/nimtorch) - PyTorch - Python + Nim. A Nim front-end to PyTorch's native backend, combining Nim's speed, productivity and portability with PyTorch's latest implementations.


## Design

- [nim-random-font-color](https://github.com/juancarlospaco/nim-random-font-color#nim-random-font-color) - Random curated Fonts, pastel Colors and Seamless CSS3 Patterns for your UI/UX design, design for non-designers, poors man design.
- [chroma](https://github.com/treeform/chroma) - Everything you want to do with colors, in Nim.
- [typography](https://github.com/treeform/typography) - Fonts, Typesetting and Rasterization.
- [trick](https://github.com/exelotl/trick) - Library for GBA/NDS image conversion, and more!


## Embedded

- [ardunimo](https://github.com/gokr/ardunimo) - Nim wrapper for Arduino + LinkIt ONE SDK by Mediatek.
- [ardunimesp](https://gitlab.com/NetaLabTek/Arduimesp) - Nim wrapper for Arduino ESP8266 framework + A tool for flash, compile and make the nim project into an Arduino project.
- [msp430f5510](https://gitlab.com/jalexander8717/msp430f5510-nim) - Run Nim on MSP430f5510 micro-controller (6KB of RAM).
- [Nesper](https://github.com/elcritch/nesper) - Program the ESP32 using Nim. Library on top of esp-idf.
- [stm32f3](https://github.com/mwbrown/nim_stm32f3) - Run Nim on STM32F3 micro-controller (16KB of RAM).


## Game Development

- [frag](https://github.com/zacharycarter/frag) - 3D Game Engine.
- [nico](https://github.com/ftsf/nico) - Nim Game Framework based on Pico-8.
- [nimgame2](https://github.com/Vladar4/nimgame2) - A simple 2D game engine for Nim.
- [godot-nim](https://github.com/pragmagic/godot-nim) - Nim bindings for Godot Engine.
- [rod](https://github.com/yglukhov/rod) - Cross-platform game engine.
- [natu](https://github.com/exelotl/natu) - Toolkit for writing Game Boy Advance games in Nim.
- [nimgl](https://github.com/nimgl/nimgl) - NimGL is a Nim library that offers bindings for popular libraries used in computer graphics.
- [SDL2](https://github.com/Vladar4/sdl2_nim) - Wrapper for SDL 2.
- [rapid](https://github.com/liquid600pgm/rapid) - A game engine written in Nim, optimized for rapid game development and prototyping.
- [GLAD](https://github.com/Dav1dde/glad) - Multi-Language Vulkan/GL/GLES/EGL/GLX/WGL Loader-Generator based on the official specs.
- [nim-glm](https://github.com/stavenko/nim-glm) - Port of the popular glm C++ library to Nim.
- [enu](https://github.com/dsrw/enu) - A Logo-like DSL for Godot, implemented in Nim.
- [nodesnim](https://github.com/ethosa/nodesnim) - Simple game engine based on SDL2 and OpenGL.


## Logging

- [nim-chronicles](https://github.com/status-im/nim-chronicles) - A crafty implementation of structured logging for Nim.
- [nim-morelogging](https://github.com/FedericoCeratto/nim-morelogging) - Logging library for Nim.


## Window

- [nimdow](https://github.com/avahe-kellenberger/nimdow) - A window manager written in Nim.
- [Nimwin](https://github.com/weskerfoot/Nimwin) - A Very Simple X11 Window Manager.


## UI

- [ui](https://github.com/nim-lang/iup) - Wrapper for IUP - Beginnings of what might become Nim's official UI library.
- [fidget](https://github.com/treeform/fidget) - Figma based UI library for Nim, with HTML and OpenGL backends.


## GUI

- [nimAntTweakBar](https://github.com/krux02/nimAntTweakBar) - Wrapper for AntTweakBar.
- [nimx](https://github.com/yglukhov/nimx) - Desktop, Mobile & Web GUI framework in Nim.
- [NiGui](https://github.com/trustable-code/NiGui) - The cross-platform, desktop GUI toolkit.
- [Neel](https://github.com/Niminem/Neel) - A library for making Electron-like HTML/JS GUI apps.
- [wNim](https://github.com/khchen/wNim) - Nim's Windows GUI Framework.
- [nimqml](https://github.com/filcuc/nimqml) - Qt Qml bindings for the Nim programming language.
- [webgui](https://github.com/juancarlospaco/webgui) - Web Technologies based Crossplatform GUI Framework with Dark theme.
- [gintro](https://github.com/StefanSalewski/gintro) - High-level GObject-Introspection based GTK3/GTK4 bindings for Nim.
- [nsciter](https://github.com/Yardanico/nsciter) - High-level and low-level Nim wrapper for https://sciter.com.


## Plot

- [ggplotnim](https://github.com/Vindaar/ggplotnim) - A port of ggplot2 for Nim.
- [nim-plotly](https://github.com/brentp/nim-plotly) - The plotting library for Nim.
- [graph](https://github.com/stisa/graph) - A basic plotting libiary in Nim.
- [npainter](https://github.com/mrgaturus/npainter) - Semi GPU-Accelerated painting software written in Nim.
- [pixie](https://github.com/treeform/pixie) - Full-featured 2d graphics library for Nim.


## Terminal

- [illwill](https://github.com/johnnovak/illwill) - Simple cross-platform terminal library inspired by (n)curses.
- [NimCx](https://github.com/qqtop/NimCx) - Color and Utilities for the Linux Terminal.
- [nicy](https://github.com/icyphox/nicy) - A nice and icy zsh and bash prompt in Nim.


## Editor

- [moe](https://github.com/fox0430/moe) - Command line based editor.
- [paravim](https://github.com/paranim/paravim) - A Vim-based editor for Nim.
- [nim-noise](https://github.com/jangko/nim-noise) - Nim implementation of linenoise command line editor.
- [editor](https://github.com/pseudo-random/editor) - A simple text editor written in Nim.
- [Editor Integration](https://github.com/nim-lang/Nim/wiki/editor-support) - Official list of editor plugins for Nim.
- [Nim Playground](https://play.nim-lang.org/) - Code and run Nim online.
- [DoongJohn's Nim playground](https://doongjohn.github.io/nim-playground/) - An alternative implementation of the Nim playground.


## Implementations

- [Nim](https://github.com/nim-lang/Nim) - Nim (formerly known as "Nimrod") is a compiled, garbage-collected systems programming language which has an excellent productivity/performance ratio. Nim's design focuses on efficiency, expressiveness, elegance (in the order of priority).
- [Nlvm](https://github.com/arnetheduck/nlvm) - LLVM backend for Nim.


## Macros

- [cascade](https://github.com/citycide/cascade) - Method & assignment cascades for Nim, inspired by Smalltalk & Dart.
- [macroutils](https://github.com/PMunch/macroutils) - A package that makes creating macros easier.
- [nimacros](https://github.com/FemtoEmacs/nimacros) - Documentation for Nim Macros.
- [pipe](https://github.com/5paceToast/pipe) - Pipe operator for Nim, as seen in functional languages.
- [unpack](https://github.com/technicallyagd/unpack) - Sequence/object unpacking/destructuring.
- [with](https://github.com/zevv/with) - The with macro for Nim.
- [zero-functional](https://github.com/zero-functional/zero-functional) - A library providing (almost) zero-cost chaining for functional abstractions in Nim.


## Package Repositories

- [Nim packages](https://github.com/nim-lang/packages) - List of packages for Nimble.
- [Nim package directory](https://nimble.directory/) - This service allows you to explore Nim packages known to Nimble.
  It tests package installation and generates documentation using "nim doc".


## Protocols
- [nimlsp](https://github.com/PMunch/nimlsp) - The Language Server Protocol implementation for Nim.
- [nim-ndns](https://github.com/rockcavera/nim-ndns) - A pure Nim Domain Name System (DNS) client.
- [nim-dnsprotocol](https://github.com/rockcavera/nim-dnsprotocol) - Domain Name System (DNS) protocol for Nim programming language.
- [telebot.nim](https://github.com/ba0f3/telebot.nim) - Async client for Telegram Bot API in pure Nim.
- [dimscord](https://github.com/krisppurg/dimscord) - A Discord Bot & REST Library for Nim.


## REPL

- [INim](https://github.com/AndreiRegiani/INim) - Interactive Nim Shell.
- [jupyternim](https://github.com/stisa/jupyternim) - A Jupyter kernel for Nim.


## Scripting

- [Nimcr](https://github.com/PMunch/nimcr/blob/master/README.md) - Running Nim code with Shebangs.
- [nimr](https://github.com/Jeff-Ciesielski/nimr) - Run Nim programs like scripts.


## Services

- [Luntic](https://github.com/xxlabaza/luntic) - Lightweight REST in-memory discovery service.


## IO

- [ioselectors](https://github.com/xflywind/ioselectors) - The ioselectors plus for Nim.
- [wepoll](https://github.com/xflywind/wepoll) - Windows epoll wrapper for Nim.
- [nim-faststreams](https://github.com/status-im/nim-faststreams) - Nearly zero-overhead input/output streams for Nim.
- [lockfreequeues](https://github.com/elijahr/lockfreequeues) - Lock-free queue implementations for Nim.


## Compression

- [zippy](https://github.com/guzba/zippy) - Pure Nim implementation of deflate, zlib, gzip and zip.
- [supersnappy](https://github.com/guzba/supersnappy) - Dependency-free and performant Nim Snappy implementation.
- [snappy](https://github.com/jangko/snappy) - Nim implementation of Snappy compression algorithm.
- [zip](https://github.com/nim-lang/zip) - Wrapper for the zip library.


## Tests

- [balls](https://github.com/disruptek/balls) - A unittest macro to save the world, or at least your Sunday.


## Text Processing

- [regex](https://github.com/nitely/nim-regex) - Pure Nim regex engine with linear time match.
- [npeg](https://github.com/zevv/npeg) - PEGs for Nim, another take.
- [patty](https://github.com/andreaferretti/patty) - A pattern matching library for Nim.
- [gara](https://github.com/alehander42/gara) - Macro-based pattern matching library.
- [glob](https://github.com/citycide/glob) - Pure library for matching file paths against Unix style glob patterns.
- [nim-datauri](https://github.com/juancarlospaco/nim-datauri#nim-datauri) - Data URI Base64 UTF-8.


### Translation

- [nim-tinyslation](https://github.com/juancarlospaco/nim-tinyslation#nim-tinyslation) - Text string translation from free online crowdsourced API.



### Template Engines

- [smalte](https://github.com/roquie/smalte) - It is a dead simple and lightweight template engine. Specially designed for configure application before start in Docker.
- [nim-html-dsl](https://github.com/juancarlospaco/nim-html-dsl) - Nim HTML DSL.
- [nim-templates](https://github.com/onionhammer/nim-templates) - A simple string templating library for Nim.
- [nimja](https://github.com/enthus1ast/nimja) - Typed and compiled template engine inspired by jinja2, twig and onionhammer/nim-templates for Nim.


## Web

### UDP

- [netty](https://github.com/treeform/netty) - Reliable UDP connection library for games in Nim.


### RPC

- [nim-json-rpc](https://github.com/status-im/nim-json-rpc) - Nim library for implementing JSON-RPC clients and servers.


### MQTT

- [nmqtt](https://github.com/zevv/nmqtt) - Native Nim MQTT client library.


### HTTP server
- [httpx](https://github.com/xflywind/httpx) - Cross platform web server for Nim.
- [httpbeast](https://github.com/dom96/httpbeast) - A highly performant, multi-threaded HTTP 1.1 server written in Nim.
- [GuildenStern](https://github.com/olliNiinivaara/GuildenStern) - Genuinely multithreading integrated HTTP/1.1 + WebSocket v13 Server for POSIX-compliant OSes.
- [netkit](https://github.com/iocrate/netkit) - Out-of-the-box, stable and secure network facilities and utilities written by pure Nim.


### Websocket

- [websocket.nim](https://github.com/niv/websocket.nim) - Websockets for Nim.
- [ws](https://github.com/treeform/ws) - Simple WebSocket library for Nim.
- [news](https://github.com/Tormund/news) - Nim easy web socket.


### Web Frameworks

- [Jester](https://github.com/dom96/jester) - The sinatra-like web framework for Nim. Jester provides a DSL for quickly creating web applications in Nim.
- [prologue](https://github.com/planety/prologue) - Full-Stack Web Framework written in Nim.
- [rosencrantz](http://andreaferretti.github.io/rosencrantz/) - DSL to write web servers, inspired by [Spray](http://spray.io/) and its successor [Akka HTTP](http://akka.io).
- [whip](https://github.com/mattaylor/whip) - Simple fast http server for Nim based on httpbeast and nest for high performance routing.
- [basolato](https://github.com/itsumura-h/nim-basolato) - A fullstack web framework for Nim based on Jester.
- [Karax](https://github.com/karaxnim/karax) - Framework for developing single page applications in Nim.
- [scorper](https://github.com/bung87/scorper) - A micro and elegant web framework written in Nim.
- [nim_websitecreator](https://github.com/ThomasTJdev/nim_websitecreator) - Nim fullstack website framework - deploy a website within minutes.


### Parsing HTML

- [Nimquery](https://github.com/GULPF/nimquery) - Library for querying HTML using CSS selectors, like JavaScript's `document.querySelector`.


### Auth

- [nim-httpauth](https://github.com/FedericoCeratto/nim-httpauth) - HTTP Authentication library for Nim.
- [oauth](https://github.com/CORDEA/oauth) - OAuth library for Nim.


## Markdown

- [HastyScribe](https://github.com/h3rald/hastyscribe) - Self-contained markdown compiler generating self-contained HTML documents.
- [nim-markdown](https://github.com/soasme/nim-markdown) - A Beautiful Markdown Parser in the Nim World.
- [lester](https://github.com/madprops/lester) - Create quick documents out of Markdown, into HTML.


## Development Tools

### Binding Generators

- [Nimpy](https://github.com/yglukhov/nimpy) - Gen Python wrappers, call python from Nim.
- [nimterop](https://github.com/nimterop/nimterop) - Nimterop is a Nim package that aims to make C/C++ interop seamless.
- [c2nim](https://github.com/nim-lang/c2nim) - c2nim is a tool to translate Ansi C code to Nim.
- [jnim](https://github.com/yglukhov/jnim) - Nim - Java bridge.


### Command-Line Interface Automation

- [cligen](https://github.com/c-blake/cligen) - Infer & generate command-line interace/option/argument parsers.
- [docopt.nim](https://github.com/docopt/docopt.nim) - Command-line args parser.
- [nim-argparse](https://github.com/iffy/nim-argparse) - Argument parsing for Nim.
- [clapfn](https://github.com/oliversandli/clapfn) - Argument parsing similar to Python's argparse.


## Resources

### Books

- [Nim in Action](https://www.manning.com/books/nim-in-action) - Nim's first book.
- [Nim Days](https://github.com/xmonader/nimdays) - A project to document my journey with Nim with mini applications, libraries documented from A to Z and also to provide new Nim users with some extra in depth information.
- [Nimbus Handbook](https://nimbus.guide) - A comprehensive introduction to the Nim programming language.
- [nim-style-guide](https://github.com/status-im/nim-style-guide) - Status style guid for the Nim language.


### Blogs

- [Nim Blog](http://nim-lang.org/blog.html) - Official Nim blog.
- [Goran Krampe](http://goran.krampe.se/nim/) - Wrapping C, arduino, performance, links.
- [HookRace](https://hookrace.net/blog/nim/) - Blog with multiple articles on Nim.
- [Rants from the Ballmer Peak](https://gradha.github.io/tags/nim.html) - Posts on Nim and other languages.
- [Yuriy Glukhov's blog](https://yglukhov.github.io/) - Making and shipping a game in Nim.
- [Araq's Musings](https://nim-lang.org/araq) - Blog on Nim from the creator himself.
- [Nim memory](http://zevv.nl/nim-memory/) - This is a small tutorial explaining how Nim stores data in memory.
- [Nim Arc](http://zevv.nl/nim-memory/nim-arc.html) - Make a friendly explanation of ARC and its implications for the programmer.


### Community

- [The Nim forum](http://forum.nim-lang.org/)
- [The Nim IRC channel](http://webchat.freenode.net/?channels=nim)
- [The Nim Gitter channel](https://gitter.im/nim-lang/Nim)
- [The Nim Discord channel](https://discord.gg/ptW3Rb3)
- [The Nim mailing list](http://www.freelists.org/list/nim-dev)
- [The Nim SubReddit](http://reddit.com/r/nim)
- [The Nim Telegram](https://t.me/nim_lang)
- [The Nim Telegram in Spanish](https://t.me/NimArgentina)

### Websites

- [Nim Basics](https://narimiran.github.io/nim-basics/) - Tutorial for beginners and people just starting with Nim.
- [How I start](https://howistart.org/posts/nim) - Great guide going from 0 to a bf interpreter and then a bf to Nim compiler.
- [Learn Nim in Y minutes](https://learnxinyminutes.com/docs/nim/) - Whirlwind tour.
- [Nim by Example](https://nim-by-example.github.io) - Series of pages and examples for learning the Nim programming language.
- [Nim for Python programmers](https://github.com/nim-lang/Nim/wiki/Nim-for-Python-Programmers) - Guide to Nim for people with experience in Python.
- [Rosettacode:Nim](https://rosettacode.org/wiki/Category:Nim) - 100s of solutions for various tasks using Nim (Implementations available in other languages as well).
- [dev](https://dev.to/t/nim) - Nim blogs in `dev.io`.


### Videos

- [Nim official Channel](https://www.youtube.com/channel/UCDAYn_VFt0VisL5-1a5Dk7Q/videos) - Official videos introduce the powerful and interesting part in Nim language.
- [Nim for beginners](https://www.youtube.com/user/kiloneie/playlists) - This is a video series meant to teach people programming in Nim to people who have never programmed before, or are new to Nim.
- [Make a website with Nim](https://www.youtube.com/watch?v=ndzlVRWqT2E&list=PL6RpFCvmb5SGw7aJK1E4goBxpMK3NvkON) - This is a video series meant to teach people make a website with Nim
using `jester`.
- [Learning Nim](https://www.youtube.com/watch?v=I_Y94G37iR4&list=PLu-ydI-PCl0PqxiYXQMmLh7wjQKm5Cz-H) - Tutorial video series on learning Nim showcasing various features of the language and its libraries.
- [araq twitch](https://www.twitch.tv/araq4k) - The live broadcast regarding Nim language.
- [alehander42 twitch](https://www.twitch.tv/alehander42) - The live broadcast regarding Nim language.
- [clyybber twitch](https://www.twitch.tv/clyybber) - The live broadcast regarding Nim language.
- [d0m96 twitch](https://www.twitch.tv/d0m96) - The live broadcast regarding Nim language.
- [disruptek twitch](https://www.twitch.tv/disruptek) - The live broadcast regarding Nim language.
- [yardanico twitch](https://www.twitch.tv/yardanico) - The live broadcast regarding Nim language.
- [zachary_carter twitch](https://www.twitch.tv/zachary_carter) - The live broadcast regarding Nim language.

## License
Awesome-Nim logo is based on the "Nim Crown" logo by Joseph Wecker, used with permission from the Nim project.
