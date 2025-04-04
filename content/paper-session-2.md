
+++
date = '2025-01-24T21:30:10-05:00'
draft = false
title = 'Paper Session 2'
+++

Thursday, March 13, 2025  
**Room 426/428**  
4pm - 5:20pm  

## SCKinect

[Evan Murray](/bios/#evan-murray)  
4pm

[go to paper](/papers/Murray.pdf)

SCKinect is a SuperCollider plugin which allows users to interact with the Kinect v2 sensor in the server and language. Its core implementation contains a UGen called “Kinect,” designed to output human skeleton joint-tracking data to control buses. It will also include primitives designed to facilitate user interaction with Kinect devices. One example would be for users to be able to post all the available Kinect devices to the post window in SuperCollider, similar to how other human input devices work.

The shared benefit of the Kinect and SuperCollider is their ability to facilitate natural user interactions and artistic expression. The interpreted nature of SuperCollider and the server-language duality allows users to more-naturally communicate what they want to do, enabling them to focus on artistic expression. With the addition of the Kinect UGen, performers can interact with SuperCollider directly through their movement in an agent-less manner.

This project relates to interactive music systems and plugins for scsynth. Additionally, the GPU and CPU are both used here for visual and audio processing respectively. Although the GPU doesn’t directly provide audio, it is somewhat related to heterogeneous computing, as the CPU and GPU are both running the scsynth.

## Sound Matching

[Gerard Roma](/bios/#gerard-roma)  
4:20pm

[go to paper](/papers/Roma.pdf)

Sound matching is a classic problem in sound synthesis, originally proposed for controlling FM synthesis. Given a target sound, the problem is to find the parameters that a synthesizer could use to approximate the target. This paper describes an implementation of sound matching in SuperCollider, using the Fluid Corpus Manipulation toolbox. Given a synth definition designed by the user, the system trains a model that can approximate existing sounds by predicting synthesizer parameters. Matching can be performed for a whole buffer or continuously in real time.

## A Case Study of Music Glyph Notation in SuperCollider using SMuFL fonts

[Tom Hall](/bios/#tom-hall)  
4:40pm

*Keywords: extensions of sclang, live coding, multimedia music systems.*

This paper describes a dynamic ‘live’ music notation project using common practice Western notation (CPWN) ‘glyphs’ natively within SuperCollider. The project builds on work presented in a new co-authored ‘Notations’ chapter in the forthcoming 2nd edition of ‘The SuperCollider Book’, and aims to avoid any interaction with third-party music software common to related projects. A barrier to native SuperCollider implementation begins with displaying music glyphs. Since a specialist music font is required, glyphs cannot usefully be pasted as Unicode UTF-8 into an IDE. The ‘MITHUnicode’ dependency helper class translates between Unicode binary and hex encodings so that non-ASCII characters can be easily referred to and displayed in SuperCollider. Using Unicode identifiers and working specifically with music fonts, the W3C initiative ‘SMuFL’ (Standard Music Font Layout) enables font interoperability between different notation softwares. Glyphs comprising an extended CPWN superset are given unique Unicode code points as well as metadata to assist with complex positioning considerations for music display.

Combining these approaches, the class ‘THNoteViewer’ enables the dynamic presentation of CPWN notes and complex chords within a SuperCollider Window in a format similar to Max software’s ‘nslider’ Object. To do this requires determining the correct placement of music noteheads and music glyphs such as ‘accidentals’ (flats, sharps etc). To avoid collisions between glyphs, SMuFL metadata is imported into the class, and dependency classes using computational geometry such as the ‘Graham scan’ algorithm and the Separating Axis Theorem are used to avoid glyph collision. Using a MVC design, THNoteViewer employs these approaches to display CPWN musical glyphs natively within SuperCollider in a manner that is both dynamic and responsive, whilst obeying complex engraving rules overlooked in some other related software environments.

## An Exploratory Analysis of SCTweets Classification and Similarity

[Fellipe M. Martins](/bios/#fellipe-m.-martins)  
5pm

In the field of electroacoustic music, few artists and composers have published detailed information about their processes, and an even smaller number have provided a comprehensive blueprint, code, or instruction set that allows for a facsimile reconstruction of their work. With the advent of digital audio and the rise of creators making music exclusively on personal computers, it has become possible to track numerous details of the composition process when the software files are available. The use of programming languages for music composition has opened up a unique avenue for analysis, enabling musicologists to evaluate more clearly the relationship between sound results, high-level extracted features, and the tools and techniques used in their creation. An exceptional case is the SCTweets — 140-character SuperCollider code snippets that typically comprise compact sound procedures or dense compositions, shared on the microblogging platform Twitter (now X). We discuss the initial results of a timbral exploratory analysis on a specific set of SCTweets: tweets shared by Fredrik Olofsson on the repository sccode.org. Using the FluCoMa toolkit, we evaluate how timbral similarity might correlate with auditory criteria proposed by Pierre Schaeffer's theory. Additionally, we reveal various challenges and insights when correlating the usage of UGens and the provided timbral map. We selected Olofsson's SCTweets due to their unique use of the SuperCollider language, which often features codes utilizing only one number (666, 42, 1, 7), one type of UGen (SinOsc, Saw, LFCub), and codes that deliberately push DSP procedures to their limits to create new sounds, while adhering to the restriction of using only vanilla SC. We conclude the text with a discussion about the novelty of this analytical technique, presenting our findings and potential pitfalls.

