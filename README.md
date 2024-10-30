# belly-button-challenge

**Project Overview**

This project is about creating an interactive dashboard to explore the Belly Button Biodiversity dataset, which lists the different microbes living in human belly buttons. It lets users see how diverse these tiny organisms are, and provides a fun way to visualize which microbes are common and which ones are rare for each individual sample.

**Features**
* Bar Chart: Displays the top 10 OTUs (Operational Taxonomic Units) for a selected individual.
* Bubble Chart: Visualizes all bacterial cultures present, with markers sized and colored by sample data.
* Demographic Panel: Shows metadata for selected samples (e.g., age, ethnicity, location).
* Dynamic Dashboard: Charts and metadata update based on the selected individual.
  
**Files**

* index.html: HTML structure and layout of the dashboard interface.
* app.js: JavaScript code for data retrieval, chart rendering, and interactivity.
* samples.json: Contains microbial and metadata information.

**Setup Instructions**

**1.** Clone Repository: Create and clone a repository named 'belly-button-challenge' on GitHub.

**2.** Copy Starter Code: Copy the provided files (index.html, samples.json, app.js) to your local project folder.

**3.** Push Changes to Github: As changes and updates are made, use the project repo folder to open the terminal and push changes to the main branch on Github.

**Functionality**

  **Bar Chart**
  * Displays the top 10 OTUs for the selected individual.
  * Uses sample_values for bar lengths, otu_ids for labels, and otu_labels as hover text.
    
  **Bubble Chart**
  * Shows all microbial species found in a sample.
  * Uses otu_ids for the x-axis, sample_values for the y-axis and marker sizes, and otu_labels for hover text.
    
  **Metadata Panel**
  * Displays demographic information for the selected sample using key-value pairs.
    
  **Dropdown Menu**
  * Allows users to select a sample ID, dynamically updating the charts and metadata panel.
    
**How to Use**

**1.** Open the 'index.html' file in Google Chrome browser.

**2.** Select a sample ID from the dropdown to view corresponding data.

**3.** Explore the charts and demographic information that update based on the selection.



**References**

*ChatGPT was used for README outline and format, and troubleshooting errors for this project assignment.*

* OpenAI. (October, 2024). ChatGPT (GPT-4) [Large language model]. https://chat.openai.com/

*Xpert Learning Assistant was used for troubleshooting errors for this project assignment.*

* Xpert Learning Assistant. (2024). Retrieved from https://bootcampspot.instructure.com/



