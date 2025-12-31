---
title: "73 Programming Project Ideas to Inspire and Challenge You"
source: "https://codecrafters.io/blog/programming-project-ideas"
author:
  - "[[CodeCrafters]]"
published:
created: 2025-12-31
description: "Curated list of project ideas for programmers who aren't sure what to build. We chose 73 projects that teach a lot and are fun to build."
tags:
  - "clippings"
---
Blog • Monday, Apr 14th 2025

[Karan Kalra](https://www.linkedin.com/in/karankalra97) Developer, CodeCrafters

[Sarup Banskota](https://twitter.com/sarupbanskota) Co-founder/CEO, CodeCrafters

Many developers want to start a side project but aren't sure what to build. The internet is full of ideas that are basic and dull.

Here's our list of 73 project ideas to inspire you. We have chosen projects that teach a lot and are fun to build.

## 1\. Bittorrent Client

Build a BitTorrent client that can download files using the BitTorrent protocol. You can start with single-file torrents. This is a great way to learn how P2P networking works.

Read the [official BitTorrent specification](https://www.bittorrent.org/beps/bep_0003.html) here.

## 2\. Wordle Solver

Build a program that solves Wordle. This can be a great lesson on information theory and entropy. You'll also get hands-on experience at optimizing computations.

This [YouTube video](https://www.youtube.com/watch?v=v68zYyaEmEA) will get you started.

## 3\. Deepfake

Implement Optimal Transport from scratch to morph one face into another while preserving identity and structure. You'll apply linear programming to a real problem.

![Deepfake](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fdeepfake.5b20fd7c.webp&w=3840&q=75)

You can try and morph your face on the Mona Lisa. Or maybe not...

Here are [some OT resources](https://github.com/kilianFatras/awesome-optimal-transport) and a [paper](https://proceedings.neurips.cc/paper_files/paper/2016/file/26f5bd4aa64fdadf96152ca6e6408068-Paper.pdf) which proposes a solution.

## 4\. Spreadsheet

Create a spreadsheet with support for cell references, simple formulas, and live updates. You'll learn about dependency graphs, parsing, and reactive UI design.

The founder of the GRID spreadsheet engine shares some insights [here](https://medium.grid.is/we-built-a-spreadsheet-engine-from-scratch-heres-what-we-learned-e4800ab9edf1).

## 5\. Container

Build a lightweight container runtime from scratch without Docker. You'll learn about kernel namespaces, chroot, process isolation, and more.

[Read this](https://igupta.in/blog/life-of-a-container/) to understand how containers work.

## 6\. Geometric Theorem Proving

Build a system that uses Euclid's postulates to derive geometric proofs and visualize the steps. You'll learn symbolic representation, rule systems, logic engines, and proof theory.

![Mizar](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fmizar.0961da34.png&w=1080&q=75)

[The Mizar project](https://mizar.uwb.edu.pl/) aims to formalize all of mathematics, and has been going on since the 1970s.

You can efficiently implement [Gelernter's visionary 1959 paper](https://aitopics.org/download/classics:FB935240) today.

## 7\. Googlebot

Google uses a crawler to navigate web pages and save their contents. By building one, you'll learn how web search works. It's also great practice for system design.

You can make your own list of sites and create a search engine on a topic of your interest.

This [article](https://jc1175.medium.com/how-i-would-design-a-web-crawler-9013251fa9f3) proposes a design approach.

## 8\. DNS Server

Build a DNS server that listens for queries, parses packets, resolves domains, and caches results. Learn more about low-level networking, UDP, TCP, and the internet.

Start with [how DNS works](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/) and dive into the [DNS packet format](https://mislove.org/teaching/cs4700/spring11/handouts/project1-primer.pdf).

## 9\. Six Degrees of Kevin Bacon

Build a game where players connect two actors through shared credits with other actors, and reveal the optimal path at the end. You'll learn how to deal with massive graphs.

![The Wiki Game](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fwikigame.934b957a.png&w=3840&q=75)

[The Wiki Game](https://www.thewikigame.com/group) is another fun version of the same concept.

Explore how to create fast graphs, and then try [Landmark Labelling](https://drops.dagstuhl.de/storage/00lipics/lipics-vol248-isaac2022/LIPIcs.ISAAC.2022.5/LIPIcs.ISAAC.2022.5.pdf) for supreme performance.

## 10\. RAFT

Implement the RAFT protocol from scratch to support distributed computing. Learn consensus, failure recovery, and how to build fault-tolerant distributed systems.

Visit [this page](https://raft.github.io/) for the RAFT paper and other resources.

## 11\. Procedural Crosswords

Design a program from scratch that creates satisfying crosswords with adjustable difficulty. You'll learn procedural generation, constraint propagation, and difficulty modeling.

![Procedural Generation](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fprocedural.4ac21de7.jpg&w=3840&q=75)

[No Man's Sky](https://www.youtube.com/watch?v=Yio9ypz5cHY) is the largest deterministic game till date. It features a procedurally generated open world that includes 18,446,744,073,709,551,616 planets.

For example, you can implement the Wave Function Collapse algorithm explained [here](https://robertheaton.com/2018/12/17/wavefunction-collapse-algorithm/).

## 12\. Bitcask

Bitcask is an efficient embedded key-value store designed to handle production-grade traffic. Building this will improve your understanding of databases and efficient storage.

You can implement this [short paper](https://riak.com/assets/bitcask-intro.pdf).

## 13\. Audio Fingerprinting

Apps like Shazam extract unique features from audio. This fingerprint is then used to match and identify sounds. You'll need to learn hash-based lookups and a bit of signal processing.

Here's a [detailed post](https://uni.johnwhite.it/Appunti/Teoria%20dei%20Segnali/TSG%20-%20Risorse/How%20does%20Shazam%20work%20-%20Coding%20Geek.pdf) with everything you need to know.

## 14\. Dangerous Dave

Recreate the industry-changing game using SDL, and add some story elements, NPC interactions, and levels. It'll be a perfect intro to game development.

![Dangerous Dave](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fdave.7464c20c.png&w=1920&q=75)

Dangerous Dave was created by the prolific game developer John Romero, who co-founded id Software and designed games like Wolfenstein 3D and Doom.

[This video](https://www.youtube.com/watch?v=kmECa4Gcckc&list=PLSkJey49cOgTSj465v2KbLZ7LMn10bCF9&index=1) will set you up.

## 15\. Diff Tool

Implement an algorithm from scratch to compare two text files or programs. This will involve dynamic programming and application of graph traversal.

Here's the [classic paper](https://publications.mpi-cbg.de/getDocument.html?id=8a8182da40fa742601410c5717da0008) behind Myers' diff, used in Git for years.

## 16\. Visualize object-oriented code

Generate UML class diagrams from source code with support for relationships like inheritance. You'll visualize object-oriented code and learn how to parse with ASTs.

![D & D](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fuml.a6da686b.webp&w=3840&q=75)

Here's another way to visualize object-oriented code.

[This article](https://medium.com/basecs/leveling-up-ones-parsing-game-with-asts-d7a6fc2400ff) explains parsing with ASTs.

## 17\. BMP Codec

Write your own encoder/decoder for the BMP image format and build a tiny viewer for it. You'll learn binary parsing, image encoding, and how to work with pixel buffers and headers.

[The Wikipedia article](https://en.wikipedia.org/wiki/BMP_file_format) is a good place to start.

## 18\. Filesystem

Build a FUSE filesystem for Linux from scratch, with indexing, file metadata, and caching. You'll have to optimize data structures for storage and performance.

[This article](https://blog.carlosgaldino.com/writing-a-file-system-from-scratch-in-rust.html) talks about the concepts used in filesystems.

## 19\. Quantum Computer Simulation

Write the qubit and quantum gates from scratch. Use them to simulate a circuit for a quantum algorithm like Bernstein-Vazirani or Simon's algorithm.

![Quantum](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fquantum.c53b0b96.jpg&w=828&q=75)

This is the best way to grasp quantum computing and develop an intuition for it.

Read [this short paper](https://sciendo.com/article/10.1515/aucts-2015-0084) for the essentials without any fluff.

## 20\. VLC

Write a video player that decodes H.264/H.265 using ffmpeg, and supports casting local files to smart devices. Learn packet buffering, discovery protocols, and stream encoding.

Get started with [this article](http://dranger.com/ffmpeg/ffmpeg.html).

## 21\. Redis

Build a Redis clone from scratch that supports basic commands, RDB persistence, replica sync, streams, and transactions. You'll get to deep dive into systems programming.

You can use the [official Redis docs](https://redis.io/docs/latest/develop/reference/protocol-spec/) as a guide.

## 22\. Video Editor

Build a client-side video editor that runs in the browser without uploading files to a server. Learn how to work with WASM, and why people love using it for high performance tasks.

![Video Editor](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fvideoeditor.d7229c0c.png&w=3840&q=75)

WASM and WebGL made it possible to serve 3D modelling sites on a web browser.

Visit the [official WebAssembly site](https://webassembly.org/) to get started.

## 23\. Auth Server with Sessions / JWT

This is a rite of passage. You'll get hands-on experience with encryption, token expiration, refresh flows, and how to manage user sessions securely.

Implement [username and password auth](https://auth0.com/blog/username-password-authentication/). Then manage sessions with [JWT or session IDs](https://www.youtube.com/watch?v=fyTxwIa-1U0).

## 24\. Autocomplete System

You have used it in searches and other places where you write text. Implement a solution that suggests the right words, and then optimize heavily for speed.

This [YouTube video](https://www.youtube.com/watch?v=SG9CPplNGgo) gives an idea of the implementation process.

## 25\. SQLite

Build a simple SQL engine that reads.db files, uses indexes and executes queries. It's a deep dive into how real-world databases are built and run efficiently.

![SQLite database](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsqlite.b55eaa7c.webp&w=3840&q=75)

SQL has been around for 50 years, showing how great abstractions can stand the test of time.

You need to understand [B-trees](https://medium.com/basecs/busying-oneself-with-b-trees-78bbf10522e7) and [how SQLite stores data on disk](https://www.sqlite.org/fileformat.html#b_tree_pages).

## 26\. Background Noise Remover

Remove background sounds from audio files. You'll learn signal processing and denoising techniques used in GPS, mouse input, sensors, object tracking, etc.

You can use a technique like [Kalman Filtering](https://www.kalmanfilter.net/default.aspx) to do this.

## 27\. Dropbox

Design a file sharing app with sync, cloud storage, and basic p2p features that can scale to some extent. You'll get practice in cloud architecture and backend design.

[This article](https://www.pankajtanwar.in/blog/system-design-how-to-design-google-drive-dropbox-a-cloud-file-storage-service) dives into the system design.

## 28\. Google Maps

Build a map engine to index roads, terrain (rivers, mountains), places (shops, landmarks), and areas (cities, states). Learn spatial indexing, range queries, and zoom-level abstractions.

Start by implementing an R-tree from scratch by following the [original paper](https://dl.acm.org/doi/pdf/10.1145/971697.602266).

![Quadtree](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fquadtree.ba1726ab.png&w=3840&q=75)

You can use Quadtrees instead of R-trees for a simpler implementation.

Use [Natural Earth](https://www.naturalearthdata.com/) and [GeoFabrik](https://www.geofabrik.de/) datasets to populate your map engine.

## 29\. Road Network

Recreate a city's road network, simulate traffic using real open data, and design an improved version. Tackle an NP-hard optimization problem with real constraints.

In some cases, nature has long solved what we call hard. Implement [SMA](https://en.wikiversity.org/wiki/Slime_Mould_Algorithm) or [ACO](https://www.youtube.com/watch?v=u7bQomllcJw) here.

## 30\. Collaborative Editor

Develop a decentralized collaborative text editor. Similar to Google Docs, but without any central server. Use CRDTs to manage concurrent edits and ensure eventual consistency.

Use ropes, gap buffers, or piece tables to build a fast text buffer optimized for efficient editing.

Read [this article](https://mattweidner.com/2022/02/10/collaborative-data-design.html) on designing data structures for such apps.

## 31\. Evolutionary Design

Evolve working models of machinery using only primitive mechanical parts and constraints. You'll learn about genetic algorithms, fitness functions, and physics simulation.

![Evolution](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fevolution.514b562c.webp&w=3840&q=75)

Simulating the problem constraints incorrectly can lead to some odd results...

You can design [bridges](http://www.demo.cs.brandeis.edu/papers/other/cs-97-191.html#resul), [cars](https://www.whiletrue.it/genetic_3-wheelers/), [clocks](https://www.youtube.com/watch?v=mcAq9bmCeR0), calculators, catapults, and more. [NASA used GAs to design an antenna for their space mission](https://ntrs.nasa.gov/api/citations/20030067398/downloads/20030067398.pdf).

This [YouTube video](https://www.youtube.com/watch?v=mcAq9bmCeR0) shows how interesting evolutionary design can get.

## 32\. Web Server

Create a server from scratch that supports HTTP requests, static files, routing, and reverse proxying. Learn socket programming and how web servers work.

[This page](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Overview) will get you started.

## 33\. Depth Estimation

Estimate a depth (disparity) map from a stereo image pair using Markov Random Fields. You'll learn about computer vision, graphical models, and inference techniques.

Start with the [Middlebury Dataset](https://vision.middlebury.edu/stereo/data/) and [this article](https://nghiaho.com/?page_id=1366) on belief propagation for stereo matching.

## 34\. Git

Build a minimal Git with core features like init, commit, diff, log, and branching. Learn how version control works using content-addressable storage, hashes, and trees.

![Git](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fgit.52598144.webp&w=3840&q=75)

Linus Torvalds built Git in 10 days, and never imagined it would last 20 years.

Check out [*Write yourself a Git*](https://wyag.thb.lt/) for an overview of git internals.

## 35\. GDB

Build a Unix debugger with stepping, breakpoints, and memory inspection. You'll learn low-level systems programming and process control.

[This article](https://aosabook.org/en/v2/gdb.html) discusses the internal structure of GDB.

## 36\. Neural Networks

Build a deep learning framework from scratch with a tensor class, autograd, basic layers, and optimizers. Grasp the internals of backpropagation and gradient descent.

Start by building a simple 3-layer feedforward NN (multilayer perceptron) with your framework.

Andrej Karpathy explains the basic concepts in this [YouTube Video](https://www.youtube.com/watch?v=VMj-3S1tku0).

## 37\. Chess

Build a Chess app from scratch, where users can play against each other or your own UCI engine. This project offers a blend of algorithms, UI, game logic, and AI.

You can go one step further and make the engine play itself to improve like AlphaZero and Leela.

![AlphaGo](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falphago.8fdda543.png&w=3840&q=75)

Watch AlphaGo on YouTube if you haven't already.

You can start with the [rules](https://www.chesshouse.com/pages/chess-rules) and the [chess programming wiki](https://www.chessprogramming.org/Main_Page).

## 38\. Wikipedia Search

Build a fast search engine from scratch for the Wikipedia dump with typo tolerance and semantic ranking, and fuzzy queries. You'll learn indexing, tokenization, and ranking algorithms.

[This article](https://itnext.io/building-a-search-engine-in-rust-c945b6e638f8) offers a good introduction to the basics of information retrieval.

## 39\. CDN Caching

Build a caching system to avoid redundant fetches for static assets. You'll learn web caching, log analysis, and how to use probabilistic data structures in a real setting.

You can use [this dataset](https://ita.ee.lbl.gov/html/contrib/NASA-HTTP.html) containing two month's worth of HTTP requests to the NASA server.

[This article](https://harish-bhattbhatt.medium.com/bloom-filter-application-and-implementation-52c6d4512c21) introduces some of the key concepts.

## 40\. TikTok

Build a short-video app with infinite scroll, social graphs of friends and subs, and a tailored feed. You'll learn efficient preloading, knowledge graphs, and behavioral signals.

![Doom Scrolling](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fdoomscroll.8bc8537e.webp&w=3840&q=75)

Build the next doom-scrolling app that hijacks attention spans and ruins sleep schedules.

Read [this article](https://www.aaronabraham.ca/technical-writing/tiktok-monolith-system) on Monolith, Bytedance's recommendation system.

## 41\. Time Sync Daemon

Implement NTP from scratch to build a background service that syncs system time with time servers. You'll learn daemon design and the internals of network time sync.

[RFC 5905](https://datatracker.ietf.org/doc/html/rfc5905) is a great place to start.

## 42\. Twitter Trends

Implement HyperLogLog from scratch to provide analytics on number of users engaging with hashtags in real time. You'll learn some key concepts around big data systems.

Start with [Google's paper on HyperLogLog](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/40671.pdf).

## 43\. SQL Optimizer

Write a query planner that rewrites SQL queries for better performance. You'll learn cost estimation, join reordering, and index selection.

![Bigquery](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fbigquery.085ccc99.png&w=3840&q=75)

It only takes a few rogue scripts hammering BigQuery to send your burn multiple into a nosedive.

[This DuckDB post](https://duckdb.org/2023/09/15/query-optimizer.html) explains how optimizers work.

## 44\. Anonymous Voting

Implement an encrypted voting system for anonymity. Use zero-knowledge proofs to verify results.

Learn cryptographic primitives, smart contracts, and ZKPs.

For example, [this paper](https://chinmaysonar.github.io/Projects/bc-zk-report.pdf) attempts to define such a protocol.

## 45\. VPN

Build a mesh VPN where nodes relay traffic without central servers. You'll learn NAT traversal, encrypted tunneling, and decentralized routing.

[Tailscale's blog](https://tailscale.com/blog/how-nat-traversal-works/) introduces some key concepts.

## 46\. Zip

Build a file archiver that compresses, bundles, and encrypts your files. Implement compression and encryption algorithms from scratch. Benchmark your performance against zip.

![Zip](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fzip.837110eb.webp&w=1920&q=75)

'your mama' jokes have clearly gone too far.

You can refer to the [official.zip specification](https://pkwaredownloads.blob.core.windows.net/pem/APPNOTE.txt).

## 47\. Ray Tracer

Build a basic ray tracer to render 3D scenes with spheres, planes, and lights. This will be great practice in writing clean abstractions and optimizing performance-heavy code.

You can refer to the [*Ray Tracing in One Weekend*](https://raytracing.github.io/books/RayTracingInOneWeekend.html#wherenext?/afinalrender) ebook.

## 48\. Programming Language

Create your own language. It is best to start with an interpreted language that does not need a complier. Design your own grammar, parser, and an evaluation engine.

[Crafting Interpreters](https://craftinginterpreters.com/contents.html) is by far the best resource you can refer to.

## 49\. Messenger

Recreate WhatsApp with chats, groups, history, encryption, notifications, and receipts. You'll get practice at building a production-grade app with an API, data store, and security.

You can draw inspiration from this [system design approach](https://interviewnoodle.com/how-i-would-design-facebook-messenger-384fc0d28787).

## 50\. Amazon Delivery

Build a service to provide routes for a fleet of vehicles with limited capacity to deliver Amazon packages. You'll learn to optimize routing under constraints.

![Amazon Delivery](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Famazondelivery.1dad64d8.webp&w=3840&q=75)

Use Google Maps API to visualize customers and routes.

Here's a comparison of effective [VRP algorithms](https://www.dline.info/dspai/fulltext/v2n1/dspaiv2n1_1.pdf).

## 51\. Kafka Broker

Build a basic broker to handle topic creation, produce and consume requests. You'll implement concurrency, avoid race conditions, and learn how distributed logs work.

Here's a [guide](https://ossrs.io/lts/en-us/assets/files/kafka-160915-0553-82964-c24c2b2f5caacb605a0ccec44e4eb9db.pdf) to the Kafka protocol.

## 52\. Knowledge Graph

Build an interactive knowledge graph that connects entities across media. Monitor the web for new content to keep it updated. You'll learn graph databases and data handling.

Explore this [GitHub repo](https://github.com/BrambleXu/knowledge-graph-learning) to learn about knowledge graphs and find some inspiration.

## 53\. Malware

Create a malware and test it against simple firewalls on your VMs. Don't share the code with anyone, though. This project is a solid intro to cybersecurity.

This [YouTube video](https://www.youtube.com/watch?v=zEk3mi4Pt_E) discusses the core concepts.

## 54\. Game Boy Advance Emulator

Emulate the iconic GBA. You'll learn about CPU architecture, memory, graphics, and input.

![GBA Emulator](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Femu.4e817091.webp&w=1080&q=75)

It'll be insanely rewarding the moment your first ROM boots up.

You can use the [GBATEK document](https://problemkaputt.de/gbatek.htm) to get started.

## 55\. TCP/IP stack

Implement a minimal userspace TCP/IP stack for Linux based on its core specification. You'll learn network and system programming at a deeper level.

You can get started with IETF's docs on [TCP](https://datatracker.ietf.org/doc/html/rfc7414), [IP](https://datatracker.ietf.org/doc/html/rfc791), [internet checksum](https://datatracker.ietf.org/doc/html/rfc1071), and more.

## 56\. Lock-Free Data Structures

Write your own lock-free data structures using atomic primitives. You'll learn a lot about concurrency, memory management, and atomic operations.

Read about the concept [here](https://en.wikipedia.org/wiki/Non-blocking_algorithm), and make sure to run a lot of tests like [these](https://brilliantsugar.github.io/posts/how-i-learned-to-stop-worrying-and-love-juggling-c++-atomics/).

## 57\. Load Balancer

Build a program to distribute requests across backend servers, check health, and support sessions. Learn about socket programming, concurrency, and scalable web infrastructure.

![Power of 2 random choices](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fp2.c6335544.png&w=1920&q=75)

[The power of two random choices](https://brooker.co.za/blog/2012/01/17/two-random.html) works surprisingly well here.

[This article](https://blog.envoyproxy.io/introduction-to-modern-network-load-balancing-and-proxying-a57f6ff80236) is an excellent intro to the topic.

## 58\. Malloc

Implement your own version of `malloc`. Learn how memory allocation works under the hood by working with pointers, heaps, alignment, fragmentation, and system calls.

[This tutorial](https://wiki-prog.infoprepa.epita.fr/images/0/04/Malloc_tutorial.pdf) by Marwan Burelle is the perfect place to start.

## 59\. Netflix

Build an app to host and stream 4k videos by writing a streaming protocol from scratch. You'll learn about file storage, video encoding, adaptive streaming, and scalable content delivery.

This [YouTube video](https://www.youtube.com/watch?v=kCAXpAikMVc) provides an overview of how it works.

## 60\. Smart Home

Build an app that controls IR appliances and manual switches with device grouping, scheduling, and automation. This project is a mix of embedded systems, app dev, and UI design.

![Smart Home](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsmart.ded8aeb7.webp&w=3840&q=75)

Finally...

Watch [this video](https://www.youtube.com/watch?v=y3kPYw9bgBk) for some inspiration.

## 61\. CI System

Build a Continuous Integration system that watches a Git repo, runs tests in isolated environments, and reports results. You'll learn process orchestration and containerization.

This concise [article](https://aosabook.org/en/500L/a-continuous-integration-system.html) will be helpful.

## 62\. Random Forest

Implement a decision tree from scratch and use it to solve a binary classification task with random forest. You'll learn information gain, recursive partitioning, and overfitting.

This [blog post](https://lethalbrains.com/learn-ml-algorithms-by-coding-decision-trees-439ac503c9a4) covers the basics.

## 63\. Shell

Build a shell with command parsing, process execution, piping, redirection, and job control. You'll learn a lot about system programming, memory, and operating systems.

[This article](https://aosabook.org/en/v1/bash.html) discusses its architecture.

## 64\. Bitcoin Node

Build a node that can download and verify blocks from the Bitcoin network. You'll learn about Merkle trees, transactions, Bitcoin's P2P protocol, and more.

![Ape NFT](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fape.3a9b1c8e.webp&w=3840&q=75)

Alternatively, you can use blockchain to sell hyperlinks to png files of apes.

You can refer to the Mastering Bitcoin ebook [here](https://github.com/bitcoinbook/bitcoinbook).

## 65\. Make

Write a simple `make` tool that reads a Makefile and builds targets. You'll explore some neat concepts around caching, filesystem, version control, and automation.

[This paper](https://aegis.sourceforge.net/auug97.pdf) discusses how it works, and also suggests a non-recursive `make`.

## 66\. Browser Extension

Build an extension to store passwords, OTPs, page state, scroll, forms, clipboard history, with auto-fill across sessions. You'll learn DOM inspection, secure storage, and sync protocols.

Start with the official [Chrome](https://developer.chrome.com/docs/extensions/get-started) or [Mozilla](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension) docs on extensions.

## 67\. Stock Trading Bot

Build a bot that uses trading algorithms to simulate or execute trades. Learn to structure event-driven systems, integrate APIs, and automate decisions under constraints.

![Trump2Cash](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Ftrump2cash.cc8eb9b6.png&w=3840&q=75)

[Trump2Cash](https://github.com/maxbbraun/trump2cash) is a bot that monitors Donald Trump's tweets to execute trades on mentioned stocks.

For example, [this paper](https://ijirt.org/publishedpaper/IJIRT153541_PAPER.pdf) describes one such algorithm you can implement.

## 68\. Browser Engine

Build a simple browser that parses HTML/CSS to render text and images. You'll learn tokenization, DOM trees, box models, style cascading, and layout algorithms.

[This blog series](https://limpet.net/mbrubeck/2014/08/08/toy-layout-engine-1.html) explains the basic concepts.

## 69\. Automated Journal

Build a background app that uses your phone's GPS, motion, and mic to identify events and store a journal of your life. You'll learn signal processing, sensor APIs, and background tasks.

[This article](https://aosabook.org/en/500L/a-pedometer-in-the-real-world.html) offers a glimpse into the experience of working with sensors.

## 70\. OpenGL

Build a tiny renderer from scratch. This'll make you a better programmer across the board, and it's a must if you're serious about computer graphics.

![Character Render](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fchar.e11b2b04.webp&w=1920&q=75)

Use the renderer to recreate your favorite characters.

[Read this wiki](https://github.com/ssloy/tinyrenderer/wiki/Lesson-0:-getting-started) to get started.

## 71\. Laser Tag

Build a laser tag system with real-time hit detection, wireless comms between guns, and live sync. You'll learn IR encoding, MQTT protocol, and lockstep/event-driven design.

[This project](https://hackaday.io/project/160804-lzrtag-flexible-diy-lasertag) attempts to do something similar.

## 72\. Audio Multicast

Build an audio streaming system from scratch that plays music in sync across multiple devices or speakers. You'll learn low-latency transport, clock sync, buffering, and jitter handling.

Snapcast explains its sync approach [here](https://github.com/badaix/snapcast?tab=readme-ov-file).

## 73\. Decentralized Internet

Build a p2p mesh network that routes traffic without ISPs or central servers. You'll learn distributed routing (like BGP for P2P), NAT traversal, and encrypted packet forwarding.

![Decentralized Internet](https://codecrafters.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fdecentralizedinternet.cac48e04.jpg&w=1920&q=75)

Credit for this idea goes to Richard Hendricks.

[The Scuttlebutt Protocol](https://scuttlebot.io/more/protocols/secure-scuttlebutt.html) and [IPFS](https://ipfs.tech/) are great references.

## Final Thoughts

That's a wrap.

If you do implement anything as a result of this post, or have any feedback on the ideas, [let us know](https://codecrafters.io/blog/)!