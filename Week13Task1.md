# Data Collection - Survey123 applications

## Creating a basic form with Survey123
1. Log in to the Survey123 website using Fleming College access.
2. From the main page, choose "+ New Survey" and choose one of the options - I will be testing both using a template and creating from scratch.

### Template options:
3. Click get started under Template survey.
4. I chose the "Report trail hazards and maintenance issues" template, since this will also give us a better idea in terms of designing our final project maintenance data collection form.
5. This template has 10 questions to be answered:
- Trail name
- observation date and time (which appears to autofill with the date and time the form is opened)
- mile marker (easily changable to km since we are in Canada)
- map for geolocation (with an option to choose your current location if on the trail!)
- photo of the maintenance/hazard (include up to 3 files)
- type of hazard/maintenance needed (dropdown options)
    - options include: trail washout, trail not well defined, trail flooded, downed tree, poisonous plants, animal observation, structure in need of maintenance, trash, and OTHER
    - if the hazard question is answered with Poisonous plant, a follow up question asks for plant type
    - if the hazard question is answered with animal observation, a follow up question asks for animal type
- a description box (with no character limit)
- choose a level of severity (4 options)
6. We wouldn't need the trail name question so I've removed it, and I've changed the MILE to KILOMETER via the Edit panel along the side: when a question is clicked it is easily editable in the right-hand panel.
7. For our website I will need to go into detail about the options available for each question, I need to set aside some time to write those out and perhaps think about the other question types that could be used. BUT we're not using Esri products so it would be better to more fully explore this in KoBoToolbox.
8. After making all edits, click Save on the lower right portion of the site. Then click Publish to be able to access the form for testing.

### Blank survey options: (after completing steps 1 and 2 from above)
3. Click get started under blank survey.
4. For this one I will be maing a basic point of interest form, since the trail maintenance was able to be done using a template.
5. Click on the survey title section within the form and give the survey an appropriate title and description. I changed the alignment on both items to be centered. Also give the form a name, tags, and summary for within your content library.
6. Here are the questions I will need to format:
- observation date/time
- location
- kilometer marker
- photos (landmarks if photos aren't able to be taken?)
- type of POI:
    - historic graves
    - Historic buildings and areas
    - Fire towers
    - Logging industry sundries (timber slide sections, rollways, etc.)
    - Thunderboxes (painted outhouses)
    - Artefact find points (rocks with carvings, boat remains, etc.)
    - Interesting or unique tree species
    - Lookouts and other trails
    - Trail signs
    - existing and potential campsites
- description (single line)
- other comments (multiline)

#### QUESTION FORMATTING
For each of the questions, start in the add tab:
1. Observation date and time: Select "Date and time". In the edit tab, give it an appropriate label and hint/description. Change the default value to 'submitting date and time' so that it does not need to be filled out by the user. Check 'this is a required question' in order to have each observation associated with an observation time.
2. Location: Select "Map". In the edit tab, give it an appropriate label and hint/description. Ensure that the drawing tool is set to point. Next to map and extent, choose Expand to explore the options for basemap: I chose Imagery Hybrid because I like the satellite imagery look. For default location, select 'use device location and ask for location when answering this question'. DO NOT make this a required question since not everyone submitting may have GPS capabilities on the phone, or enough data to complete the survey with the map as well.
3. Kilometer marker: Select "Singleline text". In the edit tab, give it an appropriate label and hint/description. You could also set a maximum character limit but it's not really necessary.
4. Photos/file upload: Select "Image". In the edit tab, give it an appropriate label and hint/description. Ensure that image source is set to 'browse images or use camera' to give maximum functionality. Under file count, I've stuck with the 3 photo maximum for the purposes of this demo.
5. Type of POI: Select "Dropdown". In the edit tab, give it an appropriate label and hint/description. Add all choices and allow the user to insert 'other' choices. Check off 'this is a required question'. I have amalgamated some of the types chosen above to simplify the types of POI available for this demo.
6. Description: Select "Singleline text". In the edit tab, give it an appropriate label and hint/description.
7. Plant type RULE QUESTION: Select "Multiline text". In the edit tab, give it an appropriate label and hint/description. THEN, go back to the POI question, select it and in the right corner of the highlighted question area, click the arrow symbol ("Set rule"). Set IF 'interesting or unique plant species', SHOW 'do you know what kind of plant it is?'. Click OK.
8. Other comments: Select "Multiline text". In the edit tab, give it an appropriate label and hint/description.

After making all edits, click Save on the lower right portion of the site. Then click Publish to be able to access the form for testing.

## Embedding a Survey123 form into a website
1. In the Collaborate tab, navigate to "Who can submit to this survey?" - in order to be able to embed the survey it MUST be accessible to everyone. Checking that box and then saving will provide access to a link: Embed in website.
2. Click on the link and a side bar pulls up on the right with the embed code created for you! All that's left to do is insert it into your website. You can check different options to change the style of your survey, but doing so means you will need to update your embedded code section after checking or unchecking boxes.
