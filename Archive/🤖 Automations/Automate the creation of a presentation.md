
# Help from Chat GPT
#### Step 1: Extract Information for Each Placeholder

1. **Identify Key Sections and Placeholders:** Define the exact sections in each case study that correspond to placeholders in the Google Slides template.
2. **Use ChatGPT to Structure Data:** Run a structured extraction on the case study text. Given token limits, break the text into smaller, logically grouped sections (e.g., project overview, role, insights).
3. **Output Data as Key-Value Pairs:** For each placeholder, assign a corresponding value (e.g., `"project_duration": "March 2022 - June 2022"`).

#### Step 2: Populate an Excel/Google Sheets Template

1. **Create Columns for Each Placeholder**: In your Excel or Google Sheets file, create columns with headers named after each placeholder (e.g., `project_title`, `role`, `goal`, etc.).
2. **Paste Structured Data into Spreadsheet**: Populate the spreadsheet by pasting each extracted section into the corresponding columns for each case study row.

#### Step 3: Use Make.com for Automated Population in Google Slides

1. **Setup a Make Scenario**: Use Make’s Google Sheets and Google Slides modules.
2. **Map Each Column to Google Slides Placeholders**: In Make, configure your Google Sheets module to pull data from each row and map it directly to your Google Slides template’s placeholders.
3. **Automate for Multiple Case Studies**: The Make scenario can iterate over rows in the spreadsheet, creating a unique presentation for each case study.

So
1. List all the placeholders in my slide
2. Ask chat gpt to extract the content that corresponds to each placeholder. 
3. Place this content inside of other google sheets' cells
4. Use another automation to have this content copied from there to the slides. 

### All placeholders used

**I NEED TO MODIFY THIS TEMPLATE. IT DOES NOT ALIGN WITH THE TEMPLATE I CREATED. **

* {{case_study_title}}
* {{product_description}}
* {{target_users}}
* {{project_duration}}
* {{problem_statement}}
* {{project_goal}}
* {{role}}
* {{responsibilities}}




# Use-Case
* Having a content that you want to convert into a presentation
* Having a template for this presentation
* Needing that to be done for several files
* The powerpoint needs to be a bit complex e.g. columns, image on the left, on the right, columns
* You want to have the control on the presentation itself

# My use-case
* I want to convert my written case studies to a presentation, without it to be too repetitive. 
* The template has already been defined and is accessible in my google drive 
* Each Case Study has been written in Google Docs and is accessible in my drive

## Missing pieces
I need to convert each case study to the slides. 
In each slide, I will have placeholders where information is expected. 
I should extract from the written text the information that should go to each placeholder. 
I could do that using the chat gpt structured information module. 
However, I am a bit afraid of the limitation in terms of token of this Make module to structure data. Maube I should first split the case study by an actual chat gpt module. 

I need to have in mind that not everything in the template will be fillable. 

What is the best way to input the data?
* Excel row? 
* Survey?
* Uploading a document?

Let's start with an excel row. I will paste the content of my portfolio case study. 
