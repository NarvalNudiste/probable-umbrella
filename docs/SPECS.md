## Bachelor project

# Nouveau Musée de Bienne collaboration :  ArcheoGame

### Specifications

---

| Project number |                                             2xx |
|----------------|------------------------------------------------:|
| Client         | Nouveau Musée de Bienne (NMB), Ludivine Marquis |
| Expert         |                                 Mathieu Hopmann |
| Coordinator    |                                 Stéphane Gobron |
| Supervisor     |                               Magdalena Punceva |
| Student        |                               Guillaume Noguera |

---

## Context

Bienne's Nouveau Musée (NMB) was born from the merger of Musée Schwab and Musée Neuhaus in 2012.
Focused towards archeology, history and art, the museum regularly holds temporary exhibitions. One of those exhibitions, which will take place in June 2018, will features many works on the theme “Imagine the past” among which we would like to introduce a work of painter Benoît Clarys which will be themed around perception.
The NMB, with the partnership of the Haute-Ecole Arc, University of applied science and art of western Switzerland (HE-Arc, HES-SO) that provides the development of a virtual reality (VR) platform, will proposes a stand aimed towards young visitors to explore VR potential in exhibitions.
Within this VR experience, end users will be able to explore, discover and interact with archaeological objects through four types of paradigms :

* The real world
* The painting as a real object
* The virtual environment representing the real world
* The representation of the painting as a virtual object

---

## Goal

Develop an educational serious game (SG) in VR.

As the exhibition features original work from an invited painter representing an archaeological life scene, visitors will be able to interact with a virtual representation of objects from this era which would be way too fragile to manipulate in real life and replace them in a painting.

The intent is to suggest potential instruction to players on said objects with an entertaining experience. End users evolves in a virtual replica of BNM specific area environment in which they are presented with a table on top of which five distinct ancient objects are laying. In front of them is a large painting picturing the use of said objects in a real life scenario.

The objective of the SG is to match each object by replacing them in the correct area of the picture. By doing so, objects will "fade" into the picture, revealing the original work of art. Objects will be paired with a short audio anecdote provided by the Museum.


---

## Environment

The Unity game engine will be used, along scripts written in C#. The VR device will be an HTC Vive. 3D models (Room, small props) will be created in Maxon Cinema 4D. As of sound, possible editing will be done in Ableton Live.

---

## Objectives

### Primary (4.5 points)

* State of the art
* If needed, customization of input high resolution objects meshes from 3D artist
* Low resolution realistic objects as well as respective picture representations input
* 3D model of the room (realistic render type, best effort)
* Objects interactions:
	* Grabbing the object
	* Throwing the object on the painting (Matching mechanic)
* Audio:
	* Audio anectodes
	* Game FX
* Reset mechanic
* Game mechanics
* Scoring and respective user interface
* Tuning of game parameters
* Indoor testing and setup


### Seconday (1.5 points)

* Advanced game mechanics
* Advanced scoring and user interface
* Advanced sound and music FX
* Object breaking / Respawning
