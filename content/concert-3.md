
+++
date = '2025-01-24T21:30:10-05:00'
draft = false
title = 'Concert 3'
+++

Friday, March 14, 2025  
1pm  
TBD


**Improvisation using *Lossy Codecs*** directed by Derek Worthington  
&emsp;&emsp;*James Annett, viola*  
&emsp;&emsp;*Dustin Donahue, percussion*  
&emsp;&emsp;*Kerrith Livengood, flute*  
&emsp;&emsp;*Maxwell Miller, guitar*  
&emsp;&emsp;*Mason Moy, tuba*  
&emsp;&emsp;*Hyunkyung Shin, contrabass*  



***2CUBES*** by Hyunkyung Shin and Henrik von Coler  
&emsp;&emsp;*Hyunkyung Shin, Contrabass & ARCube*  
&emsp;&emsp;*Henrik von Coler, Modular Synthesizer & ARCube*  



***Copper Ouroboros*** by Mason Moy  
&emsp;&emsp;*Mason Moy, tuba*  



***Antithesis (this is the part where I scream)*** by Maxwell Miller  
&emsp;&emsp;*Maxwell Miller, guitar & voice*  



***Notoligotoma hardyi*** by Bruno Ruviaro  
&emsp;&emsp;*Dustin Donahue, percussion*  

---

## Program Notes

### *Lossy Codecs*

by [Derek Worthington](/bios/#derek-worthington)

Lossy Codecs is a system for directed improvisation that utilizes a dynamic graphic score created in real time, using a program built in SuperCollider. The program allows the director to control the changing values of various musical parameters, using TVs or a projector to display their screen to the performers. The performers improvise material based on their interpretation of this information, leading to unique sonic ecologies for each performance. The goal of this system is to merge methods and aesthetics from electronic music creation with live ensemble performance. One idea that inspired its creation was to be able to ‘play’ an ensemble as if it were a stochastic electronic instrument, controlling high-level parameters to shape the texture and form, while the details are supplied by live musicians instead of a program. But this idea must be balanced by a consideration of the improvising musicians’ freedom, creating an interesting tension and feedback process, where the director can react to the musicians as much as the other way around.

The system begins by defining a set of 17 musical parameters. Some are straightforward (Volume, Lyricism), while others are more abstract or ambiguous (Chunkiness, Thematicness). The values of the parameters are communicated by the height of colored bars, allowing the performers an intuitive approach to parsing the information. The director has control of what parameters are given at any time, and can set their values directly, assign goal values and transition times, or map them to independent LFOs, allowing complex and multidimensional textural progression.

### *2CUBES*

by:  
[Hyunkyung Shin](/bios/#hyunkyung-shin)  
[Henrik von Coler](/bios/#henrik-von-coler)  


CuboiDuo is an electronic duo performance utilizing two ARCube(s), an augmented reality (AR) interface designed for three-dimensional spatial control. The ARCube enhances engagement and immersion by being placed alongside physical control devices. Shaped as a cube with four 3-centimeter-diameter spheres, the ARCube enables spatial manipulation through AR. The virtual scene is generated using Unity Engine, and the cube serves as a scaled model representing the physical dimensions of the spatial audio system.

Two hand gestures, Grab and Pinch, enable intuitive interaction with the cube: the Grab gesture allows performers to move and rotate the cube, while the Pinch gesture controls the movement of the spherical objects within it. The cube’s Y-axis rotation is constrained to maintain stability during performance, and it can be conveniently placed next to the performers.

For virtual source positioning, OSC messages are transmitted at 100 Hz over WiFi to a Linux-based rendering server running SuperCollider-based spatialization software. Each performer’s instrument—double bass and modular synth—connects to four sound synthesis processes on the same server. Through the ARCube interface, performers can manipulate the individual sound characteristics of each process via gesture control.

The audio streams are routed to four Higher Order Ambisonics (HOA) encoders, generating four virtual sound sources that are decoded and projected through a quadraphonic loudspeaker setup. The real-time inputs from the double bass and modular synth undergo spatialization and sound transformation in real time, producing experimental electronic music.

The performance emphasizes avant-garde improvisation, blending the extended techniques of the double bass with the rhythmic, electronic sounds of the modular synth. This interplay creates an experimental stage where acoustic sounds are electronically transformed and layered with modular synth’s dynamic textures, resulting in a uniquely immersive electronic music experience.

### *Copper Ouroboros*

by [Mason Moy](/bios/#mason-moy)

Program Note Needed

### *Antithesis (this is the part where I scream)*

by [Maxwell Miller](/bios/#maxwell-miller)

Antithesis (this is the part where I scream) is the embodiment of the frustration I sometimes feel dealing with a split sense of self. It explores feelings of inevitability and anger, with me grappling with the electronic sounds and fighting to retain voice as a performer amidst a thick and sometimes overwhelming texture. This piece is quite open in its structure, asking the performer to create gestures of increasing intensity until it reaches its point of climax, a full scream, until releasing that energy back into silence. This piece forgoes the use of video and is performed in near-darkness, symbolic of the internal experience it portrays.

### *Notoligotoma hardyi*

by [Bruno Ruviaro](/bios/#bruno-ruviaro)

Notoligotoma hardyi is a piece for solo percussion and live-electronics composed by Bruno Ruviaro (composer) in collaboration with Janice Edgerly-Rooks (biologist) and Dustin Donahue (percussionist). The combination of music and biology might seem surprising at first, but when one considers the type of data Edgerly-Rooks collects, bringing these fields together makes sense. Since 2005, Janice and her students have been quantifying silk spinning behavior of a few dozen species of insects called Embioptera. They spin silk by stepping with their front feet, packed with silk glands, around their bodies as they secrete silk to build a domicile where they gain protection against the elements. Individuals display thousands of spin-steps to complete construction. While analyzing long data sets, she noticed that sometimes the data reminded her of musical patterns. Ruviaro looked at the data and wondered what it would sound like if spin-steps were recreated for percussion instruments. He analyzed and transcribed over 5000 spinning steps of an Australian species, Notoligotoma hardyi—hence the composition’s name. The data were then made audible through sonification techniques (sonification is the use of non-speech audio to perceptualize data). Individual steps were assigned to percussion instruments and a score was created representing the data. Performer Dustin Donahue helped not only in the process of carefully choosing instruments, but also brought his own rhythmic imagination to the otherwise rhythm-less data. In addition to using acoustic instruments, Ruviaro added live-electronic sounds to represent the growing silk structures that result from the insect’s choreography. The piece was created using SuperCollider on Ubuntu Linux.

