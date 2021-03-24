# Kathryn Little GEOM 99 Development Log
Entries correspond by item ID to items in a time spreadsheet. https://docs.google.com/spreadsheets/d/1lUKwxB6D-XHU_XxhBCz5gyZjIaFscJHnYOMXFN8_jmw/edit?usp=sharing
### Week 7:
##### Task ID: 
001
##### Task Name: 
Create Development log
##### Date: 
March 3, 2021
##### Time: 
15:00-15:15
##### Total Time: 
15 minutes
##### Outcomes: 
Created a development log in github and a corresponding spreadsheet for detailed time recording.
##### To Do: 
Need to continue to update development log throughout the rest of the course. 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
002
##### Task: 
Sign into AWS 
##### Date: 
March 3, 2021
##### Time: 
15:15-15:30
##### Total Time: 
15 mins
##### Outcomes: 
learned how to sign on to the AWS EC2 server, connect my computer to the remote desktop and stop the server.
##### Resources: 
Week 7 Web GIS Development video.
##### To Do: 
Publish to the AWS EC2 server. 
### --------------------------------------------------------------------------------------------------
### Week 8: 
##### Task ID: 
003
##### Task: 
Services in ArcGIS Enterprise, Services and Portal Items readings
##### Date: 
March 8, 2021
##### Time: 
13:30-15:00
##### Total Time: 
1.5 hours
##### Outcomes: 
Learned about the relationships between web services on ArcGIS Server and the ArcGIS Portal. In summary: 
All data used in ArcGIS Enterprise is made available by web services that can be queried by client apps. Geospatial services can include maps, scenes, geoprocessing tools, geodatabases and imagery. Web services are published from ArcGIS Pro or ArcMap and run on server sites. This is made possible by the relationship between server sites and the ArcGIS Portal. Certain types of services can only be published to certain server sites. Services and administrative controls can be accessed by the RESTful API. On ArcGIS Server these are ArcGIS Server Services Directory and ArcGIS Server Administrator Directory. 
##### Resources: 
https://enterprise.arcgis.com/en/server/latest/publish-services/windows/services-in-arcgis-enterprise.htm 
https://enterprise.arcgis.com/en/server/latest/publish-services/windows/relationships-between-web-services-and-portal-items.htm
https://enterprise.arcgis.com/en/server/latest/publish-services/windows/what-is-a-map-service.htm
### --------------------------------------------------------------------------------------------------
##### Task ID: 
004
##### Task: 
Managing Portal from ArcGIS Pro Video 
##### Date: 
March 8, 2021
##### Time: 
15:00-15:30
##### Total Time: 
0.5 hours
##### Outcomes: 
Learned about how to manage ArcGIS Portal from ArcGIS Pro 
##### Resources: 
https://www.youtube.com/watch?v=KItDcnDQce0
### --------------------------------------------------------------------------------------------------
### Week 9:
##### Task ID: 
005
##### Task: 
Configurable Solutions Menu (Wednesday Lab Period)
##### Date: 
March 17, 2021
##### Time: 
14:00 - 16:00
##### Total Time: 
2 hours
##### Outcomes: 
Learned the basics of ArcGIS Experience Builder and its capabilities. Compared this with the function and capabilities of Web App builder. Experience Builder: creates a web app; selection of configurable tools, widgets and templates (or can design your own template); no coding necessary; fully integrated with ArcGIS Online and ArcGIS Enterprise; can incorporate 2D and 3D content in one map. Web App Builder: creates a mapping application on the web; built in tools available; create 2D or 3D web maps; custom widgets and themes can be developed; no coding required; built into ArcGIS Online and ArcGIS Enterprise. Note: widgets and configurable tools can not be copied from Web App Builder to Experience Builder. 
##### Resources: 
https://www.esri.com/en-us/arcgis/products/arcgis-experience-builder/overview
https://www.youtube.com/watch?v=pNrsd5naN7U
https://www.youtube.com/watch?v=Vu6_pBa7zis
https://www.esri.com/en-us/arcgis/products/arcgis-web-appbuilder/overview
https://www.youtube.com/watch?v=nIYE-_Nhdec
##### To Do: 
Try creating a demo experience builder app to learn the functionality further in order to apply this to the group web project. 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
006
##### Task: 
Week 7/8 Checklist: Publishing to EC2 Server, Creat Duck Dns and obtain SSL Certificate 
##### Date: 
March 17, 2021
##### Time: 
16:00 - 17:30
##### Total Time: 
1.5 hours
##### Outcomes: 
Published the Canada Map from ArcGIS Pro to the EC2 server. To do this I got the server running in AWS, added the server connection in ArcGIS Pro and published from Pro. In order to reference the data on the server and not copy the data when publishing, the Canada folder in my directory was zipped and copied to a folder in the same filepath on the EC2. This enabled the data to be referenced when publishing. Prior to this, I created a Duck Dns for my server url which I used when creating the server connection in ArcGIS Pro. I also obtained an SSL certificate to avoid certificating issues when trying to publish. 
##### Resources: 
https://www.youtube.com/watch?v=V2o07DMyNkc&t=237s 
https://www.youtube.com/watch?v=nIRlZN9ECwY 
Week 7 Web GIS Development Video in Adobe Connect
##### To Do: 
Update the IP address of the EC2 on the Duck Dns each time the server is started otherwise the url will not work as the IP address will change each time. 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
007
##### Task: 
Happy Puppies Team Meeting
##### Date: 
March 18, 2021
##### Time: 
12:30 - 14:00
##### Total Time: 
2 hours
##### Outcomes: 
Discussed the web solution for our collab project and worked on completing the problem statement for the Web GIS Group Web Solution Project. As a team we decided to pursue ArcGIS Experience builder to create an interactive web application to provide information on hydrological systems. Experience builder was chosen as it provides lots of functionality and flexibility which we believe will be useful for our web solution needs. 
##### Resources: 

