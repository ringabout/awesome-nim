<h1> <a href="https://nim-lang.org"><img src="asset/awesome-nim-logo.svg" alt="Awesome-nim-logo" width="600"/></a><a href="https://awesome.re"><img align="right" src="https://awesome.re/badge.svg"></a> </h1>

> A curated list of awesome Nim frameworks, libraries, software and resources.

[Nim](https://nim-lang.org/) is a statically typed compiled systems programming language. Good for everything from shell scripting to web front & backend, to ML, HPC, and embedded.

<h2> Contents </h2>

- [Language Features](#language-features)
  - [Implementations](#implementations)
  - [Standard Libraries](#standard-libraries)
  - [Package Repositories](#package-repositories)
  - [Editors](#editors)
  - [Async IO](#async-io)
  - [Threading](#threading)
  - [Macros](#macros)
- [Operating System](#operating-system)
  - [System API](#system-api)
  - [IO](#io)
  - [Date and Time](#date-and-time)
  - [Randomization](#randomization)
  - [Scripting](#scripting)
- [Hardware](#hardware)
  - [Embedded](#embedded)
- [Data](#data)
  - [Database](#database)
    - [Driver](#driver)
    - [ORM](#orm)
  - [Data Processing](#data-processing)
  - [Parsing](#parsing)
  - [Serialization](#serialization)
- [Text](#text)
  - [Pattern Matching](#pattern-matching)
  - [Translation](#translation)
  - [Markdown](#markdown)
- [Multimedia](#multimedia)
  - [Audio](#audio)
  - [Image](#image)
- [Algorithms](#algorithms)
  - [Math](#math)
    - [Symbolic](#symbolic)
    - [FFT](#fft)
    - [Vector](#vector)
    - [Matrix](#matrix)
  - [Deep Learning](#deep-learning)
  - [Cryptography](#cryptography)
  - [Compression](#compression)
- [User Interface](#user-interface)
  - [Terminal](#terminal)
  - [Design](#design)
  - [GUI](#gui)
  - [Plotting](#plotting)
- [Web](#web)
  - [Protocols](#protocols)
    - [DNS](#dns)
    - [Websockets](#websockets)
  - [HTML Parsers](#html-parsers)
  - [HTTP Servers](#http-servers)
  - [Frameworks](#frameworks)
  - [Template Engines](#template-engines)
  - [Authentication](#authentication)
- [Game Development](#game-development)
- [Development Tools](#development-tools)
  - [Editor Integration](#editor-integration)
  - [REPL](#repl)
  - [Binding Generators](#binding-generators)
  - [Build Systems / Package Management](#build-systems--package-management)
  - [Logging](#logging)
  - [Testing](#testing)
  - [Benchmarking](#benchmarking)
  - [Command-Line Interface Automation](#command-line-interface-automation)
- [Resources](#resources)
  - [Books](#books)
  - [Blogs](#blogs)
  - [Community](#community)
  - [Tutorials](#tutorials)
  - [Videos](#videos)


## Language Features


### Implementations

- [Nim](https://github.com/nim-lang/Nim) - Nim (formerly known as "Nimrod") is a compiled, garbage-collected systems programming language which has an excellent productivity/performance ratio. Nim's design focuses on efficiency, expressiveness, elegance (in the order of priority).
- [nlvm](https://github.com/arnetheduck/nlvm) - LLVM backend for Nim.


### Standard Libraries

Nim provides unique features for seamless and transparent interoperability with other technologies. Some users found it useful to make other standard libraries usable from Nim.

- [cpython](https://github.com/juancarlospaco/cpython) - Python standard library for Nim.
- [Node.js](https://github.com/juancarlospaco/nodejs) - Node.js standard library for Nim.


### Package Repositories

- [Nim packages](https://github.com/nim-lang/packages) - List of packages for Nimble.
- [Nim package directory](https://nimble.directory/) - Explore Nim packages known to Nimble.


### Editors

- [Nim Playground](https://play.nim-lang.org/) - Code and run Nim online.
- [DoongJohn's Nim playground](https://doongjohn.github.io/nim-playground/) - An alternative implementation of the Nim playground.


### Async IO

- [nim-chronos](https://github.com/status-im/nim-chronos) - An efficient library for asynchronous programming.
- [cps](https://github.com/disruptek/cps) - Continuation-Passing Style for Nim.


### Threading

- [weave](https://github.com/mratsim/weave) - A state-of-the-art multithreading runtime: message-passing based, fast, scalable, ultra-low overhead.


### Macros

- [cascade](https://github.com/citycide/cascade) - Method & assignment cascades for Nim, inspired by Smalltalk & Dart.
- [macroutils](https://github.com/PMunch/macroutils) - A package that makes creating macros easier.
- [nimacros](https://github.com/FemtoEmacs/nimacros) - Documentation for Nim macros.
- [pipe](https://github.com/5paceToast/pipe) - Pipe operator for Nim, as seen in functional languages.
- [unpack](https://github.com/technicallyagd/unpack) - Sequence/object unpacking/destructuring.
- [with](https://github.com/zevv/with) - The `with` macro for Nim.
- [zero-functional](https://github.com/zero-functional/zero-functional) - A library providing (almost) zero-cost chaining for functional abstractions in Nim.


## Operating System

### System API

- [winim](https://github.com/khchen/winim) - Nim's Windows API and COM Library.


### IO

- [ioselectors](https://github.com/xflywind/ioselectors) - The ioselectors plus for Nim.
- [wepoll](https://github.com/xflywind/wepoll) - Windows epoll wrapper for Nim.
- [nim-faststreams](https://github.com/status-im/nim-faststreams) - Nearly zero-overhead input/output streams for Nim.
- [lockfreequeues](https://github.com/elijahr/lockfreequeues) - Lock-free queue implementations for Nim.


### Date and Time

- [nim-datetime2human](https://github.com/juancarlospaco/nim-datetime2human) - Calculate date & time with precision from seconds to millenniums. Human friendly date time as string. ISO-8601.
- [timezones](https://github.com/GULPF/timezones) - Nim timezone library compatible with the standard library.


### Randomization

- [nim-random](https://github.com/oprypin/nim-random) - Random number generation library for Nim.
- [sysrandom.nim](https://github.com/euantorano/sysrandom.nim) - A Nim library to generate random numbers and random ranges of bytes using the system's PRNG.


### Scripting

- [nimcr](https://github.com/PMunch/nimcr) - Running Nim code with Shebangs.
- [nimr](https://github.com/Jeff-Ciesielski/nimr) - Run Nim programs like scripts.


## Hardware

- [nimvisa](https://github.com/leeooox/nimvisa) - Wrapper for NI-VISA instrument control library.
- [ftd2xx](https://github.com/leeooox/ftd2xx) - Wrapper for FTDI ftd2xx library (USB to JTAG/SPI/I2C/Bitbang etc.).


### Embedded

- [ardunimo](https://github.com/gokr/ardunimo) - Nim wrapper for Arduino + LinkIt ONE SDK by Mediatek.
- [ardunimesp](https://gitlab.com/NetaLabTek/Arduimesp) - Nim wrapper for Arduino ESP8266 framework + A tool for flashing, compiling and making a Nim project into an Arduino project.
- [msp430f5510](https://gitlab.com/jalexander8717/msp430f5510-nim) - Run Nim on MSP430f5510 micro-controller (6KB of RAM).
- [Nesper](https://github.com/elcritch/nesper) - Program the ESP32 using Nim. Library on top of esp-idf.
- [stm32f3](https://github.com/mwbrown/nim_stm32f3) - Run Nim on STM32F3 micro-controller (16KB of RAM).


## Data

### Database

#### Driver

- [nimongo](https://github.com/SSPkrolik/nimongo) - Pure Nim lang MongoDB driver.
- [asyncpg](https://github.com/cheatfate/asyncpg) - Asynchronous PostgreSQL driver for Nim.
- [anonimongo](https://github.com/mashingan/anonimongo) - Another Nim pure Mongo DB driver.
- [redis](https://github.com/nim-lang/redis) - Official redis wrapper for Nim.
- [amysql](https://github.com/bung87/amysql) - Async MySQL Connector write in pure Nim.
- [mycouch](https://github.com/hamidb80/mycouch) - Multisync CouchDB driver for Nim.


#### ORM

- [ormin](https://github.com/Araq/ormin) - Prepared SQL statement generator , A lightweight ORM.
- [nim-allographer](https://github.com/itsumura-h/nim-allographer) - A query_builder/ORM library inspired by Laravel/PHP and Orator/Python for Nim.
- [nim-gatabase](https://github.com/juancarlospaco/nim-gatabase) - Connection-Pooling Compile-Time ORM for Nim.
- [norm](https://github.com/moigagoo/norm) - Norm is an object-oriented, framework-agnostic ORM for Nim that supports SQLite and PostgreSQL.


### Data Processing

- [NimData](https://github.com/bluenote10/NimData) - DataFrame API written in Nim, enabling fast out-of-core data processing.


### Parsing

- [parsetoml](https://github.com/NimParsers/parsetoml) - A Nim library to parse TOML files.
- [NimYAML](https://github.com/flyx/NimYAML) - YAML implementation for Nim.


### Serialization

- [nim-toml-serialization](https://github.com/status-im/nim-toml-serialization) - Flexible TOML serialization `not` relying on run-time type information.
- [nim-serialization](https://github.com/status-im/nim-serialization) - A modern and extensible serialization framework for Nim.
- [frosty](https://github.com/disruptek/frosty) - Marshal native Nim objects via streams, sockets.
- [nim-protobuf-serialization](https://github.com/status-im/nim-protobuf-serialization) - The nim-protobuf-serialization.
- [protobuf-nim](https://github.com/PMunch/protobuf-nim) - Protobuf implementation in pure Nim that leverages the power of the macro system to not depend on any external tools.


## Text

- [nim-datauri](https://github.com/juancarlospaco/nim-datauri) - Data URI Base64 UTF-8.

### Pattern Matching

- [regex](https://github.com/nitely/nim-regex) - Pure Nim regex engine with linear time match.
- [npeg](https://github.com/zevv/npeg) - PEGs for Nim, another take.
- [patty](https://github.com/andreaferretti/patty) - A pattern matching library for Nim.
- [gara](https://github.com/alehander42/gara) - Macro-based pattern matching library.
- [glob](https://github.com/citycide/glob) - Pure library for matching file paths against Unix style glob patterns.


### Translation

- [nim-tinyslation](https://github.com/juancarlospaco/nim-tinyslation) - Text string translation from free online crowdsourced API.


### Markdown

- [HastyScribe](https://github.com/h3rald/hastyscribe) - Self-contained markdown compiler generating self-contained HTML documents.
- [nim-markdown](https://github.com/soasme/nim-markdown) - A beautiful Markdown Parser in the Nim world.
- [lester](https://github.com/madprops/lester) - Create quick documents out of Markdown, into HTML.


## Multimedia

### Audio

- [paramidi](https://github.com/paranim/paramidi) - A Nim library for making MIDI music.
- [omni](https://github.com/vitreo12/omni) - A DSL for low-level audio programming.


### Image

- [nimpng](https://github.com/jangko/nimPNG) - PNG (Portable Network Graphics) decoder and encoder written in Nim.
- [nimpdf](https://github.com/jangko/nimpdf) - PDF document writer, written in Nim.
- [nimsvg](https://github.com/bluenote10/NimSvg) - The Nim-based DSL allowing to generate SVG files and GIF animations.
- [inumon](https://github.com/dizzyliam/inumon) - A high-level image I/O and manipulation library for Nim.
- [imageman](https://github.com/SolitudeSF/imageman) - Image manipulation library.
- [pixie](https://github.com/treeform/pixie) - A full-featured 2D graphics library for Nim.


## Algorithms

### Math

#### Symbolic

- [symbolicnim](https://github.com/HugoGranstrom/symbolicnim) - A symbolic library written purely in Nim.


#### FFT

- [impulse](https://github.com/SciNim/impulse) - Impulse will be a collection of primitives for signal processing (FFT, Convolutions).


#### Vector

- [vectorize](https://github.com/SciNim/vectorize) - SIMD vectorization backend.
- [vmath](https://github.com/treeform/vmath) - Math vector library for graphical things.


#### Matrix

- [neo](https://github.com/unicredit/neo) - A matrix library.


### Deep Learning

- [Arraymancer](https://github.com/mratsim/Arraymancer) - A fast, ergonomic and portable tensor library in Nim with a deep learning focus for CPU, GPU, OpenCL and embedded devices.
- [NimTorch](https://github.com/sinkingsugar/nimtorch) - PyTorch - Python + Nim. A Nim front-end to PyTorch's native backend, combining Nim's speed, productivity and portability with PyTorch's latest implementations.


### Cryptography

- [nimcrypto](https://github.com/cheatfate/nimcrypto) - Nim cryptographic library.
- [nimAES](https://github.com/jangko/nimAES) - Advanced Encryption Standard, Rinjdael Algorithm written in Nim.
- [nim-crc32](https://github.com/juancarlospaco/nim-crc32#nim-crc32) - CRC32 for Nim, 2 proc, just pass the thing you want to do CRC.


### Compression

- [zippy](https://github.com/guzba/zippy) - Pure Nim implementation of deflate, zlib, gzip and zip.
- [supersnappy](https://github.com/guzba/supersnappy) - Dependency-free and performant Nim Snappy implementation.
- [snappy](https://github.com/jangko/snappy) - Nim implementation of Snappy compression algorithm.
- [zip](https://github.com/nim-lang/zip) - Wrapper for the zip library.


## User Interface

### Terminal

- [illwill](https://github.com/johnnovak/illwill) - Simple cross-platform terminal library inspired by (n)curses.
- [NimCx](https://github.com/qqtop/NimCx) - Color and utilities for the Linux terminal.
- [nicy](https://github.com/icyphox/nicy) - A nice and icy zsh and bash prompt in Nim.


### Design

- [nim-random-font-color](https://github.com/juancarlospaco/nim-random-font-color) - Random curated fonts, pastel colors and seamless CSS3 Patterns for your UI/UX design. Design for non-designers - poor man's design.
- [chroma](https://github.com/treeform/chroma) - Everything you want to do with colors, in Nim.
- [typography](https://github.com/treeform/typography) - Fonts, typesetting and rasterization.
- [trick](https://github.com/exelotl/trick) - Library for GBA/NDS image conversion, and more!


### GUI

- [nimAntTweakBar](https://github.com/krux02/nimAntTweakBar) - Wrapper for AntTweakBar.
- [nimx](https://github.com/yglukhov/nimx) - Desktop, Mobile & Web GUI framework in Nim.
- [NiGui](https://github.com/trustable-code/NiGui) - A cross-platform, desktop GUI toolkit.
- [Neel](https://github.com/Niminem/Neel) - A library for making Electron-like HTML/JS GUI apps.
- [wNim](https://github.com/khchen/wNim) - Nim's Windows GUI Framework.
- [nimqml](https://github.com/filcuc/nimqml) - Qt QML bindings for the Nim programming language.
- [webgui](https://github.com/juancarlospaco/webgui) - Web Technologies based cross-platform GUI Framework with a dark theme.
- [gintro](https://github.com/StefanSalewski/gintro) - High-level GObject-Introspection based GTK3/GTK4 bindings for Nim.
- [nsciter](https://github.com/Yardanico/nsciter) - High-level and low-level Nim wrapper for https://sciter.com.
- [iup](https://github.com/nim-lang/iup) - Wrapper for IUP. Beginnings of what might become Nim's official UI library.
- [fidget](https://github.com/treeform/fidget) - Figma based UI library for Nim, with HTML and OpenGL backends.


### Plotting

- [ggplotnim](https://github.com/Vindaar/ggplotnim) - A port of ggplot2 for Nim.
- [nim-plotly](https://github.com/SciNim/nim-plotly) - The plotting library for Nim.
- [graph](https://github.com/stisa/graph) - A basic plotting library in Nim.
- [npainter](https://github.com/mrgaturus/npainter) - Semi GPU-accelerated painting software written in Nim.


## Web

### Protocols

- [netty](https://github.com/treeform/netty) - Reliable UDP connection library for games in Nim.
- [nim-json-rpc](https://github.com/status-im/nim-json-rpc) - Nim library for implementing JSON-RPC clients and servers.
- [nmqtt](https://github.com/zevv/nmqtt) - Native Nim MQTT client library.
- [telebot.nim](https://github.com/ba0f3/telebot.nim) - Async client for Telegram Bot API in pure Nim.
- [dimscord](https://github.com/krisppurg/dimscord) - A Discord Bot & REST Library for Nim.


#### DNS

- [nim-ndns](https://github.com/rockcavera/nim-ndns) - A pure Nim Domain Name System (DNS) client.
- [nim-dnsprotocol](https://github.com/rockcavera/nim-dnsprotocol) - Domain Name System (DNS) protocol for Nim programming language.


#### Websockets

- [websocket.nim](https://github.com/niv/websocket.nim) - Websockets for Nim.
- [ws](https://github.com/treeform/ws) - Simple WebSocket library for Nim.
- [news](https://github.com/Tormund/news) - Nim easy web socket. Based on ws.
- [jswebsockets](https://juancarlospaco.github.io/nodejs/nodejs/jswebsockets) - WebSockets optimized for JavaScript targets.


### HTML Parsers

- [Nimquery](https://github.com/GULPF/nimquery) - Library for querying HTML using CSS selectors, like JavaScript's `document.querySelector`.


### HTTP Servers

- [httpx](https://github.com/xflywind/httpx) - Cross platform web server for Nim.
- [httpbeast](https://github.com/dom96/httpbeast) - A highly performant, multi-threaded HTTP 1.1 server written in Nim.
- [GuildenStern](https://github.com/olliNiinivaara/GuildenStern) - Genuinely multithreading integrated HTTP/1.1 + WebSocket v13 Server for POSIX-compliant OSes.
- [netkit](https://github.com/iocrate/netkit) - Out-of-the-box, stable and secure network facilities and utilities written in pure Nim.
- [jshttp2](https://juancarlospaco.github.io/nodejs/nodejs/jshttp2) - Async HTTPS 2.0 web server.


### Frameworks

- [Jester](https://github.com/dom96/jester) - The sinatra-like web framework for Nim. Jester provides a DSL for quickly creating web applications in Nim.
- [prologue](https://github.com/planety/prologue) - Full-Stack web framework written in Nim.
- [rosencrantz](http://andreaferretti.github.io/rosencrantz/) - DSL to write web servers, inspired by [Spray](http://spray.io/) and its successor [Akka HTTP](http://akka.io).
- [whip](https://github.com/mattaylor/whip) - Simple and fast HTTP server for Nim based on httpbeast and nest for high performance routing.
- [basolato](https://github.com/itsumura-h/nim-basolato) - A fullstack web framework for Nim based on Jester.
- [Karax](https://github.com/karaxnim/karax) - A framework for developing single page applications in Nim.
- [scorper](https://github.com/bung87/scorper) - A micro and elegant web framework written in Nim.
- [nim_websitecreator](https://github.com/ThomasTJdev/nim_websitecreator) - Nim fullstack website framework - deploy a website within minutes.


### Template Engines

- [smalte](https://github.com/roquie/smalte) - It is a dead simple and lightweight template engine. Specially designed for configure application before start in Docker.
- [nim-html-dsl](https://github.com/juancarlospaco/nim-html-dsl) - Nim HTML DSL.
- [nim-templates](https://github.com/onionhammer/nim-templates) - A simple string templating library for Nim.
- [nimja](https://github.com/enthus1ast/nimja) - Typed and compiled template engine inspired by jinja2, twig and onionhammer/nim-templates for Nim.


### Authentication

- [nim-httpauth](https://github.com/FedericoCeratto/nim-httpauth) - HTTP Authentication library for Nim.
- [oauth](https://github.com/CORDEA/oauth) - OAuth library for Nim.


## Game Development

- [frag](https://github.com/zacharycarter/frag) - 3D Game Engine.
- [nico](https://github.com/ftsf/nico) - Nim Game Framework based on Pico-8.
- [nimgame2](https://github.com/Vladar4/nimgame2) - A simple 2D game engine for Nim.
- [norx](https://github.com/tankfeud/norx) - A complete wrapper of the ORX 2.5D cross platform game engine library.
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


## Development Tools

### Editor Integration

- [Editor Support](https://github.com/nim-lang/Nim/wiki/editor-support) - Official list of editor plugins for Nim.
- [nimlsp](https://github.com/PMunch/nimlsp) - The Language Server Protocol implementation for Nim.
- [nim.nvim](https://github.com/alaviss/nim.nvim) - Nim plugin for NeoVim.
- [vscode-nim](https://github.com/saem/vscode-nim) - Language support for the Nim programming language for VS Code.


### REPL

- [INim](https://github.com/AndreiRegiani/INim) - Interactive Nim Shell.
- [jupyternim](https://github.com/stisa/jupyternim) - A Jupyter kernel for Nim.


### Binding Generators

- [c2nim](https://github.com/nim-lang/c2nim) - c2nim is a tool to translate Ansi C code to Nim.
- [nimterop](https://github.com/nimterop/nimterop) - A Nim package that aims to make C/C++ interop seamless.
- [Futhark](https://github.com/PMunch/futhark) - Automatic wrapping of C headers in Nim with libclang.
- [nimpy](https://github.com/yglukhov/nimpy) - Generate Python wrappers and call Python from Nim.
- [jnim](https://github.com/yglukhov/jnim) - Nim - Java bridge.


### Build Systems / Package Management

- [ChooseNim](https://github.com/dom96/choosenim) - Installing and switching between Nim versions (à la rustup, pyenv).
- [Nake](https://github.com/fowlmouth/nake) - Describe your Nim builds as tasks.
- [Nawabs](https://github.com/Araq/nawabs) - A build system that throws away version numbering in favor of git hashes.
- [Nimble](https://github.com/nim-lang/nimble) - Nimble can be used as a build system.
- [nimph](https://github.com/disruptek/nimph) - Nim package hierarchy manager from the future.
- [nimby](https://github.com/treeform/nimby) - A very simple and unofficial package manager for Nim.
- [nsis](https://github.com/nim-libs/nsis) - Nim programming language setup tool.


### Logging

- [nim-chronicles](https://github.com/status-im/nim-chronicles) - A crafty implementation of structured logging for Nim.
- [nim-morelogging](https://github.com/FedericoCeratto/nim-morelogging) - Logging library for Nim.


### Testing

- [balls](https://github.com/disruptek/balls) - A unittest macro to save the world, or at least your Sunday.


### Benchmarking

- [golden](https://github.com/disruptek/golden) - A benchmark for compile-time and/or runtime Nim.
- [timeit](https://github.com/xflywind/timeit) - Measuring execution times written by Nim.
- [criterion](https://github.com/disruptek/criterion) - Statistic-driven micro-benchmark framework.


### Command-Line Interface Automation

- [cligen](https://github.com/c-blake/cligen) - Infer & generate command-line interace/option/argument parsers.
- [docopt.nim](https://github.com/docopt/docopt.nim) - Command-line args parser.
- [nim-argparse](https://github.com/iffy/nim-argparse) - Argument parsing for Nim.
- [clapfn](https://github.com/oliversandli/clapfn) - Argument parsing similar to Python's argparse.
- [cliche](https://github.com/juancarlospaco/cliche) - AutoMagic CLI argument parsing is so cliché.


## Resources

### Books

- [Nim in Action](https://www.manning.com/books/nim-in-action) - Nim's first book.
- [Computer Programming with Nim](https://ssalewski.de/nimprogramming.html) - A gentle introduction to the Nim programming language.
- [Nim Basics](https://narimiran.github.io/nim-basics/) - Tutorial for beginners and people just starting with Nim.
- [Nim Style Guide](https://status-im.github.io/nim-style-guide/) - Status style guide for the Nim language.


### Blogs

- [Nim Blog](http://nim-lang.org/blog.html) - Official Nim blog.
- [Goran Krampe](http://goran.krampe.se/nim/) - Wrapping C, Arduino, performance, links.
- [HookRace](https://hookrace.net/blog/nim/) - Blog with multiple articles on Nim.
- [Rants from the Ballmer Peak](https://gradha.github.io/tags/nim.html) - Posts on Nim and other languages.
- [Yuriy Glukhov's blog](https://yglukhov.github.io/) - Making and shipping a game in Nim.
- [Araq's Musings](https://nim-lang.org/araq) - Blog on Nim from the creator himself.
- [Nim on dev.to](https://dev.to/t/nim) - Nim blogs on `dev.to`.


### Community

- [The Nim forum](http://forum.nim-lang.org/)
- [The Nim IRC channel](http://webchat.freenode.net/?channels=nim)
- [The Nim Gitter channel](https://gitter.im/nim-lang/Nim)
- [The Nim Discord channel](https://discord.gg/ptW3Rb3)
- [The Nim mailing list (forum archive)](https://www.mail-archive.com/nim-general@lists.nim-lang.org/)
- [The Nim subreddit](http://reddit.com/r/nim)
- [The Nim Telegram](https://t.me/nim_lang)
- [The Nim Telegram in Spanish](https://t.me/NimArgentina)


### Tutorials

- [Nim Days](https://xmonader.github.io/nimdays/) - A project to document my journey with Nim with mini applications, libraries documented from A to Z and also to provide new Nim users with some extra in depth information.
- [How I start](https://howistart.org/posts/nim) - Great guide going from 0 to a bf interpreter and then a bf to Nim compiler.
- [Learn Nim in Y minutes](https://learnxinyminutes.com/docs/nim/) - Whirlwind tour.
- [Nim by Example](https://nim-by-example.github.io) - Series of pages and examples for learning the Nim programming language.
- [Nim for Python programmers](https://github.com/nim-lang/Nim/wiki/Nim-for-Python-Programmers) - Guide to Nim for people with experience in Python.
- [Nim on Rosetta Code](https://rosettacode.org/wiki/Category:Nim) - Thousands of solutions for various tasks using Nim.
- [Nim Memory](http://zevv.nl/nim-memory/) - A small tutorial explaining how Nim stores data in memory.
- [Nim ARC](http://zevv.nl/nim-memory/nim-arc.html) - A friendly explanation of ARC and its implications for the programmer.


### Videos

- [Nim's Official Channel](https://www.youtube.com/channel/UCDAYn_VFt0VisL5-1a5Dk7Q/videos) - Official videos introduce the powerful and interesting part in Nim language.
- [Nim for Beginners](https://www.youtube.com/user/kiloneie/playlists) - This is a video series meant to teach people programming in Nim to people who have never programmed before, or are new to Nim.
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

---
*Awesome-Nim logo is based on the "Nim Crown" logo by Joseph Wecker, used with permission from the Nim project.*
