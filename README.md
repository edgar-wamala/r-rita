# r-rita
r-rita means: Refugee Relief, Information, Tracking and Accountability

   # prerequisites
  
 Make sure node js is installed. preferably the latest version.
 
 sms enabler app installed. refer to the link https://www.smsenabler.com/download.html
 
 Make sure you poses a GSM modem device basing on the SMS enabler specifications. refer to the link on how to choose and configure a GSM modem device with SMSenable app
 https://www.smsenabler.com/configuring-connection.html
	
   # r-ritaWeb
   r-ritaWeb is a folder containing the code for web application  built using html,javascript and bootstrap.
   To run the code inside this folder, you need to download it and place it in any desired location on your machine/PC.
   Then after open the folder and run the index.html file by clicking on it to open in a browser. From that point, you can start
    performing actions such as register refugees, viewing delivered items and so on.
 Alternatively you can place the folder inside any server forexample xampp or apache server or any other server and run it as shown below.
 localhost/r-ritaWeb.

  # r-ritaSMS.zip
  This zipped file contains server code written in express/node js  including express modules that make it possible for the server program to communicate or serve both the realtime database from firebase online and the GSM modem through the SMSenabler. 
 Download the file and unzip it.
 Open the folder using VSCode. 
 open terminal and run node index.js
 
![web](https://user-images.githubusercontent.com/51428956/160915724-11fff41b-5e7f-4610-90fc-9a5ef2adf760.JPG)

Go to SMSenabler setting and select SMS to webserver and type in the URL as show below

![sms_setting](https://user-images.githubusercontent.com/51428956/160916404-b679e5b6-2048-473c-82ac-769b2245857f.PNG)

You can now start to send sms messages using the assigned codes

