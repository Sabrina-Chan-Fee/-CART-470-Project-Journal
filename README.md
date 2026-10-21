# -Week 5
## Design system
I worked on building a design system in Figma so we can have a consistent UI. I started a base for the variable padding number/radius size, font size, color, input and label components, and a base for the button components. The buttons needed some UI refined that was send to Leah. I did some reach on how to create dynamic components using the following tutorial (https://youtu.be/Do-w990lv4s?si=PGC5MZ4th0IrS3nb). Some colors and effects were missing and waiting for other people's input. We needed a list of components that need to be made.

Components needed
- card components
- slider/seek/ player bar
- input field
- dropdown
- Labels

<img width="1610" height="1136" alt="image" src="https://github.com/user-attachments/assets/febf477a-a8cf-444c-8eb1-ac645ad96ca1" />

## Json Form
I also continued to work on the JSON form. I was able to complete 80% of the functionality and merged to main. The only thing missing is improving the UI with some CSS and grabbing the audio file names from the folders. Another function missing is getting the sounds file name form the github repo. After doing some research, it seems some form of Github API will be needed.

<img width="2852" height="1444" alt="image" src="https://github.com/user-attachments/assets/19e924e9-f4c0-429b-9cc8-9f6bc7658cb1" />


REST API documentation: https://docs.github.com/en/rest/repos/contents?apiVersion=2026-03-10
```
//code example found for getting the file names
//html
<label for="fileSelect">Choose a file:</label>
<select id="fileSelect">
  <option value="">-- Select a file --</option>
</select>

//js
const owner = 'YOUR_GITHUB_USERNAME';
const repo = 'YOUR_REPO_NAME';
const path = ''; // leave empty for root, or specify folder path like 'docs'
const url = `https://github.com{owner}/${repo}/contents/${path}`;

async function loadRepoFiles() {
  try {
    const response = await fetch(url);
    const data = await response.json();
    const selectElement = document.getElementById('fileSelect');

    data.forEach(item => {
      if (item.type === 'file') {
        const option = document.createElement('option');
        option.value = item.name;
        option.textContent = item.name;
        selectElement.appendChild(option);
      }
    });
  } catch (error) {
    console.error('Error fetching files:', error);
  }
}

loadRepoFiles();

```
