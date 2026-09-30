# CART470 – Distributed Listening

**Team:** Leah Song, Jessica Chan, Sabrina Chan Fee, Eamon Foley, Victoria Hoang

## Project Focus

In collaboration with Professor Gabriel Vigliensoni, we are building an open-source distributed listening system for his CART 346 Digital Sound class that uses mobile phones as speaker nodes for spatialized sound installations. Upon entering a room, participants scan a QR code to load a web app in their phone's browser, then place their phone on the ground or a table. Together, the phones act as a spatialized speaker system that can be set up in any room or layout without dedicated audio hardware.
The project is meant to be a skeleton, or base that others can build on. Students in Gabriel's CART 346 Digital Sound class will be able to fork our GitHub repository, add their own audio files, adjust the UI, and write a JSON score that dictates which sounds play on which phones and when.


## Thesis / Project Outcome

Our goal/thesis is to build a real-time, web-based system that distributes audio across a group of mobile phones in near synchronicity. As participants join by scanning a QR code, the system keeps track of each phone and assigns it to a speaker group based on the piece's JSON score. During playback, sound moves between these groups according to how the sound artist has programmed it, turning the room into a spatialized sound installation.
The intended outcome of the project is to create an adaptable, open-source tool for artists. By forking our repository and writing their own score, students/artists will be able to present distributed, spatial pieces. The final outcome will be a working demo hosted on Compute Canada, a public GitHub repository, a template score and documentation that make the system easy for others to work with and build on.


## Knowledge Base / Fields / Domains / Keywords

- Audiovisual installation
- Web hosting
- MaxAudio
- JavaScript
- Reactive UI/UX
- Distributed Audio

## Link to Team Kanban

[Team Kanban Board](https://app.fizzy.do/6280767/boards/03gvol14dsy6pof4ziyx2jgqt)

## Learning Objectives

1. Learn how to use WebSockets
2. Learn how to use the Web Audio API to load and play audio on phones
3. Learn how to keep audio in sync across many devices
4. Design a JSON score template that is simple enough for students to use
5. Host the server through Compute Canada
6. Write a clear, concise codebase with documentation so others can fork and use the project
7. Learn to work in a group and with client expectations

## Learning Activities

- Research on using the Web Audio API
- Understand how to host the server using Compute Canada for the project
- Create an example JSON template needed for the project
- Learn to make a reactive UI using JavaScript and JSON


## Milestones

### 1. Proof of Concept

Proof of concept: Have it work locally with a loaded music file, and have the server. When users connect to the page, all connected phones will play a default test sound. 

### 2. Audio Grouping

Have the project be able to play audio on different groups of phones according to JSON file instructions. Apply feedback from Gabriel.

### 3. Compute Canada Hosting

Be able to host the server using Compute Canada. UI dynamically reacts according to audio. 

### 4. Final Distributed System

Have a server on Compute Canada that can split audio files to multiple phones. The controller will create the number of grouped phones and play the audio

## Weekly Plan

| Week # | Topic | Detail | Work Due |
|---|---|---|---|
| **Sep 23** | Define project | Define scope, way of getting audio, and main function. | **Sep 30** |
| **Sep 30** | Set up server and questions for Gabriel + Create rough UI wireframe | Write questions to ask Gabriel in the Discord for the Friday meeting. | **Oct 7** |
| **Oct 7** | **Iteration #1** | Have it work locally with a music file and test. When users connect to the page, all connected phones will play a default test sound. | **Oct 14** |
| **Oct 14** | Gather feedback | Test out and gather feedback from Gabriel. | **Oct 21** |
| **Oct 21** | **Iteration #2** | Have the project play different audio files on different groups of phones according to JSON. Prototype and presentation due the following week. | **Oct 28** |
| **Oct 28** | Finalize dynamic UI and implement front-end | Design and implement the front end. | **Nov 4** |
| **Nov 4** | User testing and feedback | Improve the UI and gather feedback from stakeholders. | **Nov 11** |
| **Nov 11** | **Iteration #3** | Host the project on the Compute Canada server and have the UI dynamically react according to the audio. | **Nov 18** |
| **Nov 18** | QA testing | Test the project in different scenarios to find bugs and edge cases. | **Nov 25** |
| **Nov 25** | Gather feedback | Get feedback from Gabriel. | **Dec 1** |
| **Dec 1** | **Iteration #4** | **Finalize bugs and implement final feedback.** | **Dec 9** |
| **Dec 9** | Finalization | Finalize last-minute bugs and implement remaining details. | **Dec ?** |