##### To Do: 
Begin planning the design of the ArcGIS Experience Builder web solution we intend to build to solve our problem statement. 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
008
##### Task: 
What is a CDN video 
##### Date: 
March 19, 2021
##### Time: 
21:30 - 21:45
##### Total Time: 
0.25 hours
##### Outcomes: 
Learned the basics of a content delivery network and how it supports video streaming on the internet. Learned the differences between LOSSY and LOSSLESS compression as well as adaptive bit rate, and how these concepts changed the ability to share and stream video drastically. 
##### Resources: 
https://www.youtube.com/watch?v=OV3legWSi6U
##### To Do: 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
009
##### Task: 
Attended Friday Lab, worked on problem statement with group
##### Date: 
March 19, 2021
##### Time: 
10:00 - 12:00
##### Total Time: 
2 hours
##### Outcomes: 
Refined problem statement to reduce the workload of the project. The problem statement was edited to focus more on the creation of a general web app that provides hydrological information about the study area in our collaborative project with a very basic 1-layer web map just to have the web map functionality in the project.
##### Resources: 

##### To Do:
Once problem statement is approved, begin working on web solution for the group project. 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
010
##### Task: 
Explore Experience Builder examples and default templates available within Experience Builder. Began experimenting with Experience Builder to create a simple web app. 
##### Date: 
March 22, 2021
##### Time: 
20:30 - 21:45
##### Total Time: 
1.25 hour
##### Outcomes: 
Learned more about the capabilities within Experience Builder based on the example apps visited which can be applied to the creation of our app for the group project web solution. Based on these examples, you can use maps, photos, text, and embedded media such as audio and videos (eg. youtube). You can also use a pop-up with directions on how to use the app. The experience builder app can also contain statistics - similar to ArcGIS Dashboards. It appears to be possible to embed ArcGIS Online into an Experience Builder app and access item pages for layers and web maps hosted in your organization. Data from the map can be downloaded from Experience Builder to a CSV or SHP if enabled. Furthermore the Experience Builder app can be formatted as a web page (this is possibly using an embed content widget to embed an existing website using the URL). 
Experimenting with Experience Builder: experimented with the widgets - map, table, feature info, list, legend. Began creating an example experience builder with some old data from the City of Ottawa Parking Services to create a web app showing parking garages and pay stations in the Byward Market (similar to one of the Experience Builder examples). 
##### Resources: 
https://experience.arcgis.com/experience/df36d88209d9458bbd5ecf85515de827/?data_id=dataSource_1-Silverwood_NH_Tour_Points_9868%3A3
https://experience.arcgis.com/experience/f7f674ce7a4a45b4afc8c3c4b2bdba7d
https://experience.arcgis.com/experience/e2059f05649442dd943bddfaf5ce1bb8
https://experience.arcgis.com/experience/e29add561dee4c968fbadbe18d7ce307/page/page_24/
https://maps.scag.ca.gov/helpr/?page=page_0
##### To Do: 
Continue to experiment with Experience Builder to get a feel for how our web solution can be formatted and the widgets and non-map content we can implement. 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
011
##### Task: 
Configurable apps video, reading into ArcGIS Dashboards and StoryMaps
##### Date: 
March 23, 2021
##### Time: 
20:45 - 21:15
##### Total Time: 
0.5 hour
##### Outcomes: 
Configurable Apps: web apps configured with python (or arcade?) can filter out certain data in order to refine your search and make the web app more tailored to the user's need in real time. ArcGIS Dashboards: Combines web maps, statistics, and other widgets to create an interactive data presentation app. Layers can be turned on and off to show different things and  widgets can be customized to change their display based on a trigger executed on the map. ArcGIS Storymaps: Essentially a multimedia presentation that can combine maps (can use the rapid map builder built into storymaps if needed) and/or text, photos and video in order to tell a story. Very customizable with no coding needed and templates to choose from. Maps can be brought in from AGOL. The story map attached in resources is an amazing example of the integration of multimedia with photos, text, and maps to create a fully rounded experience for the user contained within a web app. 
##### Resources: 
https://www.youtube.com/watch?v=PQjvUVwqic8
https://www.esri.com/en-us/arcgis/products/arcgis-storymaps/overview
https://www.esri.com/en-us/arcgis/products/arcgis-dashboards/resources
https://storymaps.arcgis.com/stories/42b1a6fe6a524b578becd12c0bee4b4c
##### To Do: 
Continue working on experience builder for the group project web solution.  


