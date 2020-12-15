# smartparkingMangement

Implemented Smart Parking web application with IoT- deploy the application in AWS using EC2, EBS volumes, ASG, Muti-AZ- for High availability and fault-tolerance for the application, used DynamoDB tables to store data, triggered Lambda functions with DynamoDB triggers for Insert only operations, IAM, AWS IoT Core to establish communication between AWS and sensors, ELB, CI/CD Pipeline to deploy any changes from developers using Code pipeline stack in AWS. 

This project Contains IoT Code - Sensor sending data to AWS IoT Core in IoT folder
Web application - Node.js ,web parking application talking with AWS DynamoDB
Code pipeline - automatic ec2 deployment using codepipeline, Trigger files - Under Scripts 
