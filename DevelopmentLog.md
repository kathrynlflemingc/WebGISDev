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
20:30 - 22:00
##### Total Time: 
1.5 hour
##### Outcomes: 
Learned more about the capabilities within Experience Builder based on the example apps visited which can be applied to the creation of our app for the group project web solution. Based on these examples, you can use maps, photos, text, and embedded media such as audio and videos (eg. youtube). You can also use a pop-up with directions on how to use the app. The experience builder app can also contain statistics - similar to ArcGIS Dashboards. It appears to be possible to embed ArcGIS Online into an Experience Builder app and access item pages for layers and web maps hosted in your organization. Data from the map can be downloaded from Experience Builder to a CSV or SHP if enabled. Furthermore the Experience Builder app can be formatted as a web page (this is possibly using an embed content widget to embed an existing website using the URL). 
Experimenting with Experience Builder: experimented with the widgets - map, table, feature info, list, legend. Began creating an example experience builder with some old data from the City of Ottawa Parking Services to create a web app showing parking garages and pay stations in the Byward Market (similar to one of the Experience Builder examples). The experience builder app I tried to make never really got off the ground due to an issue with the data I was trying to use, but I was able to import an existing COVID-19 map from Spatial Analysis and play around with the experience builder widgets that way. 
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
### --------------------------------------------------------------------------------------------------
### Week 10:
##### Task ID: 
012
##### Task: 
Experimented with Experience Builder
##### Date: 
March 25, 2021
##### Time: 
20:00 - 22:00
##### Total Time: 
2 hours
##### Outcomes: 
Experimenting with the widgets in Experience Builder:
* Photo widget
	- Purely static - can connect to URL or upload image - widget is not targetable by a trigger and action therefore it cannot change based on the feature selected. 
	- In order to do this you would probably have to have the image attached to the record in ArcGIS Pro and use item details if you wanted the picture to change based on the object selected 
* Table Widget 
	- Can connect to data and display the attribute table - can hide certain columns 
	- Looks as though you can change the data displayed in the table by linking to multiple data sources and 
		
* Pages
	- Not sure yet how to go between pages in the Live View or Preview, but it seems like you can have multiple pages for sure - maybe you need to use a button and link to the next page?
* List
	- Like a series of cards that you can format with text, a button and an image
	- Very different from feature info and table
* Feature info vs. Table
	- Feature info - see one feature at a time and can configure the map to zoom to the selected object 
		- Can set triggers to zoom into the selected feature
		- However when first trying to do this the map would automatically zoom into a feature right when the app opened in preview mode which is not ideal if you want the user to be able to view the entire map before making selections
	- Table - a table of all of the feature attributes simultaneously 
		- Can see all of the features at once
		- Can set triggers on this - however - when selecting records in the table by default you can have more than one selected at a time - so this would not be as useful if you really wanted to zoom in on just that feature if it is selected in the table (you would need to unselect the previous one each time to target just the one of interest)
		- Can have multiple sheets connected to different layers that are changed using the dropdown menu in the table 
		- Note: the only thing about this that isn't ideal is that for records that have a lot of text (ie. The rate structure in my example) you can't see all of it in the table - therefore that information is inaccessible
			- In the feature info you can see the full contents of the record
		- Would be more ideal for layers with LOTS of records
* Feature info - have to select the maximum number of features to show I believe it may not show all of them by default or could be slower to load if there are too many features

##### Resources: 

##### To Do: 
Continue working on experience builder for the group project web solution. 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
013
##### Task: 
Friday Lab - meeting with Shawn, began working on storymaps, connected to a github repository created by Kristine.
##### Date: 
March 26, 2021
##### Time: 
10:00 - 12:00
##### Total Time: 
2 hours
##### Outcomes: 
Began investigating storymaps in more detail to potentially pivot the technology used in the web solution to this. The reasoning behind this potential change is the challenge of using experience builder, as the widgets are tricky to configure. As a group we also question whether we have enough data to make experience builder make sense. A storymap would be a simpler approach to a similar product, however would lack the functionality of selecting individual streams to view more information (such as stream order). In storymaps I began by creating a web map of the streams which have been clipped to the study area. I embedded this map into the storymap and began exploring the different content types and template options available. Kristine created a repository in her github account and I cloned the repository onto my local computer using visual studio code. This will be where we document our progress for the final web solution. 
##### Resources: 

