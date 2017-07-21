# <img src="https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Z_ReuseImages/images/information.jpg" width="150" alt="Further Resources"/> Further Resources

* [Knowledge folder](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/tree/master/Knowledge) folder in this repo that contains deep dive articles / info on several relevant topics
* [Resources](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Resources.md) contains links to operational tools, dashboards etc. of the HCP landscape.
* [External Resources and further information](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Resources.md#external-resources-and-further-information) contains many references to external information and advanced topics of cloud application development.
* [HCP Cloud Foundry Positioning, Development and Migration Guideline](https://github.wdf.sap.corp/cc-java-dev/cc-coursematerial/blob/master/Knowledge/HCP_CF%40HCP_Application_Provider_final.pdf) 
* See also the [Java Performance Training](https://wiki.wdf.sap.corp/wiki/display/NWEngPer/Performance+Trainings), especially chapters  1, 5, 6 und 9.

# SDKs
This course focuses on explaining how to write a good microservice and understand the internals that are important. There are a few SDKs developing within SAP that provide a 'empty shell' and APIs to make development for certain cases easier. We expect several SDKs to develop for different scopes and use cases such as IoT, S/4 extensions etc.

The important ones are:
- **[S/4 Extension SDK](https://github.wdf.sap.corp/MA/sdk)** (f.k.a. "FIN SDK"): This SDK originally grew out of experience at FIN and abstracts the environment differences of HCP NEO and Cloud Foundry into an API layer. This makes it easy to migrate apps from HCP to Cloud Foundry. In the mean time the focus has shifted to provide an SDK for partners and customers to easily write custom S/4 extensions. See the [S/4 Cloud SDK wiki](https://wiki.wdf.sap.corp/wiki/x/Y4J3bg) for more details.
 