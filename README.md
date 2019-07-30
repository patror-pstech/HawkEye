# HawkEye
HawkEye Disaster Monitor and Alert System 

## Goal of this project
1. **Reuse** existing options like
   1. For taking *images* 
     * Traffic Cameras
     * ATM/Security Cameras
     * Mobile Phone Cameras
   2. For *measuring*
     * Vehicles (2/3/4 Wheeler - Tyre/Body/Severe Levels)
     * People (Ankle/Waist/Neck/Drowning)
     * Objects (Traffic Cones/Dividers, Electric/Telephone Poles) 
   3. For providing *alerts*
     * Email
     * SMS
     * Whatsapp
1. To provide **Disaster Monitoring and Management**
   1. To *monitor* Floods/Snow levels
   2. To *send alerts* to subscribers
     * Govt. Authority
     * Media
     * Other Subscribers
   3. To provide *map* of the flooded areas based on the subscribers range (in km/miles)
   4. To provide *chat assistance* using
     * Facebook Messenger (**No need of installing any fancy apps or software**)
     * Watson Assistant


# Contents of the Project
## 1. [Documents](https://github.com/patror-pstech/HawkEye/tree/master/Documents)
This folder contains a word document about [the idea](https://github.com/patror-pstech/HawkEye/blob/master/Documents/hawkEye.docx), a [presentation/ppt](https://github.com/patror-pstech/HawkEye/blob/master/Documents/Call-for-Code-2019-Solution-HawkEye.pptx), and a test document of the [Visual Analysis Score of the images](https://github.com/patror-pstech/HawkEye/blob/master/Documents/HawkEye%20Test%20Round1%262_old_ver.docx).

## 2. [Watson Visual Recognition Classses](https://github.com/patror-pstech/HawkEye/tree/master/Watson%20Visual%20Recognition%20Classses)
This folder contains different zip files with categorized images. Just drag and drop the images in watson Visual Recognition and it will train the model.

## 3. [Python and Mqtt])(https://github.com/patror-pstech/HawkEye/tree/master/Python%20and%20Mqtt)
This folder contains the python code and Mqtt to execute the trained Watson Visual Recognition model.

## 4. [Jupyter Notebook](https://github.com/patror-pstech/HawkEye/tree/master/Jupyter%20Notebook)
This folder contains the python code (in [Jupyter Notebook](https://github.com/patror-pstech/HawkEye/blob/master/Jupyter%20Notebook/pyHawkEye0723.ipynb) and [HTML format](https://github.com/patror-pstech/HawkEye/blob/master/Jupyter%20Notebook/pyHawkEye0723.slides.html)) to extract data from data base, send email/sms/whatsapp

## 5. [Map Solution/HawkEyeDemo-Leaflet](https://github.com/patror-pstech/HawkEye/tree/master/Map%20Solution/HawkEyeDemo-Leaflet)
This folder contains the map solution to show flood levels of an area.

## 6. [IBM Watson Assistant](https://github.com/patror-pstech/HawkEye/tree/master/IBM%20Watson%20Assistant)
This folder contains the [chatbot jason file](https://github.com/patror-pstech/HawkEye/blob/master/IBM%20Watson%20Assistant/skill-HawkEyeNavigationAsistant.json). Using this we can train the chatbot, and we can configure it with facebook.
This allows the users to chat with the chatbot without installing any app.
