# AMPLIFY - Phygital Solutions for the Cultural and Creative Industries

AMPLIFY is a groundbreaking initiative uniting artists, technologists, and
researchers from 8 European countries to drive the digital transformation of
the Cultural and Creative Industries. By merging physical and digital
(phygital) experiences and fostering collaboration, AMPLIFY is creating
innovative ways to connect creators and audiences!

For more information about the project, its aims, pilots and technologies,
check our [website](https://amplify-porject.eu)!

## Our Vision

We envision a future where the European cultural and creative industry fully
embraces a sustainable, inclusive digital transition. By leveraging emerging
technologies such as Artificial Intelligence and Extended Reality, AMPLIFY aims
to influence the cultural sector with new artistic formats, fostering human
connections and promoting European values.

## Our Values

We believe that technology should serve creativity, culture, and community, not
control it. As AI and immersive tools reshape our world, we stand for a digital
future that is ethical, inclusive, and human-centred.

## Our Tools

To this end, we develop open-source tools that leverage technology to support
artists and empower communities in their creative pursuits. The two primary
tools forming the output of the project are **AMPLIFY CREATIVE** and
**AMPLIFY IMMERSIVE**. The following sections outline the tools and point you
to the repositories for each pilot, in which the development effort takes place.

### AMPLIFY CREATIVE

AMPLIFY CREATIVE is a user-friendly digital tool designed to unite people
across distances for learning, performing, and creating together. Ideal for
community settings, it combines AI-driven audio-visual production with phygital
engagement, making collaborative experiences seamless and accessible.

- AI-Powered Collaboration: Automatically mixes audio and video for professional-quality outputs.
- Multi-Modal Sensing: Captures emotional cues, like movement or expression, to adapt live performances.
- Flexible Connectivity: Seamlessly integrates multiple devices in different settings.

AMPLIFY CREATIVE is about more than just a tool – its goal is to foster
inclusion, creativity and learning across the Cultural and Creative Industries.

#### AMPLIFY CREATIVE Studio - Scotland: Connecting Remote Musicians

Focused on traditional Gaelic music, AMPLIFY CREATIVE will provide an
easy-to-use, low-cost digital tool to enable professional and non- professional
musicians, young people in particular, to learn, rehearse and perform together
from different locations. It will provide new possibilities for collaboration
through functionalities such as recording and reviewing, so participants are
able to listen back, discuss and improve. The tool enhances teaching quality
with features like AI audio mixing and low-latency communication.

- [Creative Studio](https://github.com/amplify-project/Creative-Studio) Open-source video conferencing web studio for synchronous remote music creation and learning.

#### AMPLIFY CREATIVE Playground - Portugal: Babies at the Creative Center

In this pilot, AMPLIFY CREATIVE will be used to turn babies into co-creators of
musical experiences. The tool will offer multi-sensorial musical experiences to
babies and families in physical and remote presence. AMPLIFY CREATIVE will
collect data about the baby’s reactions (motor, sound, expression, possibly
physiological) and then collate and translate it into hints that musicians can
read in real time. Alongside this AMPLIFY will capture general images and
sounds in the concert hall, so that people who are present remotely can see
(and hear) a particular baby, and only their baby, mixed with media from the
concert environment.

- [XR Score Viewer](https://github.com/amplify-project/ampPortable_xrGlassesDemo) A Unity project for real-time display of audience data in XR glasses. Data visualisations act as abstract graphical scores and also as a way to provide information on audience engagement levels.
- [Physiological Signal Models](https://github.com/amplify-project/Physiological-Signals) Models for processing physiological signals, audience poses and performing audio analysis
- [Light Instruments](https://github.com/amplify-project/light-instruments) ESP32 code powering the AMPLIFY Light Instruments
- [Light Instrument Schematics](https://github.com/amplify-project/light-instrument-schematics) Schematics for the PCBs powering the Light Instruments
- [Light Instrument Editor](https://github.com/amplify-project/light-instrument-node-editor) Editor, providing a node-based workflow for designing lighting setups for AMPLIFY Light Instruments
- [Light Instrument Config](https://github.com/amplify-project/light-instrument-config) Desktop application for configuring AMPLIFY Light Instruments and LED Controllers through USB
- [Interface Library](https://github.com/amplify-project/interface-library-spec) High level specification for AMPLIFY Creative interface libraries. For specific implementations of the specification, check the [Python](https://github.com/amplify-project/interface-library-python) and the [Unity](https://github.com/amplify-project/interface-library-unity)

### AMPLIFY IMMERSIVE

AMPLIFY IMMERSIVE leverages cutting-edge Extended Reality technologies to
create breathtaking live performance experiences. The tool will allow for the
visual extension of  a real stage equipped with sound and light infrastructure
and to create a stage anywhere, such as a cultural space or a town square, with
only a smartphone and headphones. These immersive formats will rely on
volumetric and 3D video, spatial audio and technologies to foster the
engagement and phygital social interaction of artists and audiences.

- XR Integration: Delivers lifelike 3D visuals and spatial sound for fully immersive experiences.
- Remote Interaction: Enables real-time audience engagement, from virtual applause to live Q&A.
- Adaptability: Can transform any location - be it a town square or festival stage - into a performance space.

AMPLIFY IMMERSIVE isn’t just about technology; it’s about reimagining human
connection through art and culture, even across distances.

#### AMPLIFY IMMERSIVE Stage - Italy: Immersive Concerts

This pilot transforms traditional concert experiences by allowing audiences to
enjoy live performances through augmented reality. The pilot will test an
“immersive stage”, created with AMPLIFY IMMERSIVE, which the festival audience
can approach with XR headsets. They will surround an “empty” stage while they
see their musicians playing live remotely placed digitally in that stage, while
listening to the audio through a state-of-the-art PA sound system. But AMPLIFY
IMMERSIVE goes beyond this, aiming to connect artists with audiences in a
real-time connection to create a feeling of unity and shared presence despite
the physical distance. Attendees could engage with the band in various ways,
such as sending a virtual applause, reactions, or messages, allowing for a
dynamic and responsive performance that adapts to the mood and energy of the
viewers.

- [Immersive Stage WebXR](https://github.com/amplify-project/Immersive-Stage-WebXR) End-to-end platform for live and on-demand immersive concerts: capture, encoding, DASH/S3 delivery, a browser scene editor, and a WebXR player (VR/AR, Meta Quest) with 360° video, binaural Ambisonics and per-musician audio zoom.
- [Immersive Stage Unity](https://github.com/amplify-project/Immersive-Stage-Unity) Experimental Unity-based prototype for exploring immersive concert experiences on Meta Quest 3 and Android tablets. The prototype supports on-demand 360° concert video, spatial/binaural Ambisonics audio, per-musician audio stems and audio zoom, with interactions for selecting musicians and changing perspectives.

#### AMPLIFY IMMERSIVE Space - Barcelona: Co-Creating Immersive Opera

Bringing opera to the streets of Barcelona’s Sant Andreu neighborhood, this
pilot connects professional and amateur artists through digital tools.
Participants use mobile devices to explore opera creation in real time,
experiencing 3D models, live arias, and interactive performances in community
spaces.

AMPLIFY aims to create an immersive stage without conventional infrastructure
such as a sound system, lightning, or even the stage itself. People will meet
in a square, a cultural space or even in multiple places at the same time, and
using their mobile phones and headphones, they will experience a performance or
presentation from the co-creation process.

- [Immersive Opera Experience](https://github.com/amplify-project/VRTApp-Prison) Immersive virtual reality experience co-created with residents of Barcelona's Sant Andreu neighourhood, telling the story and preserving the memories of female political prisoners
