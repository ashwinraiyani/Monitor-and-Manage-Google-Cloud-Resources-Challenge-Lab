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
  

  Make sure you replace the text REPLACE_WITH_YOUR_TOPIC with the topic you created in task 2, in line 15 of index.js.
  
  Same way copy the content of Package.json from Qwiklabs given and paste in package.json file.
  
  Click on Deploy button
  
  
  Task 4: Remove the previous cloud engineer



