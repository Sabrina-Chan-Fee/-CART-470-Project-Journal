# Week 3 POC
## Meeting with Gabriel
We met with Gabriel on Zoom on Friday, September 25th, to ask some more question regarding the project. Following the meeting, we had a much clearer understanding of the project's vision and it's requirements .

- How will we receive the audio files (if they will be audio files)
- Are they uploading them directly to our web app? or will they fork + host (general clarity)
- How long will the audio files be (approx)
- Conflict between hosting on compute canada, vs having the flexibility to fork, modify ui, upload files, ect while hosting locally
- Do we need to make different QR codes per room? Just generate links for each room?
- Relationship between number of channels and number of speakers

For our proof of concept, we need to create a server that we will temporarily host on Render and be able to play sound on all the devices connected to the server. This demo will be shown to Gabriel during our next meeting on September 30th.

## System Architecture
<figure>
<img width="2386" height="1491" alt="image" src="https://github.com/user-attachments/assets/f6c21e43-e485-4d67-a43d-62d024de5554" />
  <figcaption><em>Schema by Jess</em></figcaption>
</figure>


- The students will provide a score, which take form of a JSON file that contains the information of how their piece should be played.
- The JSON should provide the number of groups to divide the phones into
- The JSON file should provide the information on the order which the audio file will be played and in which group they should be playing from
- The maestro interface (UI) will tell the server when to start the piece (e.g. on a button click)
- the maestro UI should indicate how many phone are connected to the server
- The server will ping the connected clients to start playing the audio files.
- The clients will play the audio files based on the information provided in the JSON file.
- It will look at the queues from each group and play in the order of the queue.

## Next step
- Demo the POC
- Design more wireframes for the Meastro UI
- Update the Kanban with tickets
- reorganize some roles according to the updated project requirments
