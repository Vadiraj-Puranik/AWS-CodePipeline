 ## Architecture Diagram of the application
 
![HeartBeat-Application](https://github.com/Vadiraj-Puranik/AWS-CodePipeline/assets/113619300/e03eb7bc-80dd-49b9-b93b-c72670b6f37e)


 ## Steps

 * ### EC2 Instances Launched for testing Application(Windows OS)
 ![AWS EC2 Instance](https://github.com/Vadiraj-Puranik/AWS-CodePipeline/assets/113619300/d4b6b283-06b4-4387-b4fa-a9f281607df7)

* ### AWS S3 Storage for Storing Artifacts of Application
![Application code - S3](https://github.com/Vadiraj-Puranik/AWS-CodePipeline/assets/113619300/2dab109f-ad38-4f36-b181-cb2a4f6594a0)

* ### AWS CodeDeploy Stack with Deployment Groups
![AWS CodeDeploy Deployments](https://github.com/Vadiraj-Puranik/AWS-CodePipeline/assets/113619300/d111e74b-635b-4118-97d0-b2c7a823701b)

* ### AWS Instances status before rolling upgrade 
![Application HeartBeat](https://github.com/Vadiraj-Puranik/AWS-CodePipeline/assets/113619300/e1e2f1f9-c8f9-4adf-835f-a0586ae79210)

* ### AWS Instances status after rolling upgrade
![Application HeartBeat - After Rolling New Update](https://github.com/Vadiraj-Puranik/AWS-CodePipeline/assets/113619300/f5bf197f-48ec-4529-a596-51ec8ae83c22)


Note: This Approach Follows **In-place** Deployment Strategy.
