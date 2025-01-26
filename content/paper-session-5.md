
+++
date = '2025-01-24T21:30:10-05:00'
draft = false
title = 'Paper Session 5'
+++

Saturday, March 15, 2025  
3pm - 4:20pm  
Location TBA

## THE COMPOSITION OF INTERACTIONS IN ‘GUERREIRA DAS PEDRAS’ (2024)

[Alfonso Fellipe Romagna](/bios/#alfonso-fellipe-romagna)  
3pm

*Keywords: SuperCollider, MediaPipe, openFrameworks, Creative processes, Interactive Systems*

This work presents the creative and compositional processes in the piece Guerreira das Pedras (2024) for saxophone, dance, video, and real-time electronics. In this paper, we prioritize an emphasis on the conceptual aspect, where we discuss the main artistic intentions and how the poetics of the piece influenced the choice of tools in the creative workflow involving interactive and multimodal systems. The text presents the artistic motivations, a description of processes and interconnections, a description of the computational model, as well as reflections on the relationship between aesthetic intentions and technological choices. Part of the methodology presented is inspired by the proposal of composer and researcher Marije Baalman, where some visual symbols were also used to exemplify the workflows and procedures carried out.

## Block SuperCollider

[Rohan Drape](/bios/#rohan-drape)  
3:20pm

*Keywords: open-source programming language design, interactive music systems, alternative language clients for scsynth*

Block SuperCollider is an experimental visual programming language specialised for writing programs for the SuperCollider synthesiser. The system investigates eight areas of research: 1. rich-text editors for SuperCollider programs, 2. rendering program texts as interactive control surfaces, 3. browser based editors for the WebAssembly SuperCollider synthesiser, 4. tablet and pen based editors for SuperCollider programs, 5. environments for musicians who are non-programmers working with SuperCollider, 6. literate programming systems for SuperCollider programs, 7. simple systems for sharing SuperCollider programs with non-experts, and 8. bi-directional translation between notational systems. This essay provides a rationale for and overview of the Block SuperCollider system, describes its operation and implementation, reviews related work, and discusses directions for future research.

## ChessSynth

[Victor Zheng](/bios/#victor-zheng)  
3:40pm

I propose to introduce ChessSynth, a framework built in SuperCollider for procedurally generating a soundtrack in real time to chess games. I will describe my methodology and algorithm design and then present some demonstrations of sample generations of chess games. This work touches upon algorithmic composition, data sonification, and potentially asks the question of using a non-musical entity such as chess as a factor in live performance of music.

## Polytempic Music with SuperCollider

[Derek Worthington](/bios/#derek-worthington)  
4pm

I began composing polytempic music – music in multiple tempos simultaneously – using a ruler and pencil, measuring out relative bar lengths to line up parts. This was extremely labor intensive, and if I wanted to change any tempo relationships, everything would need to be completely redone. So I used SuperCollider to build a visual system to make the compositional workflow as smooth as possible.

The system creates timelines for each unique tempo stream and aligns them vertically, marking beats and measures horizontally. Tempos can be entered as a number or as a ratio with another part; the system takes care of the calculations and rescales the beats appropriately. Tempo changes can be added on any beat, or mapped to an LFO or user-defined envelope to vary smoothly over time. The alignment points between timelines can be changed as desired, automatically shifting everything horizontally. The length of each timeline can be adjusted, and a zoom feature allows detailed work on any small part of the full composition.

Rhythms may be entered with a mouse click. Highlighting and dragging, and augmentation and diminution functions, allow rhythms to be easily entered, edited, copied, and rearranged. A playback feature can provide simple clicks and boops, or send OSC signals to separate synthesizers in which melodies and chords may be programmed. This is not meant to produce ‘final’ audio that a listener would hear, but as a way for the composer to hear a simple representation of the rhythms and melodies they’re working with. This feedback is extremely useful to get a concrete sense of more oblique or complicated tempo relationships.

For this presentation I will discuss the system in detail and show examples of how it has been and could be used.

