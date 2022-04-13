# Data Collection - KoBoToolbox applications

## Creating a basic form with KoBoToolbox
1. Log in to the KoBoToolbox website with user credentials.
2. From the main page, choose "NEW" and choose one of the options - I will be testing both creating via importing an XLS and creating from scratch.

### Import from XLSForm option:
3. Choose "Upload an XLSForm" and select the file to upload: my file was titled MaintenanceFromTemplate.xlsx (... typing *from* and *form* for this section of Web Dev and Collab has been very hard, like really).
4. The title comes up with odd formatting so this will need to be changed before deploying. Add an appropriate description, sector and country. Click "CREATE PROJECT".
5. This will bring up the form version page: from here, click the eye icon ("Preview" on hover) to view what the form has displayed as. The formatting for the text in many of the slots has additional formatting that will need to be removed before deploying. Close the preview window.
6. Click the ellipses icon ("More actions" on hover) then "Clone this project" - I changed the title in the window this action brought up, with this form being edited to show the difference between the original import and what had to be changed to have a readable, useable form.
7. In the form version page, click the pencil icon ("Edit in Form Builder" on hover).
8. The first four sections are not necessary as these are only to say that the survey was cxreated in Survey123. In each of the remaining questions, remove the additional HTML for clarity. Once this is completed, click the eye icon to preview the updated form. I'm satisfied with the results, so I closed the preview. Click "SAVE*" (the star means that there are new unsaved changes), and then close the survey once saving is complete.
9. On the form page, deploy the form. JUST KIDDING! There's an error!!
![alt text](https://github.com/carolbuckingham/developmentlogs/blob/main/images/07%20unable%20to%20deploy.png?raw=true)

10. Going back into the original file (MaintenanceFromTemplate.xlsx), there are several fields with 'esri' in the name - I deleted all these fields and will attempt to reupload the XLSForm.
11. Choose "Upload an XLSForm" and select the file to upload: my file was titled MaintenanceFormTemplate.xlsx (changed it for the new file). Again the title and form come up with odd formatting.
12. Repeat steps 7 and 8 for the new form. On the form page, deploy the form... FORM SUCCESSFULLY DEPLOYED!
13. The picture question did not properly translate, but all other questions did. To have the same functionality of having 3 photos able to be submitted, add 2 additional questions with conditions for the previous photos to have been submitted.

***After making all edits, click Save on the upper right portion of the site and close the Form Builder. Then click Redeploy to be able to access the form for testing. Click OK to overwrite the pervious version.***

### Blank survey option: (after completing steps 1 and 2 from above)
3. Choose "Build from scratch". Give the project an appropriate title, description, sector, and country.
4. Using the questions chosen for the Survey123 form (https://github.com/carolbuckingham/developmentlogs/blob/main/Week13Task1.md), format the questions using the KoBoToolbox options. See the full methodology below.

#### QUESTION FORMATTING
For each of the requirements below, click the plus sign icon to add a new question:
1. Observation date and time: Provide the name for question and select ADD QUESTION. Select "Date and time". Go into Settings (gear icon). Select 'yes' for Mandatory Response to have each observation associated with an observation time, and set the default response to "now()" to have it autopopulate.
2. Location: Provide the name for question and select ADD QUESTION. Select "Point". Add appropriate question hint.
3. Kilometer marker: Provide the name for question and select ADD QUESTION. Select "Text". Add appropriate question hint.
4. Photos/file upload: Provide the name for question and select ADD QUESTION. Select "Photo". Add appropriate question hint.
5. I've stuck with the 3 photo maximum for the purposes of this demo. For the 2 additional photo uploads (see step 13 of XLSForm template): Provide a name for each and select ADD QUESTION. Select "Photo". Add appropriate question hint. 
- FOR 2ND PHOTO: In the Settings panel, select the 'Skip Logic' tab and add a condition. Select 'Photo' and 'was answered' will autopopulate.
- FOR 3RD PHOTO: In the Settings panel, select the 'Skip Logic' tab and add a condition. Select 'Photo' and 'was answered' will autopopulate. Add another condition: select '2nd Photo' and 'was answered' will autopopulate. Make sure that 'Question should match all of these criteria' is selected.
6. Type of POI: Provide the name for question and select ADD QUESTION. Select "Select one". Add appropriate question hint. Fill in all 13 options (including Other). Go into Settings (gear icon) and set Mandatory Response to 'yes'.
7. Other DEPENDANT QUESTION: Provide a name for the question and select ADD QUESTION. Select "Text". Reference having answered Other in the previous question about POI type. In the Settings panel, select the 'Skip Logic' tab and add a condition. Select 'What type of point of interest is this?' = 'Other'.
8. Description: Provide the name for question and select ADD QUESTION. Select "Text". Add appropriate question hint.
9. Plant type RULE QUESTION: Provide the name for question and select ADD QUESTION. Select "Text". Add appropriate question hint. In the Settings panel on 'Question Options', change the Appearance to "multiline". Select the 'Skip Logic' tab and add a condition. Select 'What type of point of interest is this?' = 'Interesting or unique plant species'.
10. Other comments: Provide the name for question and select ADD QUESTION. Select "Text". Add appropriate question hint. In the Settings panel on 'Question Options', change the Appearance to "multiline".

***After making all edits, click Save on the upper right portion of the site and close the Form Builder. Then click Deploy to be able to access the form for testing.***

## Embedding a KoBoToolbox form into a website
1. In the Form tab of the deployed form under 'Collect data', change the dropdown to "Embeddable web form code" and a code snippet will appear. Use this directly in your site to reference the form.
