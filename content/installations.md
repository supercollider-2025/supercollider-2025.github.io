
+++
date = '2025-01-24T21:30:10-05:00'
draft = false
title = 'Installations'
+++


---


## *Only footprints*

**by [Drew Farrar](/bios/#drew-farrar)**

**Friday, March 14, 2025**  
**Location TBA**

_Only footprints_ is an interactive multi-media installation that utilizes SuperCollider, Arduino, and the Godot game engine. The piece explores concepts of the human influence on the environment, distortion, and decay. The work consists of an interactive video, stereo to 8 channel sound, and a chair with an embedded Arduino. When the seat is empty the audio consists of recordings of extinct birds and the video a rendering of a forest, creating a facsimile of a nature scene. When an audience member sits in the chair a process of spectral stretching and distortion begins, deforming the audio, while a custom written shader stretches the geometry of the video in real time. This work relates to both interactive music systems and multimedia music systems, and (aspirationally) hopes of future work either embedding sclang and scsynth into the Godot engine directly (for XR installation) or embedding scsynth/supernova and using Godot's native scripting language to interact with the server (alternative language clients for scsynth). To create this work I wrote an OSC library for Godot's scripting language (GDScript).

---


## *Return to Tomorrow*

**by [Michael Webster](/bios/#michael-webster)**

**Friday, March 14, 2025**  
**Location TBA**

_Return to Tomorrow_ is an opera from the Star Trek episode of the same name, using AI voices, written in Supercollider.  The episode concerns a voice without a body, emanating from a dead planet, ultimately opening up ideas  about the human/machine interface, and the nature of consciousness and connection. The show is here performed by the computer - the code being interpreted can be seen behind and through meme-like stills from the show. It’s a recreation of a piece from the past about a warning from the future... presented, hopefully, with humor and pathos.

In order to organize the music around speech-like rhythms, I built a kind of DAW that indexes all events not to beats/bars or minutes/seconds but instead to lines of text/syllables, allowing me to reflow all music (including the singing) by tapping out rhythms on my laptop, so the whole show retains a kind of parlando vibe and running time is very close to the original TV episode. Tools were written to build project files for the voice synth and interface with ffmpeg and Kitty to generate visuals.

---


## *Gamang*

**by [Sarah Lecompte-Bergeron](/bios/#sarah-lecompte-bergeron)**

**Saturday, March 15, 2025**  
**Location TBA**

_Gamang_ is an interactive installation inspired by the feeling of being separated from friends and loved ones. « Gamang » is a type of ghost in Balinese folklore that can be encountered at night in isolated spaces.

The haunting spirit recalls the absence of people who were once close that we continue to feel as a presence. This installation was motivated by the desire to recreate the feeling of playing with peers in a gambang ensemble, a type of Indonesian gamelan.

The musical motifs are algorithmically generated from transcriptions of unique performances. An automatic music transcription algorithm was developped to ease the process. The public is invited to engage with digital ghost musicians by playing a « gangsa » (gamelan metallophone) to guide the patterns and be part of the virtual ensemble. The ghosts react to the human player sitting within them using a computer vision algorithm designed to follow anticipated actions, akin to an improvised human performance of gambang. The patterns are generated as the player improvises on the instrument.

A SuperCollider class was written to better suit balinese gamelan musical thinking while serving sound experimentation. Musical concepts unique to gamelan are embedded in the synthesis system and the interface.

The ghosts materialise themselves as flickering firefly silhouettes floating on layered mesh, giving them dimension. By walking between the sound sources, different complementing parts of the Kotekan, a type of interlocking pattern idiomatic to gamelan music, are highlighted. When at rest, the sound essence of the ghosts roam the cemetary in a quadraphonic arrangement. This nocturnal atmosphere develops itself generatively within a field recording of a full night in a cemetary in the mountains of the village of Munduk.
