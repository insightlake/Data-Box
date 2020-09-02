<img style="width:100%;" src="images/data-intake.jpg">

What is InsightLake Data Intake?
-----------

InsightLake Data Intake solution enables a company's vendors to upload data in secure and governed manner. A staging workspace is created for vendors where they can upload data and make modifications if necessary. Once ready they can commit the uploaded data so the company can use it.
Data Intake generates appropriate notifications to the company's data intake team to verify the quality of uploaded data. 

Data Intake allows vendors to upload variety of data sets like CSV, documents, images, videos etc.
Data Intake allows vendors to upload the data using different channels:
* Streaming (gRPC) : Mobile Apps for async data transfer
* API : Web UIs, apps
* SFTP : Desktop Apps like FileZilla
* Cloud App : Desktop 

## Data Intake

<img style="width:100%;" src="images/intake-portal/intake-poratl-staging.png">

## Activity

<img style="width:100%;" src="images/intake-portal/activity-page.png">

## Notifications

<img style="width:100%;" src="images/intake-portal/notifications-page.png">

## Viewer

<img style="width:100%;" src="images/viewer/viewer-page.png">

## Image Viewer

<img style="width:100%;" src="images/image-viewer/image-annotation.png">

## Video Viewer

<img style="width:100%;" src="images/video-viewer/video-locations.png">

## Lidar Viewer

<img style="width:100%;" src="images/lidar-viewer/lidar-view.png">

## Audit

<img style="width:100%;" src="images/admin/audit.png">

## FTP

<img style="width:100%;" src="images/admin/ftp.png">

## Dashboaard

<img style="width:100%;" src="images/admin/dashboard.png">

To learn more, check out [http://insightlake.com/data-intake.html](http://insightlake.com/data-intake.html)

Installation
------
* Download or clone the repository. 
* Run bin/insightlake command.
* Open browser with URL as http://localhost:8080/
* Change configuration in /conf folder to set different ports
* By default H2 database is used, you can change the database details in jdbc.properties file

Installation using docker 
------
* Download or clone the repository. 
* cd /docker
* Run `docker-compose -f docker-compose.yaml up --build`
* Open browser with URL as http://localhost:8080/
* While creating Data Location use below credentials  

        * username : root
        * password : password
        * URL :  jdbc:mysql://mysql:3306/

License
------
InsightLake Data Intake is a commercial product but distributed to be used freely. Please contact contact@insightlake.com for details.

Getting Help
----------

You can get help easily :
Community - Google Groups
Slack Channel
Twitter
Facebook
Email: contact@insightlake.com
