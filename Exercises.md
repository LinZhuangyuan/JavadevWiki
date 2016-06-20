## Environment Setup and Prerequisites

Every participant should set up their development environment in advance. This [document](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/CoursePrerequisites/README.md) describes the installation/configuration steps in detail.


## Day 1

**Microservice Architecture** [[Detail Notes](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/MicroServiceArchitecture/Readme.md)]

**Motivation / Getting Started**
- [Exercise 1: Getting Started](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/CreateMicroservice/Exercise_1_GettingStarted.md)
- [Exercise 2: Provide Hello World Resource on Tomcat](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/CreateMicroservice/Exercise_2_HelloWorldResource.md)

**Create Advertisement Service** [[Detail Notes](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/CreateMicroservice/Readme.md)]
- [Exercise 3: Create Advertisement Endpoints](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/CreateMicroservice/Exercise_3_CreateAdsEndpoints.md)
- [Exercise 4: Create Automated Component Tests](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/CreateMicroservice/Exercise_4_CreateServiceTests.md)
- [Exercise 4.2: [Optional] Implement Update/Delete Test-driven]https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/(CreateMicroservice/Exercise_4_Part2_CreateAdditionalAdsEndpoints.md)
- [Exercise 5: [Optional] Validation and Exceptions](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/CreateMicroservice/Exercise_5_ValidationAndExceptions.md)


## Day 2

**Cloud Foundry Basics** [[Detail Notes](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/CloudFoundryBasics)]
- [Exercise 6: Deploy Advertisement on Cloud Foundry](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/CloudFoundryBasics/Exercise_6_DeployAdsOnCloudFoundry.md)

**Connect Database** [[Detail Notes](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/ConnectDatabase)]
- [Exercise 7: Connect to local PostgreSQL Database](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/ConnectDatabase/Exercise_7_ConnectLocalDatabase.md)
- [Exercise 8.1: Configure Persistence](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/ConnectDatabase/Exercise_8_Part1_ConfigurePersistence.md)
- [Exercise 8.2: Use Repository to Access Database](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/ConnectDatabase/Exercise_8_Part2_UseRepositoryToAccessDatabase.md)
- [Exercise 9: Implement JPA Entity](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/ConnectDatabase/Exercise_9_ImplementJPAEntity.md)
- [Exercise 10: Deploy Ads on Cloud Foundry](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/ConnectDatabase/Exercise_10_DeployAdsWithDBServiceOnCF.md)
- [Exercise 11: [Optional] Implement a Custom Query](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/ConnectDatabase/Exercise_11_Develop_Custom_Queries.md)


## Day 3

**Logging** [[Detail Notes](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/LoggingTracing)]
- [Exercise 12: Setup Logger](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/LoggingTracing/Exercise_12_Setup_Logger.md)
- [Exercise 13: Use SLF4J Features](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/LoggingTracing/Exercise_13_Use_SLF4J_Features.md)
- [Exercise 14: [Optional] Setup Injectable Logger](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/LoggingTracing/Exercise_14_Setup_Injectable_Logger.md)
- [Exercise 15: [Optional] Analyze Log/Traces in Kibana](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/LoggingTracing/Exercise_15_GettingStarted_With_ELK_Stack.md)

**Service-to-Service Communication** [[Detail Notes](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Service2ServiceCommunication/README.md)]
- [Exercise 16: Call User Service (synchronuous)](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Service2ServiceCommunication/Exercise_16_Call_UserService.md)
- [Exercise 17: Call User Service via Hystrix](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Service2ServiceCommunication/Exercise_17_Introduce_Hystrix.md)
- [Exercise 18: Make Communication more Resilient](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Service2ServiceCommunication/Exercise_18_Make_Communication_Resilient.md)
- [Exercise 19: [Optional] Hand-over Correlation-ID](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Service2ServiceCommunication/Exercise_19_Transfer_CorrelationID.md)
- [Exercise 20: [Optional] Use Message Queues](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Service2ServiceCommunication/Exercise_20_Use_Message_Queues.md)
- [Exercise 21: [Optional] Receive MQ Messages](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Service2ServiceCommunication/Exercise_21_Receive_MQ_Messages.md)


## Day 4

**Security** [[Detail Notes](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Security/Readme.md)]
- [Exercise 22: Deploy Application Router for Authentication](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Security/Exercise_22_DeployApplicationRouter.md)
- [Exercise 23: Setup generic Authorization](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Security/Exercise_23_SetupGenericAuthorization.md)
- [Exercise 24: Make Application Secure](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Security/Exercise_24_MakeYourApplicationSecure.md)
 
**Testing Strategy** [[Detail Notes](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/TestStrategy/Readme.md)]
- [Exercise 25: Create System Test](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/TestStrategy/Exercise_25_Create_SystemTest.md)
- [Exercise 26: [Optional] Performance-Testing with JMeter](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/TestStrategy/Exercise_26_PerformanceTesting_With_JMeter.md)


## Day 5

**Continuous Integration and - Delivery**
- [Exercise: [Optional] Setup CD Pipeline](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/ContinuousDelivery/Exercise_Setup_CD_Pipeline.md)


## Advanced Exercises / Demos
- Demo: Tracing with [AOP (AspectJ)](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/LoggingTracing/AOP.md)
- Demo/Exercise: Use Message Queue to bind Statistics Service with [AMQP (RabbitMQ)](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Service2ServiceCommunication/Exercise_20_Use_Message_Queues.md)
- Demo/Exercise: [Create Performance Test with JMeter](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/TestStrategy/Exercise_26_PerformanceTesting_With_JMeter.md)
- Demo/Exercise: Make use of HANA Database
  - [connect HANA database via JDBC](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Hana/Demo_HANA.md)
  - [create Hana artefacts via HDI](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Hana/Demo_HANA_HDI.md)
- Demo: [Hystrix Dashboard](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Service2ServiceCommunication/HystrixDashboard.md)