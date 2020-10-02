# skillbadge2

Login into Google Console

Task 1: Create a bucket

  click the Navigation menu > Storage --> Browser

  Click Create Bucket

  Name your bucket: Enter any unique-name

  Directly Click - Create

Task 2: Create a Pub/Sub topic

  click the Navigation menu > Pub/Sub > Topics

  Click Create Topic

  Enter any topic name 

  * Make sure you remember the topic name, which will be used in Task 3


Task 3: Create the Cloud Function
  In the console, click the Navigation menu > Cloud Functions.

  Click Create function.

  In the Create function dialog, enter the following values:
  
  ![screen](https://github.com/ashwinraiyani/skillbadge2/blob/main/bucket.png)
  
  Click Next
  Do as per below image.
  
  ![screen](https://github.com/ashwinraiyani/skillbadge2/blob/main/bucket1.png)

  Make sure you replace the text REPLACE_WITH_YOUR_TOPIC with the topic you created in task 2, in line 15 of index.js.
  
  Same way copy the content of Package.json from Qwiklabs given and paste in package.json file.
  
  Click on Deploy button
  
  Now Download the Image : https://storage.googleapis.com/cloud-training/gsp315/map.jpg
  
  Now click on Navigation Menu > Storage > Browser 
  
  Select the bucket create in Task 1:
  
  Upload the map.jpg 
  
  
Task 4: Remove the previous cloud engineer
In the console, click the Navigation menu > IAM.

Find the second user (This is given in qwiklabs as "username 2")

Enter the username2 in "Filter Value" place 
![screen](https://github.com/ashwinraiyani/skillbadge2/blob/main/bucket3.PNG)

Click the pencil icon, select Remove.


Now make sure you have click on Check My Progress after each task and right side 100/100 score must apprear. 
