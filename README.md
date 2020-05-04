# face-recognizaton

#Install the Ionic CLI following the instructions here.
#Sign in to your Google Account.
#Select or Create a Google Cloud Platform Project.
Please make sure that billing is enabled for your Google Cloud Platform project. To enable billing, follow the procedure provided in the given link.
N.B.: You will not be able to get any response from API until you enable the billing.
#To Enable the Cloud Vision API.
a. First, select a project.
b. After selecting the project, click on “Go to API’s overview” button.
c. Click on “Enable API and Services”,
d. Search for Cloud Vision API.
e. Click on the enable button.
f. To use this API, click on Create Credentials.
g. Choose the Cloud Vision API from the list.
h. Click on “Yes I’m using one or both” and proceed further.
i. Click on the Done button.
j. Click on “Create Credentials”.
k. Click “API key” from options.
l. Copy the API key popped up and save it at a safer place. It should not be made public.
m. Click the close button.
Congrats Your API key has been generated.
Create an ionic Project using the following command at Command Prompt.
##ionic start IonVision blank
$ cd ./IonVision
$ ionic cordova plugin add cordova-plugin-camera
$ npm install --save @ionic-native/camera
$ ionic g service GoogleCloudVisionService

