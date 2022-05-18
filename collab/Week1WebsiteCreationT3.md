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

4. We're starting these web pages with a good basis in terms of the metadata information available on the website, including the title, authors, description, keywords, and character set. I'll use the home.html file as an example for filling out this information.
5. Between the head tags, the title section for the home page will be 'Friends of the Dumoine River' and is created as follows:

        <title>Friends of the Dumoine River</title>
        
6. Next, the character set for all pages will be 'UTF-8' and is created as follows:

        <meta charset="UTF-8">

7. The viewport settings for all pages are set with the following code:

        <meta name="viewport" content="width=device-width, initial-scale=1">
        
8. Our group are the authors for all pages on the site. Our names will be included in the head element as follows:

        <meta name="author" content="Allison Talsma, Carol Buckingham, Kira-Marie Lazda">
        
9. Finally, the description and keywords for the home page need to be accurate and brief, and they may change depending on our assessment and the needs of our client:

        <meta name="description" content="Friends of the Dumoine River website homepage - English">
        <meta name="keywords" content="Not-for-profit organization, Outdoors, Recreation, History">

10. After finishing the metadata information, I added the link to the CSS stylesheet within the head element of each page. That code can be seen below with a relative file path being used:

        <link rel="stylesheet" href="CSS\main-1.0.0.css">

11. Within the body element of each page I have added comments to indicate what each page will be used for along with my personal thoughts or things to clarify with our client and liaison.

## Repository organization
*To provide a divide for the English and French versions of the pages, we plan to have separate folders for the languages, and then you will be able to switch back and forth between them with a button within the navbar.*

1. Within VSC with the repository open, select the repository in the left-hand folders pane.
2. Create 2 new folders: 'english' and 'français'
3. Move all English language pages and folders to the English directory.
4. Create a copy of the home.html file within the French directory and rename it - accueil.html
5. Update html and head elements to reflect language change:
        
        <!DOCTYPE html>
        <html lang="fr">
        <head>
          <title>Ami - es de la Rivière du Moine</title>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1">
          <meta name="author" content="Allison Talsma, Carol Buckingham, Kira-Marie Lazda">
          <meta name="description" content="Ami - es de la Rivière du Moine page d'accueil - Français">
          <!-- the keywords need to be translated once we decide on the official ones -->
          <meta name="keywords" content="Not-for-profit organization, Outdoors, Recreation, History">
          <link rel="stylesheet" href="CSS\main-1.0.0.css">
        </head>
        </html>

***The remaining French pages will not be created until the English content has been delivered and those pages have been appropriately formatted.***
