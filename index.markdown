---
layout: default
---
I am a software and hardware enthusiast. I like making software and hardware projects and learning about the interface between the two. 
In recent years I became interested in ASIC design on the RTL and micro-architecture level.

# Hardware Projects

## RISC-V Processor with Audio Accelerator - Digital Design and IC Class, UC Berkeley
I implemented an in-order, 3-stage, RISC-V core with memory-mapped IO and BIOS memory to load programs on an FPGA. I also designed various IO circuits: UART to download program instructions,
FIFO to handle asynchronous buttons and switch signals from the development board, and a button parser that includes a synchronizer, debouncer, and edge detector.
I made an NCO and digital circuitry for Sigma-Delta DAC to produce audio output from the development board.

# Software Projects

## Gitlet - CS61B, UC Berkeley

I implemented a version control system with basic commands from Git called Gitlet as part of my data structures and algorithms class. I structured a hidden folder where the application was run. I serialized data structures and wrote them to files in the hidden folder to create presistance. I also wrote efficient algorithms to meet runtime requirements.

## Virtual Art Gallery

<video src="https://user-images.githubusercontent.com/17362800/207952910-e6cc1e04-79f5-45a2-882a-36fb79354839.mov" controls width="560" height="315" style="max-width: 730px;">
</video>

This is a terminal application that simulates an art gallery with a user system and a text file database. The app demonstrates persistence (information is maintained between sessions) and allows users to order and view paintings. It also has an employee login and orders to clients with data maintained in data structures (BST, Hash Table, Heap, and Linked List) written from scratch for the project. The video above demonstrates the ability of clients to log in and view paintings ordered by price. You can check out the source code [here](https://github.com/adam100150/virtual-art-gallery).

## Lyrics and Quotes

I love looking at meaningful lyrics and quotes so I made a website where people can share and talk about them. The website is built using Firebase Realtime Database and Svelte as its UI framework. Click [here](https://lyricsandquotes.org/) to go to the website and [here](lyricsandquotes) to see the design document.
