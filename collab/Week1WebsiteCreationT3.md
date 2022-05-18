# Website Creation - GitHub
Once you have a repository begun on GitHub, you can choose to edit your files directly through GitHub's website or you can use an external coding software. All further instructions will follow my Visual Studio Code workflows. This document starts off from the end of Week1WebsiteCreationT2.md [https://github.com/carolbuckingham/developmentlogs/blob/main/collab/Week1WebsiteCreationT2.md].

1. Open Visual Studio Code. 
2. From the "File" section of the toolbar, choose to open a folder and navigate to where the repository is saved (mine is saved within a folder for the greater collaborative project). Open the folder.

## Creation and organization of supplemental files
3. Within the CSS folder, I created a new file to house the external CSS for all pages and gave it a version number for future development: version-1.0.0.css
4. Within the JS folder, I created a new file to house the external JavaScript for all pages and gave it a version number for future development: version-1.0.0.js
After creating the above files I then removed the placeholder markdown files within both folders.
5. After communicating with our client, I chose to move the trail and web map pages to a separate folder path (dumoine-river/tote-road) since they would like to have future expansion on their website into the recreational activities they would like to encourage on the trail.

## HTML file skeleton
*I started with the head element of the pages since this will be the simplest to complete and should be done first to clarify the subject matter of each webpage.*

3. Within each page, I added in html, head, and body elements. Make sure to specify the language of the page within the html starting tag (for our site, it will be English on one, French on another). The starting code is as follows:

        <!DOCTYPE html>
        <html lang="en">
          <head>
          </head>
          <body>
          </body>
        </html>

4. {head element stuff}

6. Next, I added the link to the CSS stylesheet within the head element of each page. That code can be seen below with a relative file path being used:

        <link rel="stylesheet" href="CSS\main-1.0.0.css">

6. Within the body element of each page I have added comments to indicate what each page will be used for along with my personal thoughts or things to clarify with our client and liaison.

## Repository organization
*To provide a divide for the English and French versions of the pages, we plan to have separate folders for the languages, and then you will be able to switch back and forth between them with a button within the navbar.*

1. Within VSC with the repository open, select the repository in the left-hand folders pane.
2. Create 2 new folders: 'english' and 'francias'