##### To Do: 
Continue to investigate storymaps as an alternative to experience builder. 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
014
##### Task: 
Investigated the content options in ArcGIS Storymaps for the web solution 
##### Date: 
March 30, 2021
##### Time: 
20:30 - 21:30
##### Total Time: 
1 hour
##### Outcomes: 
Investigated the content options in ArcGIS Storymaps further to potentially use for the web solution instead of Experience Builder. Adding web maps is simple if they are created in ArcGIS online and the data can be filtered in order to show only the first and/or second order streams which would be beneficial for the solution (although this functionality would be available in any solution that embeds an ArcGIS online map. After looking at the other content options they are mostly photos, videos, audio, and embedded web content (in addition to text). Because the web solution has very little of this type of content and really only needs one or two web maps, I feel as though using the Storymap for the web solution will not be using Storymaps to its fullest potential, and a better solution for our project and data can be achieved in Experience Builder. For these reasons, I think that working through the bugs and quirks of Experience Builder to create an interactive web map application will be more rewarding and produce a better end product. From this investigation, Storymaps feels more like an application to create slideshows with embedded ArcGIS Online content.
##### Resources: 

##### To Do: 
Pivot back to experience builder to continue working out how to effectively configure the widgets for the web solution. 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
015
##### Task: 
read the Esri Blog: ArcGIS Exprience Builder Beta is Available Now, ArcGIS Experience Builder Out of Beta, Experience Builder Overview
##### Date: 
March 31, 2021
##### Time: 
9:00 - 9:30
##### Total Time: 
0.5 hour
##### Outcomes: 
ArcGIS Experience Builder Beta is Available now: little new information other than that there is a separate developer version of Experience Builder that can be downloaded and can offer more configuration options than the creator version. 
ArcGIS Experience Builder Out of Beta: details some features that were included when transitioning from the Beta version to the fully live online version including: 
* enterprise login
* reusable templates
* expanded language support
* shared themes within organizations
* app launcher access
* improved user experience (specifically being able to find and select page components in the Outline in order to target them individually when editing)

ArcGIS Experience Builder Overview: read over the basic concepts and components of Experience Builder. This reading supported what I have already started to learn when experimenting with experience builder (ie. where things are located on the interface, how widgets are configured, how to add content). This article did not mention how to switch between pages in live view which is what I am really interested in figuring out. 
##### Resources: 
https://www.esri.com/arcgis-blog/products/experience-builder/mapping/experience-builder-overview/
https://www.esri.com/arcgis-blog/products/experience-builder/announcements/arcgis-experience-builder-beta-is-available-now/
https://www.esri.com/arcgis-blog/products/experience-builder/announcements/arcgis-experience-builder-out-of-beta/
##### To Do: 
Would like to figure out how to switch between pages in the live view in Experience Builder. 
### --------------------------------------------------------------------------------------------------
### Week 11:
##### Task ID: 
016
##### Task: 
Attended Wednesday lab, participated in the ArcGIS Experience Builder group discussion 
##### Date: 
March 31, 2021
##### Time: 
14:00 - 16:00
##### Total Time: 
2 hours
##### Outcomes: 
Discussed the pros and cons of Experience Builder with other groups who are using Experience Builder to create their web solution, as well as saw what kind of template each group is working with. The first major outcome from this discussion was seeing how other groups made apps that were more website-like than our groups which is very dashboard-like. This caused our group to decide to each begin to create an experience builder app with a different template to experiment with the layout. A second outcome from this was learning how to go between pages in the live view. This is done by inlcuding a menu in the layout which will show the different pages in the live view. 
##### Resources: 

##### To Do: 
Begin creating an experience builder example using a template the group hasn't explored yet. 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
017
##### Task: 
Looked more in depth at the built in templates for experience builder following Wednesday Lab
##### Date: 
March 31, 2021
##### Time: 
21:45 - 22:15
##### Total Time: 
0.5 hour
##### Outcomes: 
Website-like templates: general, introduction, gallery, epic, snapshot, summary, timeline, scenic, exhibition, parallax
Dashboard-like templates (map focused): foldable, launchpad, jewelrybox, billboard, journey, ribbon, dart, pocket, quick navigation
blank templates: blank fullscreen, blank scrolling. 
Blank templates would have more customization potential than the other templates which would be more configuration based. This might be easier to work with considering we don't have lots of different layers of data. 
##### Resources: 
https://www.esri.com/en-us/arcgis/products/arcgis-experience-builder/overview
##### To Do: 
Begin creating an experience builder example using a template the group hasn't explored yet - possibly trying a blank scrolling template to give more flexibility.
### --------------------------------------------------------------------------------------------------
##### Task ID: 
018
##### Task: 
Created a custom web app for the web solution using the blank scrolling template. 
##### Date: 
April 3, 2021
##### Time: 
20:30-21:30
##### Total Time: 
1 hour
##### Outcomes: 
I chose to use the blank scrolling template in order to create more of a website-like web app which showcases the hydrological information, background information about the rice lake plains, and contains multiple web maps showing stream orders in the rice lake plains. I think this layout was successful because the problem statement for our web solution is related to communicating hydrological information, and with a more dashboard style template I feel that there is nowhere for this information to be placed within the app itself - it would need to be external to the app. 
##### Resources: 

##### To Do: 
Continue editing the web app. 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
019
##### Task: 
Worked on experience builder 
##### Date: 
April 7, 2021
##### Time: 
8:30 - 9:00
##### Total Time: 
0.5 hours
##### Outcomes: 
Added basemap toggle feature and scale bar to web maps. Basemaps feature will allow for the user to select which basemap they would like to use - aerial imagery is useful to asses the landcover type while a basic grey base map would be useful to just identify location. Aerial imagery would likely be better for conservation work. I also reduced the width of the maps to make it easier to scroll through the page (otherwise I commonly got stuck in the map zooming and out when trying to scroll through the page). 
##### Resources: 

##### To Do: 
Continue editing the web app. 
### --------------------------------------------------------------------------------------------------
##### Task ID: 
020
##### Task: 
Attended Friday Lab
##### Date: 
April 9, 2021
##### Time: 
10:00 - 12:00
##### Total Time: 
2 hours
##### Outcomes: 
Discussed the progress on the experience builder app with Shawn. Shawn suggested the group try to use ArcGIS Hub to create a website-like solution with our embedded experience builder as opposed to the same thing solely in experience builder. For the remainder of the lab I worked on exploring ArcGIS Hub. It was a bit confusing trying to figure out how to make a new Hub website as going to hub.arcgis.com gave examples of templates to work with but no clear way to create anything. Going through ArcGIS Online and the app explorer was much easier as this led directly to my Hub content. The new site that is created uses a default template that can be configured with different widgets and the existing content can be removed. This site doesn't seem very customizable, but would offer an easy solution if the user was new to web design. Unfortunately I learned the hard way that you need to save all of your edits before going into preview mode because all edits will be lost otherwise.
##### Resources: 

##### To Do: 
Redo the work that was lost from ArcGIS Hub
### --------------------------------------------------------------------------------------------------
##### Task ID: 
021
##### Task: 
Worked on an ArcGIS Hub Website
##### Date: 
April 12, 2021
##### Time: 
20:00 - 21:00
##### Total Time: 
1 hour
##### Outcomes: 
Similar to the previous experience, I struggled finding out how to create a new ArcGIS Hub site but found it in the AGOL app explorer. I removed most of the widgets from the template in order to make a website that works better for the solution. I changed the header photo from the default and embedded the headwater streams web maps. I also added text but found it frustrating that you can only choose from a specific set of font sizes and have no choice of font style. I investigated changing background colours but found the side settings bar confusing. All in all, I think ArcGIS Hub is definitely useful for bringing your AGOL content together however, I find that the site isn't as customizable as I would like it to be. This would be very useful if the user didn't have any web design experience, which I am sure is what is is designed for. 
##### Resources: 

##### To Do: 
Continue working with ArcGIS Hub.
