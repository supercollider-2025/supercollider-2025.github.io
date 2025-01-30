
+++
date = '2025-01-24T21:30:10-05:00'
draft = false
title = 'Paper Session 4'
+++

Saturday, March 15, 2025  
10:20am - 11:40am  
Location TBA

## ARCube

[Hyunkyung Shin](/bios/#hyunkyung-shin)  
10:20am

The study presents a SuperCollider-based spatial audio performance system that leverages an augmented reality (AR) interface, the ARCube. For real-time control and creative manipulation of spatialized sound, the system demonstrates how SuperCollider’s flexibility in handling complex synthesis and spatialization algorithms, combined with OSC (Open Sound Control) data from an AR interface, can be effectively harnessed for interactive and expressive live music performances.

The SuperCollider system is structured to receive high-frequency OSC messages (100 Hz) from the ARCube, which transmits 3D positional data (azimuth, elevation, distance) to dynamically control sound sources and spatial effects. Key scripts developed in SuperCollider include definitions for multi-channel spatial encoders and SynthDefs designed for various sound processes, such as pitch shifting, delay feedback, and spectral filtering. A central HOA (Higher Order Ambisonics) encoder processes the spatial positioning data from OSC messages, allowing the system to route audio sources through a 3D spatial field. SuperCollider groups and audio buses manage these HOA-encoded channels, enabling interactive manipulation of sound positions and effects through the user’s gestures with the ARCube.

The ARCube’s OSC data is parsed by SuperCollider and assigned to control buses. These control buses then map the received parameters to specific SynthDefs, such as grain effects and filters, enabling nuanced audio transformations directly influenced by the ARCube’s real-time positional updates. Gesture-based controls, such as Grab and Pinch, are mapped to functions like sound rotation, source movement, and synthesis parameter modulation, creating a tightly coupled feedback loop between performer gestures and sound transformations, fostering an intuitive interface for spatial audio control.

To validate the system’s efficacy, a creative performance was designed with trained performers. Through this performance, performers showcased extensive creative interaction and auditory perception using the AR interface. This highlights SuperCollider’s potential, with its flexible OSC integration and real-time DSP (Digital Signal Processing) capabilities, to significantly enhance creative expression in spatial audio performance. This work underscores SuperCollider’s suitability for complex spatialization and interaction scenarios, demonstrating a framework for AR-enabled spatial audio systems in live, immersive music performances.

## Performing and Sharing Laptop Ensemble Repertoire

[Joo Won Park](/bios/#joo-won-park)  
10:40am

Laptop ensemble repertoire has a better chance for repeat performance if they have low technical, technological, and cost barriers. Composers can make and share such pieces by making easy-to-render SuperCollider codes and clear instructions. In this session, I will present two examples performed by multiple ensembles consisting of beginner SuperCollider users or electronic musicians.

## Declarative SuperCollider

[Scott Carver](/bios/#scott-carver)  
11am

Abstract Needed

## Expanding the landscape of SC through multimodal art

[Joel Ong](/bios/#joel-ong)  
11:20am

At the symposium, I will present a series of works that make use of Supercollider (SC) to organize, sonify data and manage interactions through a variety of means. For example, Aeolian Traces (2016) was a multi sensory project exploring spatial sound and data visualization of narratives of human migration, including community focused work on the undocumented migrant population in Seattle. The system centrally run through SC uses geolocation datasets to drive wind currents through Arduino controlled cooling fans, networking with Processing for real time visualization, and spatial sound propagation through a low cost Ambisonic 16 channel setup. Similarly, in, Birdsong Diamond (2015-19) a user interface was built in SC to control the interactive component of the installation where visitors were invited to mimic birdsongs and given an eventual score for their attempts. More recently, the project untitled interspecies umwelten (2022-current) is an artistic research project exploring expanded and computer-mediated experiences of conversation with other species.  The project networks computer vision, LLM APIs to control interaction, text generation.  Responding to the question of the future of SC, these humble experiments propose to highlight the way SC can be instrumental as a central control system for multi-programmatic outputs.  I am more immediately a part of the user-group that has a limited but sustained experience with SC and moderate dexterity within its programming environment, so accessibility and longevity of these tools are one reason SC has remained a pivotal tool for my work. My aim at this conference would be to learn and adopt new approaches and in envisioning them within ongoing and new project, help shape its role in the future of creative systems and collaborative work.

