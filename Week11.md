# Publish Canada service to personal AWS EC2

1. Open AWS webite. Sign in with IAM root user option: input IAM root user, username, password > Enter. 
2. From the AWS management console, launch a virtual machine with EC2. 
3. From EC2 dashboard > Instances > find correct instance and select it > Instance state > Start instance.
4. Navigate to DuckDNS website and choose log in with GitHub option > input Github credentials. 
5. Update current IP to public IPv4 address from EC2 instances page. 
6. Open a new browser and navigate to rest services for server. 
7. Ensure that manager permissions are enabled via the manager.
8. Within ArcGIS Pro, insert a new ArcGIS server connection. 
9. Click okay on the invalid SSL certificate notifcation. 
10. Log in with provided ArcGIS credentials > Select save credentials to Windows credential manager (this is more secure than saved to connection file).
11. Open Windows Remote Desktop via the search option on computer's taskbar. 
12. Input the public IPv4 address with :444 at the end into Computer section > Enter. 
13. Input provided Windows username and password > Enter. 
14. Confirm on dialog to proceed to computer regardless of authentication. 
15. Once the remote desktop has opened, navigate to C:\GISWorkspace\Canada to confirm presence of Canada folder and shp (copied over to remote desktop in previous session). 
16. Right click on GISWorkspace folder and select Properties > Security > Edit permissions > Users (click the last option to change settings for all users)> check Modify > Apply > Ok.
17. In ArcGIS Pro, right click on the server connection in the Catalog pane > Publish > Map service. 
18. Include a title, summary, and tags for the map to be published with. 
19. Select data to be referenced (not copied), and ensure that the server location has 6443 in it.
20. Click Analyze: once done processing, the top error should be about data not being registered with server.
21. Click ellipses on data source error > Register Data Source With Server.
22. Fill in a name for reference and confirm folder paths on main computer and remote desktop (C:\GISWorkspace\Canada) > Create.
23. Click Analyze again > registration error disappears > Publish.
24. Map published at 12:30:34 AM 2022-03-30
25. Save ArcGIS project and close application.
26. Shut down remote desktop > Reason: unplanned.
27. On AWS EC2 site, select user instance > Instance state > Stop instance.
28. Sign out of AWS and DuckDNS and close all browsers.
