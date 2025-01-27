
+++
date = '2025-01-24T21:30:10-05:00'
draft = false
title = 'Paper Session 1'
+++

Thursday, March 13, 2025  
10:20am - 11:40am  
Location TBA

## YAWN

[Mike McCormick](/bios/#mike-mccormick)  
10:20am

The experimental metal band YAWN formed in 2020 during the COVID-19 pandemic with the goal of creating and performing uncompromising instrumental music characterized by low-tuned guitars, a complex rhythmic language, and detailed sound design.

High production value is a defining feature of this genre, and instead of relying on commercial softwares that impose certain normative performance practices, we decided shortly after the band's formation to rely on SuperCollider to synchronize click track playback, MIDI automation of effects and presets on digital guitar amplifiers, backing track playback, and our pre-programmed light show. After several years of touring with this setup, the software has grown to accommodate unconventional performative or rhythmic concepts and our musical aesthetic has fully embraced the idiosyncrasies afforded by this tailor-made approach.

In this talk I will present an overview of the SuperCollider classes I've been developing for YAWN since 2020, how the system has evolved to address the unique performative challenges presented by our music, and how it interfaces with the rest of our setup in concert. I'll also share how SuperCollider has been a central tool in our ongoing areas of research, which include generative aural "scores" and tempo polyphony.

## MIRLCa

[Anna Xambó](/bios/#anna-xambó)  
10:40am

In this presentation, I will introduce the state of affairs of the development of MIRLCa, a self-built tool in SuperCollider. The ongoing SC extension is a user-friendly live coding environment that allows the live coder to query crowdsourced sounds from the Freesound online database using MIR techniques together with interactive machine learning based on the FluCoMa library. This results in a crafted sound-based music style governed by a diverse chorale of sounds that the live coder attempts to tame. The presentation will cover both technical developments and artistic outcomes of using the tool.

## JITLib

[James Harkins](/bios/#james-harkins)  
11am

SuperCollider's Just-In-Time Library (JITLib) supports free experimentation with a wide variety of signal processing strategies, making it a good choice for SynthDef development and for teaching non-programmers. On its own, however, particularly for students, it poses some challenges: a lack of clear best practices for managing signal topology and routing, and the fact that a JITLib code document reflects a work-in-progress and may not unambiguously show the current state of the system. My JITModular project uses JITLib as a monophonic modular synthesizer, building on top of JITLib: 1/ clear, consistent recommendations for signal handling; 2/ a graphical interface to the side of the code window, providing access to parameters and displaying the current state; 3/ unified controls; 4/ a patch-saving mechanism that preserves code, state and resources (e.g. buffers and MIDI controllers). This workshop will introduce these features and demonstrate their pedagogical value. (Topics: live coding, extensions of sclang)

## supercollider-gst-rtp

[Bruno Gola](/bios/#bruno-gola)  
11:20am

In this paper presentation I introduce a framework for multichannel audio streaming from SuperCollider to mobile phones and other devices that support WebRTC, using RTP (Real-time Transport Protocol) and WebRTC together with the Janus WebRTC Gateway. The main feature related to SuperCollider is the supercollider-gst-rtp plugin, published as an opensource SuperCollider plugin. The supercollider-gst-rtp plugin allows the user to define multiple inputs (on different UDP ports) and outputs (as a combination of host and port) to stream any audio signal direct from a Synth definition, or to receive an audio stream also inside the Synth definition. This approach opens possibilities not only for multichannel pieces but also for easy and flexible audio communication over the network direct from SuperCollider without the need of external tools.

