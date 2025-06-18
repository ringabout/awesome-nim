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
  - [Error Handling](#error-handling)
  - [Contracts](#contracts)
  - [Object-Oriented Programming](#object-oriented-programming)
  - [Functional Programming](#functional-programming)
  - [Pattern Matching](#pattern-matching)
  - [Iteration](#iteration)
  - [Macros](#macros)
- [Operating System](#operating-system)
  - [System API](#system-api)
  - [IO](#io)
  - [Processes](#processes)
  - [Date and Time](#date-and-time)
  - [Randomization](#randomization)
  - [Scripting](#scripting)
- [System Tools](#system-tools)
  - [Backups](#backups)   
- [Hardware](#hardware)
  - [Embedded](#embedded)
- [Science](#science)
- [Data](#data)
  - [Database](#database)
    - [Driver](#driver)
    - [ORM](#orm)
  - [Data Structures](#data-structures)
  - [Data Processing](#data-processing)
  - [Parsing](#parsing)
  - [Serialization](#serialization)
  - [Standards](#standards)
- [Text](#text)
  - [String Types](#string-types)
  - [Translation](#translation)
  - [Markdown](#markdown)
- [Multimedia](#multimedia)
  - [Audio](#audio)
  - [Images](#images)
  - [Documents](#documents)
- [Algorithms](#algorithms)
  - [Math](#math)
    - [Symbolic](#symbolic)
    - [FFT](#fft)
    - [Vector](#vector)
    - [Matrix](#matrix)
  - [Deep Learning](#deep-learning)
  - [Bigints](#bigints)
  - [Cryptography](#cryptography)
  - [Blockchain](#blockchain)
  - [Compression](#compression)
- [User Interface](#user-interface)
  - [Terminal](#terminal)
  - [Design](#design)
  - [GUI](#gui)
    - [Crossplatform](#crossplatform)
    - [Windows](#windows)
    - [Linux](#linux)
    - [Web Technology](#web-technology)
    - [Lightweight](#lightweight)
  - [Plotting](#plotting)
- [Web](#web)
  - [Protocols](#protocols)
    - [DNS](#dns)
    - [QUIC](#quic)
    - [Websockets](#websockets)
    - [Messaging](#messaging)
    - [Multicast](#multicast)
  - [HTML Parsers](#html-parsers)
  - [HTTP Servers](#http-servers)
  - [Gemini Servers](#gemini-servers)
  - [Frameworks](#frameworks)
  - [Template Engines](#template-engines)
  - [Authentication](#authentication)
- [Game Development](#game-development)
  - [Game Libraries](#game-libraries)
  - [Game Frameworks](#game-frameworks)
  - [Game Engines](#game-engines)
  - [Rules Engines](#rules-engines)
- [Development Tools](#development-tools)
  - [Editor Integration](#editor-integration)
  - [REPL](#repl)
  - [Binding Generators](#binding-generators)
  - [Build Systems / Package Management](#build-systems--package-management)
  - [Logging](#logging)
  - [Testing](#testing)
  - [Fuzzing](#fuzzing)
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


Also, unlike those above, which requires runtime dependancy, some pure-Nim libraries are implemented.

- [pylib](https://github.com/nimpylib/pylib) - Pure Nim implementation for Python builtins, libraries and sugars.


### Package Repositories

- [Nim packages](https://github.com/nim-lang/packages) - List of packages for Nimble.
- [Nim package directory](https://nimble.directory/) - Explore Nim packages known to Nimble.


### Editors
- [moe](https://github.com/fox0430/moe) - A vim-like editor made with Nim, also supports C, Rust, Javascript, etc.
- [Nev](https://github.com/Nimaoth/Nev) - A keyboard focused GUI and terminal text editor.
- [Nim Playground](https://play.nim-lang.org/) - Code and run Nim online.
- [DoongJohn's Nim playground](https://doongjohn.github.io/nim-playground/) - An alternative implementation of the Nim playground.


### Async IO

- [std/async](https://nim-lang.org/docs/async.html) - Async/await implementation in Nim's stdlib (aka asyncdispatch).
- [chronos](https://github.com/status-im/nim-chronos) - An efficient library for asynchronous programming.
- [cps](https://github.com/disruptek/cps) - Continuation-Passing Style for Nim.


### Threading

- [malebolgia](https://github.com/Araq/malebolgia) - A powerful library in Nim that simplifies the implementation of concurrent and parallel programming.
- [weave](https://github.com/mratsim/weave) - A state-of-the-art multithreading runtime: message-passing based, fast, scalable, ultra-low overhead.
- [timerpool](https://github.com/mikra01/timerpool) - Threadsafe timerpool implementation for event purposes.
- [taskpools](https://github.com/status-im/nim-taskpools) - Lightweight, energy-efficient, easily auditable threadpools.
- [shared](https://github.com/genotrance/shared) - A Nim library for shared types.
- [synthesis](https://github.com/mratsim/Synthesis) - A compiletime, procedure-based, low-overhead, no-allocation, state-machine generator optimized for communicating processes and threads.
- [sync](https://github.com/planetis-m/sync) - Useful synchronization primitives.
- [threadlogging](https://codeberg.org/pswilde/threadlogging) - A thread safe logging library using Nim's own logging module


### Error Handling

- [result](https://github.com/arnetheduck/nim-result/) - Friendly, exception-free value-or-error returns, similar to Option[T].
- [questionable](https://github.com/status-im/questionable) - Elegant optional types for Nim.
- [optionsutils](https://github.com/PMunch/nim-optionsutils) - Utility macros for easier handling of options in Nim.


### Contracts

- [contracts](https://github.com/Udiknedormin/NimContracts) - Used to make contracts - elegant promises that pieces of code will fulfill certain conditions.
- [contra](https://github.com/juancarlospaco/nim-contra) - Lightweight and fast self-documenting design by contract programming.


### Object-Oriented Programming

- [oop_utils](https://github.com/bluenote10/oop_utils) - Nim macros for building OOP class hierarchies.
- [interfaced](https://github.com/andreaferretti/interfaced) - Interfaces for Nim.
- [traitor](https://github.com/beef331/traitor) - A macro heavy trait library made from boredom.
- [classes](https://github.com/jjv360/nim-classes) - Python-style class system for Nim.
- [classy](https://github.com/nigredo-tori/classy) - Haskell-style typeclasses for Nim.


### Functional Programming

- [cascade](https://github.com/citycide/cascade) - Method & assignment cascades for Nim, inspired by Smalltalk & Dart.
- [nimfp](https://github.com/vegansk/nimfp) - Nim functional programming library.
- [nim-pipexp](https://github.com/ShalokShalom/nim-pipexp) - Expression-based pipe operators with placeholder argument for Nim.
- [pipe](https://github.com/5paceToast/pipe) - Pipe operator for Nim, as seen in functional languages.
- [zero-functional](https://github.com/zero-functional/zero-functional) - A library providing (almost) zero-cost chaining for functional abstractions in Nim.


### Pattern Matching

- [regex](https://github.com/nitely/nim-regex) - Pure Nim regex engine with linear time match.
- [npeg](https://github.com/zevv/npeg) - PEGs for Nim, another take.
- [patty](https://github.com/andreaferretti/patty) - A pattern matching library for Nim.
- [gara](https://github.com/alehander42/gara) - Macro-based pattern matching library.
- [glob](https://github.com/citycide/glob) - Pure library for matching file paths against Unix style glob patterns.
- [ast_pattern_match](https://github.com/krux02/ast-pattern-matching) - A library to do pattern matching on the AST.
- [awk](https://github.com/greencardamom/awk) - A library of awk functions in Nim.
- [tinyre](https://github.com/khchen/tinyre) - A tiny regex engine based on Rob Pike's VM implementation.


### Iteration

- [iterrr](https://github.com/hamidb80/iterrr) - Macros-based functional-style, lazy-like, extensible iterator library.
- [itertools](https://github.com/narimiran/itertools) - Nim rewrite of a very popular Python module of the same name.
- [loopfusion](https://github.com/numforge/loopfusion) - Iterate efficiently over a variadic number of containers.
- [looper](https://github.com/b3liever/looper) - For loop macros for Nim.
- [mangle](https://github.com/baabelfish/mangle) - Attempt at a streaming library.


### Macros

- [macroutils](https://github.com/PMunch/macroutils) - A package that makes creating macros easier.
- [nimacros](https://github.com/FemtoEmacs/nimacros) - Documentation for Nim macros.
- [unpack](https://github.com/technicallyagd/unpack) - Sequence/object unpacking/destructuring.
- [with](https://github.com/zevv/with) - The `with` macro for Nim.
- [memo](https://github.com/andreaferretti/memo) - Memoization for Nim.


## Operating System

### System API

- [winim](https://github.com/khchen/winim) - Nim's Windows API and COM Library.
- [serial](https://github.com/euantorano/serial.nim) - A Nim library for accessing serial ports.
- [tempdir](https://github.com/euantorano/tempdir.nim) - A Nim library to create and manage temporary directories.
- [nimbluez](https://github.com/Electric-Blue/NimBluez) - Nim modules for access to system Bluetooth resources.


### IO

- [std/selectors](https://nim-lang.org/docs/selectors.html) - Epoll/Kqueue/Select implementation in Nim's stdlib.
- [ioselectors](https://github.com/xflywind/ioselectors) - The ioselectors plus for Nim.
- [wepoll](https://github.com/xflywind/wepoll) - Windows epoll wrapper for Nim.
- [faststreams](https://github.com/status-im/nim-faststreams) - Nearly zero-overhead input/output streams for Nim.
- [lockfreequeues](https://github.com/elijahr/lockfreequeues) - Lock-free queue implementations for Nim.


### Processes

- [psutil](https://github.com/johnscillieri/psutil-nim) - A port of Python's psutil to Nim.
- [shell](https://github.com/Vindaar/shell) - A mini Nim DSL to execute shell commands more conveniently.
- [schedules](https://github.com/soasme/nim-schedules) - A Nim scheduler library that lets you kick off jobs at regular intervals.
- [daemon](https://github.com/status-im/nim-daemon) - Cross-platform process daemonization library for the Nim language.


### Date and Time

- [datetime2human](https://github.com/juancarlospaco/nim-datetime2human) - Calculate date & time with precision from seconds to millenniums. Human friendly date time as string. ISO-8601.
- [timezones](https://github.com/GULPF/timezones) - Nim timezone library compatible with the standard library.
- [chrono](https://github.com/treeform/chrono) - A timestamps, calendars, and timezones library.


### Randomization

- [random](https://github.com/oprypin/nim-random) - Random number generation library for Nim, inspired by Python's "random" module.
- [sysrandom.nim](https://github.com/euantorano/sysrandom.nim) - A Nim library to generate random numbers and random ranges of bytes using the system's PRNG.
- [alea](https://github.com/andreaferretti/alea) - Define and compose random variables.
- [drand48](https://github.com/JeffersonLab/drand48) - Nim implementation of the standard Unix drand48 random number generator.


### Scripting

- [nimcr](https://github.com/PMunch/nimcr) - Running Nim code with Shebangs.
- [nimr](https://github.com/Jeff-Ciesielski/nimr) - Run Nim programs like scripts.


## System Tools

### Backups

- [norg](https://codeberg.org/pswilde/norgbackup) - A portable wrapper for borg and restic.

 
## Hardware

- [nimvisa](https://github.com/leeooox/nimvisa) - Wrapper for NI-VISA instrument control library.
- [ftd2xx](https://github.com/leeooox/ftd2xx) - Wrapper for FTDI ftd2xx library (USB to JTAG/SPI/I2C/Bitbang etc.).


### Embedded

- [ratel](https://github.com/PMunch/ratel) - Next-generation, zero-cost abstraction microconroller programming in Nim.
- [ardunimo](https://github.com/gokr/ardunimo) - Nim wrapper for Arduino + LinkIt ONE SDK by Mediatek.
- [ardunimesp](https://gitlab.com/NetaLabTek/Arduimesp) - Nim wrapper for Arduino ESP8266 framework + A tool for flashing, compiling and making a Nim project into an Arduino project.
- [msp430f5510](https://gitlab.com/jalexander8717/msp430f5510-nim) - Run Nim on MSP430f5510 micro-controller (6KB of RAM).
- [Nesper](https://github.com/elcritch/nesper) - Program the ESP32 using Nim. Library on top of esp-idf.
- [stm32f3](https://github.com/mwbrown/nim_stm32f3) - Run Nim on STM32F3 micro-controller (16KB of RAM).
- [boneIO](https://github.com/xyz32/boneIO) - GPIO implementation for the BeagleBone Black for Nim.


## Science

- [units](https://github.com/Udiknedormin/NimUnits) - Statically-typed quantity units library for the Nim language.
- [unchained](https://github.com/SciNim/Unchained) - A fully type safe, compile time only units library.
- [metric](https://github.com/mjendrusch/metric) - A small library providing type-level dimensional analysis.
- [orbits](https://github.com/treeform/orbits) - Orbital mechanics library for Nim.
- [qex](https://github.com/jcosborn/qex) - High-level framework for lattice field operations.

## Data

### Database

#### Driver

- [amysql](https://github.com/bung87/amysql) - Async MySQL Connector write in pure Nim.
- [anonimongo](https://github.com/mashingan/anonimongo) - Another Nim pure Mongo DB driver.
- [asyncmysql](https://github.com/tulayang/asyncmysql) - Asynchronous MySQL connector written in pure Nim.
- [asyncpg](https://github.com/cheatfate/asyncpg) - Asynchronous PostgreSQL driver for Nim.
- [kuzu](https://github.com/mahlonsmith/nim-kuzu) - Wrapper for Kuzu - an embedded graph database built for query speed and scalability.
- [limdb](https://github.com/capocasa/limdb) - Very high performance, persistent and safe key-value store based on LMDB with Nim table-like interface.
- [litestore](https://github.com/h3rald/litestore) - A lightweight, self-contained, RESTful, searchable, multi-format NoSQL document store.
- [mycouch](https://github.com/hamidb80/mycouch) - Multisync CouchDB driver for Nim.
- [nimongo](https://github.com/SSPkrolik/nimongo) - Pure Nim lang MongoDB driver.
- [redis](https://github.com/nim-lang/redis) - Official redis wrapper for Nim.
- [rocksdb](https://github.com/status-im/nim-rocksdb) - Nim wrapper for RocksDB, a persistent key-value store for flash and RAM Storage.
- [sqlcipher](https://github.com/status-im/nim-sqlcipher) - SQLCipher wrapper.
- [SQLiteral](https://github.com/olliNiinivaara/SQLiteral) - A high level SQLite API for Nim.
- [tiny_sqlite](https://github.com/GULPF/tiny_sqlite) - Very lightweight and safe SQLite library.


#### ORM

- [ormin](https://github.com/Araq/ormin) - Prepared SQL statement generator , A lightweight ORM.
- [allographer](https://github.com/itsumura-h/nim-allographer) - A query_builder/ORM library inspired by Laravel/PHP and Orator/Python for Nim.
- [gatabase](https://github.com/juancarlospaco/nim-gatabase) - Connection-Pooling Compile-Time ORM for Nim.
- [norm](https://github.com/moigagoo/norm) - Norm is an object-oriented, framework-agnostic ORM for Nim that supports SQLite and PostgreSQL.


### Data Structures

- [BitVector](https://github.com/MarcAzar/BitVector) - A high-performance Nim implementation of BitVectors.
- [rbtree](https://github.com/Nycto/RBTreeNim) - A Red/Black tree implementation in Nim.
- [quadtree](https://github.com/Nycto/QuadtreeNim) - A Quadtree library for Nim.
- [kdtree](https://github.com/jblindsay/kdtree) - A pure Nim k-d tree implementation for efficient spatial querying of point data.
- [RTree](https://github.com/StefanSalewski/RTree) - Generic R-tree implementation for Nim.
- [sorta](https://github.com/narimiran/sorta) - SortedTables in Nim, based on B-trees.
- [minmaxheap](https://github.com/StefanSalewski/minmaxheap) - A Nim implementation of a Minimum-Maximum heap.
- [BipBuffer](https://github.com/MarcAzar/BipBuffer) - A Nim implementation of Simon Cooke's Bib Buffer
- [bloom](https://github.com/boydgreenfield/nimrod-bloom) - Bloom filter implementation in Nim.
- [binaryheap](https://github.com/bluenote10/nim-heap) - Simple binary heap implementation in Nim.
- [faststack](https://github.com/Vladar4/FastStack) - Dynamically resizable data structure for fast iteration over large arrays of similar elements.
- [StashTable](https://github.com/olliNiinivaara/StashTable) - Concurrent hash tables for Nim.


### Data Processing

- [NimData](https://github.com/bluenote10/NimData) - DataFrame API written in Nim, enabling fast out-of-core data processing.
- [Datamancer](https://github.com/SciNim/Datamancer) - A dataframe library with a dplyr like API.
- [nimdataframe](https://github.com/qqtop/nimdataframe) - Dataframe for Nim.
- [nimhdf5](https://github.com/Vindaar/nimhdf5) - Wrapper and some simple high-level bindings for the HDF5 library for Nim.
- [mpfit](https://github.com/Vindaar/nim-mpfit) - A wrapper for the cMPFIT library for Nim.


### Parsing

- [Binarylang](https://github.com/sealmove/binarylang) - Extensible Nim DSL for creating binary parsers/encoders in a symmetric fashion.
- [iniplus](https://github.com/penguinite/iniplus.git) - INI parser with support for arrays and tables.
- [NimYAML](https://github.com/flyx/NimYAML) - YAML implementation for Nim.
- [parsetoml](https://github.com/NimParsers/parsetoml) - A Nim library to parse TOML files.


### Serialization

- [bingo](https://github.com/planetis-m/bingo) - Binary serialization framework for Nim.
- [flatty](https://github.com/treeform/flatty) - Tools and serializer for plain flat binary files.
- [frosty](https://github.com/disruptek/frosty) - Marshal native Nim objects via streams, sockets.
- [json-serialization](https://github.com/status-im/nim-json-serialization) - Flexible JSON serialization not relying on run-time type information.
- [nesm](https://xomachine.gitlab.io/NESM/) - NESM is a tool that generates serialization and deserialization code for a given object.
- [protobuf-nim](https://github.com/PMunch/protobuf-nim) - Protobuf implementation in pure Nim that leverages the power of the macro system to not depend on any external tools.
- [protobuf-serialization](https://github.com/status-im/nim-protobuf-serialization) - The nim-protobuf-serialization.
- [serialization](https://github.com/status-im/nim-serialization) - A modern and extensible serialization framework for Nim.
- [ssz-serialization](https://github.com/status-im/nim-ssz-serialization) - Nim implementation of Simple Serialize (SSZ) serialization and merkleization.
- [tnetstring](https://github.com/mahlonsmith/nim-tnetstring) - Parsing and serializing for the TNetstring format.
- [toml-serialization](https://github.com/status-im/nim-toml-serialization) - Flexible TOML serialization `not` relying on run-time type information.

### Standards

- [isocodes](https://github.com/kraptor/isocodes) - ISO codes for Nim (ISO 3166-1, ISO 3166-2, ISO 3166-3, ISO 15924, ISO 15924, ISO 639-2, ISO 639-5)

## Text

### String Types

- [ssostrings](https://github.com/planetis-m/ssostrings) - Small String Optimized (SSO) string implementation.
- [cowstrings](https://github.com/planetis-m/cowstrings) - Copy-On-Write string implementation according to nim-lang/RFCs#221.


### Translation

- [tinyslation](https://github.com/juancarlospaco/nim-tinyslation) - Text string translation from free online crowdsourced API.


### Markdown

- [HastyScribe](https://github.com/h3rald/hastyscribe) - Self-contained markdown compiler generating self-contained HTML documents.
- [markdown](https://github.com/soasme/nim-markdown) - A beautiful Markdown Parser in the Nim world.
- [lester](https://github.com/madprops/lester) - Create quick documents out of Markdown, into HTML.


## Multimedia

### Audio

- [paramidi](https://github.com/paranim/paramidi) - A Nim library for making MIDI music.
- [omni](https://github.com/vitreo12/omni) - A DSL for low-level audio programming.
- [wave](https://github.com/jiro4989/wave) - A tiny WAV sound module.
- [parasound](https://github.com/paranim/parasound) - A library to provide Nim bindings for miniaudio and dr_wav.
- [jacket](https://github.com/SpotlightKid/jacket) - A Nim wrapper for the libjack C library to write clients for the JACK audio server.


### Images

- [pixie](https://github.com/treeform/pixie) - A full-featured 2D graphics library for Nim.
- [nimpng](https://github.com/jangko/nimPNG) - PNG (Portable Network Graphics) decoder and encoder written in Nim.
- [nimbmp](https://github.com/jangko/nimBMP) - BMP decoder and encoder written in Nim.
- [nimsvg](https://github.com/bluenote10/NimSvg) - A Nim-based DSL allowing generation of SVG files and GIF animations.
- [pnm](https://github.com/jiro4989/pnm) - Library for PNM (Portable Anymap) in Nim.


### Documents

- [nimpdf](https://github.com/jangko/nimpdf) - PDF document writer, written in Nim.


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
- [manu](https://github.com/planetis-m/manu) - Nim MAtrix NUmeric package - a port of JAMA, adapted to Nim.
- [nlopt](https://github.com/Vindaar/nimnlopt) - A wrapper for the nonlinear optimization library Nlopt.


### Deep Learning

- [Arraymancer](https://github.com/mratsim/Arraymancer) - A fast, ergonomic and portable tensor library in Nim with a deep learning focus for CPU, GPU, OpenCL and embedded devices.
- [NimTorch](https://github.com/sinkingsugar/nimtorch) - PyTorch - Python + Nim. A Nim front-end to PyTorch's native backend, combining Nim's speed, productivity and portability with PyTorch's latest implementations.
- [laser](https://github.com/numforge/laser) - Carefully-tuned primitives for running tensor and image-processing code on CPU, GPUs and accelerators.
<!-- - [flambeau](https://github.com/SciNim/flambeau) - Nim bindings to libtorch. -->


### Bigints

- [bigints](https://github.com/nim-lang/bigints) - Bigints for Nim.
- [stint](https://github.com/status-im/nim-stint) - Stack-based arbitrary-precision integers. Fast and portable with natural syntax for resource-restricted devices.
- [theo](https://github.com/SciNim/theo) - An optimized bigint and number theory library for Nim.


### Cryptography

- [nimcrypto](https://github.com/cheatfate/nimcrypto) - Nim cryptographic library.
- [hashlib](https://github.com/khchen/hashlib) - Hash library that contains almost all the hash functions for Nim.
- [nimaes](https://github.com/jangko/nimAES) - Advanced Encryption Standard, Rinjdael Algorithm written in Nim.
- [constantine](https://github.com/mratsim/constantine) - Constant time pairing-based of elliptic curve based cryptography and digital signatures.
- [bslcurve](https://github.com/status-im/nim-blscurve) - Nim implementation of BLS signature scheme (Boneh-Lynn-Shacham) over Barreto-Lynn-Scott (BLS) curve BLS12-381.
- [bncurve](https://github.com/status-im/nim-bncurve) - Nim implementation of Barreto-Naehrig pairing-friendly elliptic curve.
- [xxhash.nim](https://github.com/OpenSystemsLab/xxhash.nim) - A wrapper for the xxhash hashing library in Nim.
- [xxtea](https://github.com/xxtea/xxtea-nim) - XXTEA encryption algorithm library.
- [crc32](https://github.com/juancarlospaco/nim-crc32) - CRC32 for Nim. Just pass the thing you want to do CRC.
- [rollinghash](https://github.com/MarcAzar/RollingHash) - High performance Nim implementation of a Cyclic Polynomial Hash, aka BuzHash, and the Rabin-Karp algorithm.
- [murmurhash](https://github.com/cwpearson/nim-murmurhash) - Pure Nim implementation of MurmerHash
- [des](https://github.com/LucaWolf/des.nim) - DES/3DES, DUKPT and MAC in Nim.
- [shimsham](https://github.com/apense/shimsham) - A collection of hash functions, including JH, SHA-2, SHA-3, SipHash, Tiger, and Whirlpool.
- [NiMPC](https://github.com/markspanbroek/nimpc) - A secure multi-party computation (MPC) library for the Nim programming language.


### Blockchain

- [eth](https://github.com/status-im/nim-eth) - Common utilities for Ethereum.
- [nimbus-eth1](https://github.com/status-im/nimbus-eth1) - An Ethereum 1.0 and 2.0 client for resource-restricted devices.
- [nimbus-eth2](https://github.com/status-im/nimbus-eth2) - Efficient implementation of the Ethereum 2.0 blockchain.
- [evmc](https://github.com/status-im/nim-evmc) - Ethereum VM binary compatible interface.
- [ethash](https://github.com/status-im/nim-ethash) - A pure-Nim implementation of Ethash, the Ethereum proof of work.
- [contract-abi](https://github.com/status-im/nim-contract-abi) - Implements encoding of parameters according to the Ethereum Contract ABI specification.
<!-- - [web3](https://github.com/status-im/nim-web3) - The humble beginnings of a Nim library similar to web3.[js|py]. -->
<!-- - [abc](https://github.com/status-im/nim-abc) - Experimental asynchronous blockchain. -->
<!-- - [nitro](https://github.com/status-im/nim-nitro) - Highly experimental implementation of the Nitro statechannels protocol in Nim. -->


### Compression

- [zippy](https://github.com/guzba/zippy) - Pure Nim implementation of deflate, zlib, gzip and zip.
- [supersnappy](https://github.com/guzba/supersnappy) - Dependency-free and performant Nim Snappy implementation.
- [snappy](https://github.com/status-im/nim-snappy) - Nim implementation of Snappy compression algorithm.
- [zip](https://github.com/nim-lang/zip) - Wrapper for the zip library.


## User Interface

### Terminal

- [illwill](https://github.com/johnnovak/illwill) - Simple cross-platform terminal library inspired by (n)curses.
- [NimCx](https://github.com/qqtop/NimCx) - Color and utilities for the Linux terminal.
- [pager](https://git.sr.ht/~reesmichael1/nim-pager) - A simple command line pager library, written in Nim.


### Design

- [chroma](https://github.com/treeform/chroma) - Everything you want to do with colors, in Nim.
- [typography](https://github.com/treeform/typography) - Fonts, typesetting and rasterization.
- [trick](https://github.com/exelotl/trick) - Library for GBA/NDS image conversion, and more!
- [HexToAnsi](https://github.com/farias-hecdin/HexToAnsi/blob/main/src/nim/README.md) - Convert hexadecimal colors to ANSI colors.


### GUI

#### Crossplatform

- [nimx](https://github.com/yglukhov/nimx) - Desktop, Mobile & Web GUI framework in Nim.
- [NiGui](https://github.com/trustable-code/NiGui) - A cross-platform, desktop GUI toolkit.
- [ui](https://github.com/nim-lang/ui) - Wrapper for libui. Beginnings of what might become Nim's official UI library.
- [uing](https://github.com/neroist/uing) - Wrapper & bindings for libui-ng, an updated and maintained fork of libui.
- [iup](https://github.com/nim-lang/iup) - Wrapper for IUP. Beginnings of what might become Nim's official UI library.
- [SDL2](https://github.com/nim-lang/sdl2) - Official wrapper for SDL 2.x.
- [SDL2](https://github.com/Vladar4/sdl2_nim) - A wrapper for SDL 2.
- [Owlkettle](https://github.com/can-lehmann/owlkettle) - Declarative user interface framework based on GTK.
- [libtray](https://github.com/neroist/libtray) - Nim wrapper for Tray (dmikushin's fork), a library to create system tray/menu bar icon with a popup menu.


#### Windows

- [wNim](https://github.com/khchen/wNim) - Nim's Windows GUI Framework.


#### Linux

- [gintro](https://github.com/StefanSalewski/gintro) - High-level GObject-Introspection based GTK3/GTK4 bindings for Nim.
- [nimqml](https://github.com/filcuc/nimqml) - Qt QML bindings for the Nim programming language.


#### Web Technology

- [Neel](https://github.com/Niminem/Neel) - A library for making Electron-like HTML/JS GUI apps.
- [nimview](https://github.com/marcomq/nimview) - A Nim/Webview based helper to create desktop/server applications with Nim and HTML/CSS.
- [webgui](https://github.com/juancarlospaco/webgui) - Web technologies based cross-platform GUI Framework with a dark theme.
- [fidget](https://github.com/treeform/fidget) - Figma based UI library for Nim, with HTML and OpenGL backends.
- [nsciter](https://github.com/Yardanico/nsciter) - High-level and low-level Nim wrapper for https://sciter.com.
- [webview](https://github.com/neroist/webview) - Nim bindings and wrapper for Webview.
- [webui](https://github.com/webui-dev/nim-webui) - Nim bindings and wrapper for WebUI.


#### Lightweight

- [imgui](https://github.com/nimgl/imgui) - ImGui bindings for Nim via cimgui.
- [nimAntTweakBar](https://github.com/krux02/nimAntTweakBar) - Wrapper for AntTweakBar.


### Plotting

- [ggplotnim](https://github.com/Vindaar/ggplotnim) - A port of ggplot2 for Nim.
- [plotly](https://github.com/SciNim/nim-plotly) - A plotly wrapper for Nim.
- [graph](https://github.com/stisa/graph) - A basic plotting library in Nim.
- [nimetry](https://github.com/refaqtor/nimetry) - Simple plotting in pure Nim.
- [nimgraphviz](https://github.com/Aveheuzed/nimgraphviz) - A Nim library for making graphs with GraphViz and DOT.


## Web

### Protocols

- [http-utils](https://github.com/status-im/nim-http-utils) - HTTP helper procedures.
- [puppy](https://github.com/treeform/puppy) - Puppy fetches HTML pages for Nim.
- [netty](https://github.com/treeform/netty) - Reliable UDP connection library for games in Nim.
- [json-rpc](https://github.com/status-im/nim-json-rpc) - Nim library for implementing JSON-RPC clients and servers.
- [nmqtt](https://github.com/zevv/nmqtt) - Native Nim MQTT client library.
- [libp2p](https://github.com/status-im/nim-libp2p) - A Nim implementation of the libp2p networking stack.
- [libp2p-dht](https://github.com/status-im/nim-libp2p-dht) - DHT based on the libp2p kademlia spec.
- [webdavclient](https://github.com/beshrkayali/webdavclient) - WebDAV client for Nim.
- [stomp](https://github.com/subsetpark/nim-stomp) - A pure-Nim client library for interacting with Stomp compliant message brokers.
- [presto](https://github.com/status-im/nim-presto) - An efficient REST API framework.
- [gemini](https://github.com/benob/gemini) - Building blocks for creating Gemini servers and clients.
- [yahttp](https://github.com/mishankov/yahttp) - Awesome simple HTTP client.


#### DNS

- [ndns](https://github.com/rockcavera/nim-ndns) - A pure Nim Domain Name System (DNS) client.
- [dnsprotocol](https://github.com/rockcavera/nim-dnsprotocol) - Domain Name System (DNS) protocol for Nim programming language.


#### QUIC

- [quic](https://github.com/status-im/nim-quic) - QUIC for Nim. This is very much a work in progress, and not yet in a usable state.
- [ngtcp2](https://github.com/status-im/nim-ngtcp2) - A wrapper around ngtcp2: an effort to implement IETF QUIC protocol.


#### Websockets

- [ws](https://github.com/treeform/ws) - Simple WebSocket library for Nim.
- [websocket.nim](https://github.com/niv/websocket.nim) - WebSockets for Nim.
- [news](https://github.com/Tormund/news) - Nim Easy WebSocket. Based on ws.
- [jswebsockets](https://juancarlospaco.github.io/nodejs/nodejs/jswebsockets) - WebSockets optimized for JavaScript targets.
- [websock](https://github.com/status-im/nim-websock) - An implementation of the WebSocket protocol for Nim.


#### Messaging

- [telebot.nim](https://github.com/ba0f3/telebot.nim) - Async client for Telegram Bot API in pure Nim.
- [dimscord](https://github.com/krisppurg/dimscord) - A Discord Bot & REST Library for Nim.
- [nwaku](https://github.com/status-im/nwaku) - Implementation of the Waku v1 and v2 protocols.
- [status](https://github.com/status-im/nim-status) - Nim implementation of the Status protocol.


#### Multicast

- [nimMulticast](https://github.com/enthus1ast/nimMulticast) - UDP Multicast made simple.


### HTML Parsers

- [Nimquery](https://github.com/GULPF/nimquery) - Library for querying HTML using CSS selectors, like JavaScript's `document.querySelector`.


### HTTP Servers

- [httpbeast](https://github.com/dom96/httpbeast) - A highly performant, multi-threaded HTTP 1.1 server ([top 10 in FrameworkBenchmarks](https://www.techempower.com/benchmarks/#section=data-r18&test=json)).
- [httpx](https://github.com/ringabout/httpx) - Cross platform web server for Nim. A fork of httpbeast adding Windows support.
- [GuildenStern](https://github.com/olliNiinivaara/GuildenStern) - Genuinely multithreading integrated HTTP/1.1 + WebSocket v13 Server for POSIX-compliant OSes.
- [Mummy](https://github.com/guzba/mummy) - A multi-threaded HTTP 1.1 server with first-class support for WebSockets.
- [netkit](https://github.com/iocrate/netkit) - Out-of-the-box, stable and secure network facilities and utilities written in pure Nim.
- [jshttp2](https://juancarlospaco.github.io/nodejs/nodejs/jshttp2) - Async HTTPS 2.0 web server.

### Gemini Servers

- [Geminim](https://github.com/ardek66/geminim) - A Gemini server.
- [Nemini](https://codeberg.org/pswilde/Nemini) - A very simple Gemini server for serving static gemtext files.

### Frameworks

- [Jester](https://github.com/dom96/jester) - The sinatra-like web framework for Nim. Jester provides a DSL for quickly creating web applications in Nim.
- [prologue](https://github.com/planety/prologue) - A fullstack web framework written in Nim.
- [whip](https://github.com/mattaylor/whip) - Simple and fast HTTP server for Nim based on httpbeast and nest for high performance routing.
- [basolato](https://github.com/itsumura-h/nim-basolato) - A fullstack web framework for Nim based on Jester.
- [karax](https://github.com/karaxnim/karax) - A framework for developing single page applications in Nim.
- [happyx](https://github.com/HapticX/happyx) - A macro-oriented full stack asynchronous web framework written in Nim.
- [scorper](https://github.com/bung87/scorper) - A micro and elegant web framework written in Nim.
- [starlight](https://github.com/planety/starlight) - Flask-like web framework written in Nim.
- [rosencrantz](https://github.com/andreaferretti/rosencrantz) - DSL to write web servers, inspired by Spray and its successor Akka HTTP.
- [nim_websitecreator](https://github.com/ThomasTJdev/nim_websitecreator) - Nim fullstack website framework - deploy a website within minutes.
- [nim-palladian](https://github.com/itsumura-h/nim-palladian) - Palladian is a Nim front-end framework based on and wrapped around Preact.


### Template Engines

- [Nim Source Code filters](https://nim-lang.org/docs/filters.html) - Nim's powerful built-in feature which can be used as a templating system or a preprocessor.
- [smalte](https://github.com/roquie/smalte) - It is a dead simple and lightweight template engine. Specially designed for configure application before start in Docker.
- [html-dsl](https://github.com/juancarlospaco/nim-html-dsl) - Nim HTML DSL.
- [templates](https://github.com/onionhammer/nim-templates) - A simple string templating library for Nim.
- [nimja](https://github.com/enthus1ast/nimja) - Typed and compiled template engine inspired by jinja2, twig and onionhammer/nim-templates for Nim.
- [mustache](https://github.com/soasme/nim-mustache) - A full implementation of v1.2.1 of the Mustache spec.
- [Tim](https://github.com/openpeeps/tim) - A high-performance template engine & markup language.


### Authentication

- [httpauth](https://github.com/FedericoCeratto/nim-httpauth) - HTTP Authentication library for Nim.
- [oauth](https://github.com/CORDEA/oauth) - OAuth library for Nim.


## Game Development

### Game Libraries

- [nimgl](https://github.com/nimgl/nimgl) - NimGL is a Nim library that offers bindings for popular libraries used in computer graphics.
- [glm](https://github.com/stavenko/nim-glm) - Port of the popular glm C++ library to Nim.
- [GLAD](https://github.com/Dav1dde/glad) - Multi-Language Vulkan/GL/GLES/EGL/GLX/WGL Loader-Generator based on the official specs.
- [enu](https://github.com/dsrw/enu) - 3D live coding with a Logo-like DSL for Godot, implemented in Nim.


### Game Frameworks

- [nico](https://github.com/ftsf/nico) - Nim Game Framework based on Pico-8.
- [natu](https://github.com/exelotl/natu) - Toolkit for writing Game Boy Advance games in Nim.
- [naylib](https://github.com/planetis-m/naylib) - safe Raylib wrapper.
- [c4](https://github.com/c0ntribut0r/cat-400) - Modular and extensible 2D and 3D game framework for Nim.
- [paranim](https://github.com/paranim/paranim) - A game library based around carefully chosen abstractions.


### Game Engines

- [NimForUE](https://github.com/jmgomez/NimForUE) - Nim plugin for UE5 with native performance, hot reloading and full interop that sits between C++ and Blueprints.
- [nimgame2](https://github.com/Vladar4/nimgame2) - A simple 2D game engine for Nim.
- [norx](https://github.com/tankfeud/norx) - A complete wrapper of the ORX 2.5D cross platform game engine library.
- [godot-nim](https://github.com/pragmagic/godot-nim) - Nim bindings for Godot Engine.
- [rod](https://github.com/yglukhov/rod) - Cross-platform 2D and 3D game engine.
- [frag](https://github.com/Tail-Wag-Games/frag) - Cross-platform 2D/3D game engine.
- [semicongine](https://github.com/saemideluxe/semicongine) - Cross-platform, (almost) dependency-free game engine.
- [saohime](https://github.com/glassesneo/saohime) - An extensible 2D game engine for Nim, inspired by Bevy Engine.
- [alasgar](https://github.com/abisxir/alasgar) - Pure nim 3D game engine based on OpenGL.


### Rules Engines

- [turn_based_game](https://github.com/JohnAD/turn_based_game) - A game rules engine for simulating or playing turn-based games.
- [pararules](https://github.com/paranim/pararules) - A RETE-based rules engine made for games.


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
- [nimgen](https://github.com/genotrance/nimgen) - nimgen is a helper for c2nim to simplify and automate the wrapping of C libraries. Superseded by nimterop.
- [nimterop](https://github.com/nimterop/nimterop) - A Nim package that leverages tree-sitter to make C/C++ interop seamless. Superseded by Futhark.
- [Futhark](https://github.com/PMunch/futhark) - Automatic wrapping of C headers in Nim with libclang.
- [nimpy](https://github.com/yglukhov/nimpy) - Generate Python wrappers and call Python from Nim.
- [jnim](https://github.com/yglukhov/jnim) - Nim - Java bridge.
<!-- - [rnim](https://github.com/SciNim/rnim) - A bridge between R and Nim. Currently this is a barely working prototype. -->


### Build Systems / Package Management

- [ChooseNim](https://github.com/dom96/choosenim) - Installing and switching between Nim versions (à la rustup, pyenv).
- [Nake](https://github.com/fowlmouth/nake) - Describe your Nim builds as tasks.
- [Nawabs](https://github.com/Araq/nawabs) - A build system that throws away version numbering in favor of git hashes.
- [Nimble](https://github.com/nim-lang/nimble) - Nimble can be used as a build system.
- [nimph](https://github.com/disruptek/nimph) - Nim package hierarchy manager from the future.
- [nimby](https://github.com/treeform/nimby) - A very simple and unofficial package manager for Nim.
- [nifty](https://github.com/h3rald/nifty) - A decentralized pseudo package manager and script runner.
- [nsis](https://github.com/nim-libs/nsis) - Nim programming language setup tool.
- [nim-windows-container](https://github.com/sirredbeard/nim-windows-container) - A Windows Container with a complete Nim build environment.


### Logging

- [chronicles](https://github.com/status-im/nim-chronicles) - A crafty implementation of structured logging for Nim.
- [morelogging](https://github.com/FedericoCeratto/nim-morelogging) - Logging library for Nim.
- [watchtower](https://github.com/BeigeHornet151/watchtower) - Lightweight logging library with colorized output, log rotation, and context fields.



### Testing

- [faker](https://github.com/jiro4989/faker) - A Nim package that generates fake data for you.
- [balls](https://github.com/disruptek/balls) - A unittest macro to save the world, or at least your Sunday.
- [einheit](https://github.com/jyapayne/einheit) - A Nim unit testing library inspired by Python's unit tests.
- [asynctest](https://github.com/status-im/asynctest) - Complements the standard unittest module in Nim to allow testing of asynchronous code.
- [unittest2](https://github.com/status-im/nim-unittest2) - Fork of the "unittest" Nim module focusing on parallel test execution, test-level scoping and strict exception handling.


### Fuzzing

- [drchaos](https://github.com/status-im/nim-drchaos) - A powerful and easy-to-use fuzzing framework in Nim for C/C++/Obj-C targets.
- [libfuzzer](https://github.com/planetis-m/libfuzzer) - LibFuzzer's interface bindings.


### Benchmarking

- [golden](https://github.com/disruptek/golden) - A benchmark for compile-time and/or runtime Nim.
- [timeit](https://github.com/xflywind/timeit) - Measuring execution times written by Nim.
- [criterion](https://github.com/disruptek/criterion) - Statistic-driven micro-benchmark framework.
- [stopwatch](https://gitlab.com/define-private-public/stopwatch) - A fork of rbmz's stopwatch that adds extra features.
- [nimbench](https://github.com/ivankoster/nimbench) - A micro benchmark module for Nim.


### Command-Line Interface Automation

- [cligen](https://github.com/c-blake/cligen) - Infer & generate command-line interace/option/argument parsers.
- [docopt.nim](https://github.com/docopt/docopt.nim) - Command-line args parser.
- [argparse](https://github.com/iffy/nim-argparse) - Argument parsing for Nim.
- [clapfn](https://github.com/oliversandli/clapfn) - Argument parsing similar to Python's argparse.
- [cliche](https://github.com/juancarlospaco/cliche) - AutoMagic CLI argument parsing is so cliché.
- [loki](https://github.com/beshrkayali/loki) - A small library for writing line-oriented command interpreters in Nim.
- [confutils](https://github.com/status-im/nim-confutils) - Simplified handling of command line options and config files
- [Cmdos](https://github.com/farias-hecdin/Cmdos) - A simple way to process cli arguments and help messages.

## Resources

### Books

- [Nim in Action](https://book.picheta.me/) - Book in Manning's "in Action" series, teaching Nim through 3 practical projects including CLI chat apps, web apps and parsers.
- [Computer Programming with Nim](https://ssalewski.de/nimprogramming.html) - A gentle introduction to the Nim programming language.
- [Nim Basics](https://narimiran.github.io/nim-basics/) - Tutorial for beginners and people just starting with Nim.
- [Nim Style Guide](https://status-im.github.io/nim-style-guide/) - Status style guide for the Nim language.
- [Mastering Nim](https://www.amazon.com/Mastering-Nim-complete-programming-language/dp/B0B4R7B9YX) - A complete guide to the programming language.


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
- [The Nim Matrix room](https://matrix.to/#/#nim-lang:matrix.org)


### Tutorials

- [Nim Days](https://xmonader.github.io/nimdays/) - A project to document my journey with Nim with mini applications, libraries documented from A to Z and also to provide new Nim users with some extra in depth information.
- [How I start](https://howistart.org/posts/nim) - Great guide going from 0 to a bf interpreter and then a bf to Nim compiler.
- [Learn Nim in Y minutes](https://learnxinyminutes.com/docs/nim/) - Whirlwind tour.
- [Nim by Example](https://nim-by-example.github.io) - Series of pages and examples for learning the Nim programming language.
- [Nim for Python programmers](https://github.com/nim-lang/Nim/wiki/Nim-for-Python-Programmers) - Guide to Nim for people with experience in Python.
- [Nim on Rosetta Code](https://rosettacode.org/wiki/Category:Nim) - Thousands of solutions for various tasks using Nim.
- [Nim Memory](http://zevv.nl/nim-memory/) - A small tutorial explaining how Nim stores data in memory.
- [Nim ARC](http://zevv.nl/nim-memory/nim-arc.html) - A friendly explanation of ARC and its implications for the programmer.
- [nimNx](https://github.com/dkgitdev/nimNx) - A Nintendo Switch Homebrew example project, written in Nim.
- [nimNxStatic](https://github.com/dkgitdev/nimNxStatic) - A static library example aiming to help integrate Nim code into the current Homebrew C projects for Nintendo Switch


### Videos

- [Nim's Official Channel](https://www.youtube.com/channel/UCDAYn_VFt0VisL5-1a5Dk7Q/videos) - Official videos introduce the powerful and interesting part in Nim language.
- [Nim for Beginners](https://www.youtube.com/user/kiloneie/playlists) - This is a video series meant to teach people programming in Nim to people who have never programmed before, or are new to Nim.
- [Make a website with Nim](https://www.youtube.com/watch?v=ndzlVRWqT2E&list=PL6RpFCvmb5SGw7aJK1E4goBxpMK3NvkON) - This is a video series meant to teach people make a website with Nim using `jester`.
- [Learning Nim](https://www.youtube.com/watch?v=I_Y94G37iR4&list=PLu-ydI-PCl0PqxiYXQMmLh7wjQKm5Cz-H) - Tutorial video series on learning Nim showcasing various features of the language and its libraries.
- [araq twitch](https://www.twitch.tv/araq4k) - The live broadcast regarding Nim language.
- [alehander42 twitch](https://www.twitch.tv/alehander42) - The live broadcast regarding Nim language.
- [clyybber twitch](https://www.twitch.tv/clyybber) - The live broadcast regarding Nim language.
- [d0m96 twitch](https://www.twitch.tv/d0m96) - The live broadcast regarding Nim language.
- [disruptek twitch](https://www.twitch.tv/disruptek) - The live broadcast regarding Nim language.
- [Nim Tutorials](https://www.youtube.com/playlist?list=PLYBJzqz8zpWaiGbFcSdlh08zlpe8Tl_Gh) - YouTube video series that teaches how to program in Nim and goes over various standared libraries.


---

### Footnotes
*Awesome-Nim logo is based on the "Nim Crown" logo by Joseph Wecker, used with permission from the Nim project.*
