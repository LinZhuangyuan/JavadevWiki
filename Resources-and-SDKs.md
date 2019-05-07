# <img src="https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Z_ReuseImages/images/information.jpg" width="150" alt="Further Resources"/> Further Resources

* [Knowledge folder](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/tree/master/Knowledge) folder in this repo that contains deep dive articles / info on several relevant topics
* [Resources](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Resources.md) contains links to operational tools, dashboards etc. of the HCP landscape.
* [External Resources and further information](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Resources.md#external-resources-and-further-information) contains many references to external information and advanced topics of cloud application development.
* [HCP Cloud Foundry Positioning, Development and Migration Guideline](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Knowledge/HCP_CF%40HCP_Application_Provider_final.pdf)
* Find more general information and further learning materials on the program see [Cloud Native Development](https://go.sap.corp/cloud-native).
* See also the [Java Performance Training](https://wiki.wdf.sap.corp/wiki/display/NWEngPer/Performance+Trainings), especially chapters  1, 5, 6 und 9.

# CAP

CAP is the internal code name for the 'Cloud Application Programming' model that offers HANA, CDS, UI5 with Java or node.js in a highly integrated stack. The goal is to make writing cloud applications simpler and reduce the boiler-plate code and system level details that developers have to deal with. 

How for this approach will be able to reach is not clear but it is clear that it will be the main-stream environment for customer / partner written extensions to S/4 and other smaller stand-alone applications. You can find a quick overview on the [CAP - getting started](https://github.wdf.sap.corp/pages/cap/get-started/) page.

# SDKs
This course focuses on explaining how to write a good microservice and understand the internals that are important. 
There are a few SDKs developed within SAP that provide APIs as well as project templates to make microservice development in certain areas easier and more efficient, e.g. for different scopes and use cases such as IoT, S/4HANA extensions etc. 

## SAP S/4 HANA Cloud SDK

The SAP S/4HANA Cloud SDK is the framework of choice for developing side-by-side extensions for S/4HANA Cloud systems based on the SAP Cloud Platform.

![S/4 SDK](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Z_ReuseImages/images/s4sdk.jpg)

The [SAP S/4HANA Cloud SDK](https://jam4.sapjam.com/groups/5flp8TOw033gh4INdIYA7w/overview_page/ai0I1Lvle3smbmA8FeelxM) provides many out-of-the-box capabilities for integrating S/4HANA and for writing Cloud-native applications in general: 
- an abstraction of the underlying cloud platform environment (Neo & Cloud Foundry) for simple access and as an option to transition to Cloud Foundry,
- a Virtual Data Model (VDM) for ease of programming and simplified communication with the S/4HANA system, 
- resilience with Hystrix to prevent cascading failure,
- continuous integration and delivery (pipeline as code),
- [tutorials and project templates](https://go.sap.corp/s4sdk-tutorials). 

You may also refer to the detailed [Feature Overview](https://wiki.wdf.sap.corp/wiki/display/RAApps/SDK+Feature+Overview) for further information on how to get started. 