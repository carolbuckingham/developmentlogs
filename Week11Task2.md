# Server Services and EC2
1. Open AWS webite. Sign in with IAM root user option: input IAM root user, username, password > Enter.
2. From the AWS management console, launch a virtual machine with EC2.
3. From EC2 dashboard > Instances > find correct instance and select it > Instance state > Start instance.
4. Navigate to DuckDNS website and choose log in with GitHub option > input Github credentials.
5. Update current IP to public IPv4 address from EC2 instances page.
6. Log in to ArcGIS Online with Fleming College credentials.
7. Navigate to the Content page > New item > URL.
8. Navigate to the API Rest Services page for the item (https://yourdomainhere/arcgis/rest/services/YourMapName/MapServer) and copy the URL for the page.
9. Paste the URL into the New item box within AGOL and select the type (autopopulates as ArcGIS Server web service, correct!) > Next.
10. Add a title, tags, and summary for the content being imported > Save.

Keep in mind that to continue to access this map image layer, the EC2 server instance must be running and the IP must be updated on DuckDNS before attempting to open the hosted content.

11. On AWS EC2 site, select user instance > Instance state > Stop instance.
12. Log out of ArcGIS Online, DuckDNS, and AWS. Close all browsers.
