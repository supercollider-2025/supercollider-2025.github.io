
+++
date = '2025-01-24T21:30:10-05:00'
draft = false
title = 'Paper Session 4'
+++

Saturday, March 15, 2025  
10:20am - 11:40am  
TBD

## ARCube

Hyunkyung Shin  
10:20am

The study presents a SuperCollider-based spatial audio performance system that leverages an augmented reality (AR) interface, the ARCube. For real-time control and creative manipulation of spatialized sound, the system demonstrates how SuperCollider’s flexibility in handling complex synthesis and spatialization algorithms, combined with OSC (Open Sound Control) data from an AR interface, can be effectively harnessed for interactive and expressive live music performances.

The SuperCollider system is structured to receive high-frequency OSC messages (100 Hz) from the ARCube, which transmits 3D positional data (azimuth, elevation, distance) to dynamically control sound sources and spatial effects. Key scripts developed in SuperCollider include definitions for multi-channel spatial encoders and SynthDefs designed for various sound processes, such as pitch shifting, delay feedback, and spectral filtering. A central HOA (Higher Order Ambisonics) encoder processes the spatial positioning data from OSC messages, allowing the system to route audio sources through a 3D spatial field. SuperCollider groups and audio buses manage these HOA-encoded channels, enabling interactive manipulation of sound positions and effects through the user’s gestures with the ARCube.

The ARCube’s OSC data is parsed by SuperCollider and assigned to control buses. These control buses then map the received parameters to specific SynthDefs, such as grain effects and filters, enabling nuanced audio transformations directly influenced by the ARCube’s real-time positional updates. Gesture-based controls, such as Grab and Pinch, are mapped to functions like sound rotation, source movement, and synthesis parameter modulation, creating a tightly coupled feedback loop between performer gestures and sound transformations, fostering an intuitive interface for spatial audio control.

To validate the system’s efficacy, a creative performance was designed with trained performers. Through this performance, performers showcased extensive creative interaction and auditory perception using the AR interface. This highlights SuperCollider’s potential, with its flexible OSC integration and real-time DSP (Digital Signal Processing) capabilities, to significantly enhance creative expression in spatial audio performance. This work underscores SuperCollider’s suitability for complex spatialization and interaction scenarios, demonstrating a framework for AR-enabled spatial audio systems in live, immersive music performances.

## Performing and Sharing Laptop Ensemble Repertoire

Joo Won Park  
10:40am

Laptop ensemble repertoire has a better chance for repeat performance if they have low technical, technological, and cost barriers. Composers can make and share such pieces by making easy-to-render SuperCollider codes and clear instructions. In this session, I will present two examples performed by multiple ensembles consisting of beginner SuperCollider users or electronic musicians.

## Declarative SuperCollider

Scott Carver  
11am

Abstract Needed

## Stecker

Dennis Scheiba  
11:20am

Stecker is a project which enhances the sound generating nature of SuperCollider by providing a native way of distributing and receiving low-latency audio and data-streams over the internet within SuperCollider using WebRTC.

This is achieved by providing a set of  UGens which can receive and transmit such signals and also a web server, which takes care of the administration and distribution of said signals and allows users to listen or generate streams from within their browser.

Stecker is inspired by JITLib and live coding in general, and is also intended to serve as a platform by providing "community radio stations" which allow for on-the-fly remixing as well as establishing and exploring new places for acoustic performances and sources.

