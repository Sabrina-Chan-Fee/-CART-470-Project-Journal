# Week 6
We had our weekly meeting with Gabriel. So far, the team managed to have the audio files play on different phone grouping according to the JSON fiel instructions. We will be having our meeting with Gabriel in person on the 28th.

## Figma
I reviewed the figma file and answered questions from Jess and Leah and provided guidance and question to Leah on design systems. For now, I have taken a back seat in the designs and will be focusing on implementing the JSON form.

## Implementing CSS to the JSON Score form
After the UI has been fully designed. I implemented the design using CSS for the JSON form. I also edited the field input to be sliders so that users can visually see the range limits for the field, therefor improving the usability and reducing confusion. Here are some before and after images of the UI after some css have been implemented.
<img width="2344" height="900" alt="image" src="https://github.com/user-attachments/assets/e318c7b8-442f-4d8b-83a3-839abb595c3a" />
<img width="2726" height="1316" alt="image" src="https://github.com/user-attachments/assets/fe502ad1-45fe-4b82-a15c-49cf2075c4ee" />
<img width="1436" height="938" alt="image" src="https://github.com/user-attachments/assets/c0bda064-f8d8-473d-8a42-986f050f3eb3" />

## New JSON form format
In addition, we changed the way the JSON and audio will be delivered by the user. Now we will have the users deliver a "Package" that will contain the json generated and the audio files they will have uploaded on the JOSN form. Therefor, some field in the JSON form that involved getting the audio file names will have to be removed. These changes are in hopes to make the user experience and process more streamlined. Its also helps reduce errors since audio files and the JSON files are packaged together properly. We can then rename the folders so that our application can read the files properly. Jess wrote down a schema for better understanding.
<img width="2508" height="2160" alt="image" src="https://github.com/user-attachments/assets/7631f5c0-1589-45ea-9f49-eb5ad7639645" />

## Task List
For next week as a soft deadline we made some high priority task to have done for testing with gabriel

Victoria:
- Be able to upload the sound in the JSON  form so that when JSON is generated you get a package ( which includes all sound files and json).
upload download package

Sabrina:
- Implement CSS for json html based on Figma design
- Slider for json
- Remove one of the Audio file name input fields since we no longer need the file path.
- Phone pages. Add an interaction button and group name. Don’t move the play and pause

Jess:
- Landing page
- Conductor global view + QR code
- Conductor smaller view
- change phone logic to be bale to kick people out (websocket disconnect)

Leah:
- Implement Html page for Guide ( user flow explained in details) 
- Finish all the designs

Eamon:
- Restructure folder to accommodate packages ( look at picture jess uploaded)
- sample sound in the form ( low priority/optional)







