

## Course Overview

The course **Microservices Development in Java** is targeted at application developers who want to learn how to develop a scalable application on HCP Cloud Foundry. You will learn about the key challenges of a public cloud application and about the key elements of cloud applications like: microservice architecture, REST services, stateless apps, cloud foundry as a platform, unit and component testing, connecting to backing services (DBs etc), logging and monitoring, etc.

The participants will develop a microservice running on CF@HCP which exposes its API via REST, connects to a persistence backing service and that communicates with another service. Based on an 'empty shell application' the participants build a real cloud application / microservice including testing and logging on the different levels. After the training you will have an idea about which libraries and frameworks are useful / required in that context.

**Prerequisite: This version of the course assumes a beginner to intermediate level of Java knowledge.** If you are not an experienced Java developer, you can prepare by going through [Test Your Java Knowledge](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/CoursePrerequisites/README.md#test-your-java-knowledge---are-you-ready-for-the-training) .

## Slides
Find [here](http://mo-f8268fdb9.mo.sap.corp:8080/jenkins/job/cc-coursematerial/lastSuccessfulBuild/artifact/Z_Presentations/cc-appdev-java.pdf) the latest slide version.

## Training Schedule

[[https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/raw/master/Abstract/images/Java_CoursePlan.png]]


## Environment Setup and Prerequisites
Every particpant should set up their development environment in advance. This [document](/CoursePrerequisites/README.md) describes the installation/configuration steps in detail.

TODO: There should be an entry for the training in SuccessFactors tool, where all particpants should be registered.


## Day 1

Microservice Architecture [[Detail Notes](MicroServiceArchitecture/Readme.md)]

Motivation / Getting Started
- [Exercise 1: Getting Started](CreateMicroservice/Exercise_1_GettingStarted.md)
- [Exercise 2: Create Hello-World-Resource](CreateMicroservice/Exercise_2_HelloWorldResource.md)

Create Advertisement Service [[Detail Notes](/CreateMicroservice/Readme.md)]
- [Exercise 3: Create Advertisement Endpoints](CreateMicroservice/Exercise_3_CreateAdsEndpoints.md)
- [Exercise 4: Create Automated Service Tests](CreateMicroservice/Exercise_4_CreateServiceTests.md)
- [Exercise 4.2: [Optional] Implement Update/Delete Test-driven](CreateMicroservice/Exercise_4_Part2_CreateAdditionalAdsEndpoints.md)
- [Exercise 5: [Optional] Validation and Exceptions](CreateMicroservice/Exercise_5_ValidationAndExceptions.md)

## Day 2
Cloud Basics [[Detail Notes](CloudFoundryBasics)]
- [Exercise 6: Deploy Advertisement on Cloud Foundry](CloudFoundryBasics/Exercise_6_DeployAdsOnCloudFoundry.md)

Connect Database [[Detail Notes](ConnectDatabase)]
- [Exercise 7: Connect to PostgreSQL Server](ConnectDatabase/Exercise_7_ConnectLocalDatabase.md)
- [Exercise 8.1: Configure Persistence](ConnectDatabase/Exercise_8_Part1_ConfigurePersistence.md)
- [Exercise 8.2: Use Repository to Access Database](ConnectDatabase/Exercise_8_Part2_UseRepositoryToAccessDatabase.md)
- [Exercise 9: Implement JPA Entity](ConnectDatabase/Exercise_9_ImplementJPAEntity.md)
- [Exercise 10: Deploy Ads on Cloud Foundry](ConnectDatabase/Exercise_10_DeployAdsWithDBServiceOnCF.md)
- [Exercise 11: [Optional] Implement Custom Query using JPAQL](ConnectDatabase/Exercise_11_Develop_Custom_Queries.md)

## Day 3
Logging [[Detail Notes](LoggingTracing)]
- [Exercise 12: Setup Logger](LoggingTracing/Exercise_12_Setup_Logger.md)
- [Exercise 13: Use SLF4J Features](LoggingTracing/Exercise_13_Use_SLF4J_Features.md)
- [Exercise 14: [Optional] Setup Injectable Logger](LoggingTracing/Exercise_14_Setup_Injectable_Logger.md)
- [Exercise 15: [Optional] Analyze Log/Traces in Kibana](LoggingTracing/Exercise_15_GettingStarted_With_ELK_Stack.md)

Service-to-Service Communication [[Detail Notes](Service2ServiceCommunication/README.md)]
- [Exercise 16: Call User Service (synchronuous)](Service2ServiceCommunication/Exercise_16_Call_UserService.md)
- [Exercise 17: Call User Service via Hystrix](Service2ServiceCommunication/Exercise_17_Introduce_Hystrix.md)
- [Exercise 18: Make Communication more Resilient](Service2ServiceCommunication/Exercise_18_Make_Communication_Resilient.md)
- [Exercise 19: [Optional] Hand-over Correlation-ID](Service2ServiceCommunication/Exercise_19_Transfer_CorrelationID.md)
- [Exercise 20: [Optional] Use Message Queues](Service2ServiceCommunication/Exercise_20_Use_Message_Queues.md)
- [Exercise 21: [Optional] Receive MQ Messages](Service2ServiceCommunication/Exercise_21_Receive_MQ_Messages.md)

## Day 4
Security
- [Exercise 22: Deploy Application Router for Authentication](Security/Exercise_22_DeployApplicationRouter.md)
- [Exercise 23: Setup generic Authorization](Security/Exercise_23_SetupGenericAuthorization.md)
- [TODO: Exercise 24: Make Application Secure]
 
Testing Strategy
- [Exercise 25: Create System Test](TestStrategy/Exercise_25_Create_SystemTest.md)
- [Exercise 26: [Optional] Performance-Testing with JMeter](TestStrategy/Exercise_XX_PerformanceTesting_With_JMeter.md)


## Day 5
Continuous Integration - Delivery
- [Exercise: Setup CD Pipeline](ContinuousDelivery/Exercise_Setup_CD_Pipeline.md)

## Demos / Advanced Exercises
- Demo: Tracing with [AOP (AspectJ)](LoggingTracing/AOP.md)
- Demo/Exercise: Use Message Queue to bind Statistics Service with [AMQP (RabbitMQ)](Service2ServiceCommunication/Exercise_20_Use_Message_Queues.md)
- Demo/Exercise: [Create Performance Test with JMeter](TestStrategy/Exercise_XX_PerformanceTesting_With_JMeter.md)
- Demo/Exercise: Make use of HANA Database
  - [connect HANA database via JDBC](Hana/Demo_HANA.md)
  - [create Hana artefacts via HDI](Hana/Demo_HANA_HDI.md)
  
## Further Resources

* [Resources](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Resources.md) contains links to operational tools, dashboards etc. of the HCP landscape.
* [External Resources and further information](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Resources.md#external-resources-and-further-information) contains many references to external information and advanced topics of cloud application development.


## Experimental Topics
- Setup local [development environment](/CoursePrerequisites/localEnvSetup/README.md) manually
- Map exceptions using JAX-RS Exception Mappers [Example](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Knowledge/ExceptionMappers.md)
- Validiation of Resource arguments e.g. `@NotNull` [relevant issue](http://stackoverflow.com/questions/31235977/is-it-safe-to-override-apache-cxfs-jaxrsbeanvalidationininterceptor-to-support)
- Creating Kibana-Dashboards using [PerfX App Cockpit](https://wiki.wdf.sap.corp/wiki/display/perfx/App+Performance+Cockpit) ([Example Dashboard 1](http://155.56.252.249/#/dashboard/App-Performance-Cockpit), [Example Dashboard 2](http://155.56.252.249/#/dashboard/Cockpit-Hystrix-Dashboard))
- Make `getAll` request pageable using pageable CRUD repository ([Javadoc](http://docs.spring.io/spring-data/commons/docs/current/api/org/springframework/data/repository/PagingAndSortingRepository.html))
- REST Interface definition (e.g. [RAML](http://raml.org/developers/raml-100-tutorial))
- Usage Monitoring using [SAP Web Analytics](https://jam4.sapjam.com/groups/about_page/ReRAnCGxPG137eKaT8Efhc)
- Feature Switches (e.g. [FF4J](http://ff4j.org/) or [Togglz](http://www.togglz.org/))
- Database schema migration, evolution, and tools (e.g. [Liquibase](http://www.liquibase.org/), [Flyway](http://flywaydb.org/))
- [Storing session data using Redis](Knowledge/Redis.md)
- ... and more


