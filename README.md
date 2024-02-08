# aws-ec2-s3 details
- SQL File Location: aws-ec2-s3/src/main/sql/aws_release_1.sql [link](https://github.com/TheCoderRiya/aws-ec2-s3/blob/main/src/main/sql/aws_release_1.sql)

- For Postman endpoints: aws-ec2-s3/Nimesa.postman_collection.json [link](https://github.com/TheCoderRiya/aws-ec2-s3/blob/main/Nimesa.postman_collection.json)

- DB Config applicaiton.properties: aws-ec2-s3/src/main/resources/application.properties [link](https://github.com/TheCoderRiya/aws-ec2-s3/blob/main/src/main/resources/application.properties)

  

  **Step 1:** Clone the Module

  **Step 2:** Run the DUMP

  **Step 3:** Change the DB config in application.properties (URL, username, password)

  **Step 4:** Import the Postman Json in postman and test the endpoints
  
  


### Result
---------------

1. Discover Services

   **URL:** http://localhost:7878/api/v1/aws/discover-services

   **Parameter:** services
   
   **Values:** EC2, S3 (you can give according to the need)

   ![image](https://github.com/TheCoderRiya/aws-ec2-s3/assets/66270239/be8c043a-e9ba-4425-9a27-4376a8640bf7)


2. Get Job Result

   **URL:** http://localhost:7878/api/v1/aws/get-job-result

   **Parameters:** jobId

   **Values:** Job id what we collected from first endpoint call

   ![image](https://github.com/TheCoderRiya/aws-ec2-s3/assets/66270239/35d94505-f134-44f8-8956-54e152d85509)


3. Get Discovery Result
   
   **URL:** http://localhost:7878/api/v1/aws/get-discovery-result

   **Parameters:** service

   **Values:** EC2, S3 (you can give according to the need)

   ![image](https://github.com/TheCoderRiya/aws-ec2-s3/assets/66270239/b277444d-2c5e-4ec5-a54f-daacf5ef6415)



