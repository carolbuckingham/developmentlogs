# Mapbox API
## Create a Mapbox account
1. Navigate to Mapbox sign up page: https://account.mapbox.com/auth/signup/
2. Fill in Account Details. Password must have an uppercase letter and a special character. > Next
3. Fill in Billing Details > Get started.
4. Log in to connected email and check for verification email. Click link within email to get started.

## Demo 1: Displaying an image
1. From the Mapbox main page, select Install Mapbox GL JS.
2. Select Use the Mapbox CDN option.
3. Create a new HTML file to display the map.
4. From the Mapbox site, copy the 2 displayed lines of code to within the head element for the HTML file > Next.
5. Copy the displayed code into the body of the HTML file > Next.
6. Navigate back to the Mapbox main page and Create a token for this page to restrict access and protect your account.
7. Choose a name and any additional scopes for the tool. Add URL (https://carolbuckingham.github.io/ & api.mapbox.com) to restrict access to the token.

You cannot use a secret access token with Mapbox GL so ensure that no Secret Scopes are selected!! This caused a 20 minute Mapbox help detour into access tokens and URL restrictions which was fixed by deleting the old token and creating a new one with only the Public Scopes checked.

8. Commit changes within GitHub to generate basic web map.
9. Within GitHub repository settings, ensure that the website is set to be published via Pages.
10. Add to HTML in map div to change zoom, center, and style of map to desired settings.
11. Navigate to API Rest Services for Luna server, bigbrains folder (https://luna.flemingcollege.ca/arcgis/rest/services/bigbrains60/).
12. Select Cbucking layer > Scroll to bottom > Export.
13. Set layer to 0, size to 256,256, background transparency to true, output to Image > Get.
14. Copy URL to code example on GitHub

I was not able to get my Luna map to work, I must be doing something wrong in the code but I've checked everything against Shawn's original example. Could it perhaps be because I have to log in to access the layer within API Rest Services?

15. Commit changes and map layer will be displayed on top of Mapbox base layer.

## Demo 2: GeoJSON
1. Copied code structure from mapboxdemo.html to new file: mapboxgeojson.html.
2. stopped at 2:20am due to code issues.
