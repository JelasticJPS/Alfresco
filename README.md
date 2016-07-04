[![Alfresco](../images/view.png)](../../../alfresco)
## Alfresco

The JPS package deploys Alfresco that initially contains 1 application server and 1 database container. 

### Highlights
This package is designed to deploy Alfresco environment is an enterprise content management solution that you can use in the cloud, on-premise and both.<br />
Alfresco's open and tightly integrated ECM and BPM platform is simple, smart and secure. Align people, content and processes to regain control of critical business content, strengthen compliance and optimize processes – making collaboration easy for employees, partners and customers.

### Environment Topology

![Alfresco Topology](https://docs.google.com/drawings/d/1npalDkrrNPmhyT6wHGF-oQhHv9KxBPCOip-OycsR08c/pub?w=505&h=216)

### Specifics

Layer                |     Server    | Number of CTs <br/> by default | Cloudlets per CT <br/> (reserved/dynamic) | Options
-------------------- | --------------| :----------------------------: | :---------------------------------------: | :-----:
AS                   | Tomcat Java |       1                        |           1 / 16                          | -
DB                   |    MySQL      |       1                        |           1 / 16                           | -

* AS - Application server 
* DB - Database 
* CT - Container

**Alfresco Version**: 5.1.0<br/>
**Tomcat Version**: 7.0.67<br/>
**Java Engine**: Java 7<br/>
**MySQL Database**: 5.7.12

### Deployment

In order to get this solution instantly deployed, click the "Get It Hosted Now" button, specify your email address within the widget, choose one of the [Jelastic Public Cloud providers](https://jelastic.cloud) and press Install.

[![GET IT HOSTED](https://raw.githubusercontent.com/jelastic-jps/jpswiki/master/images/getithosted.png)](https://jelastic.com/install-application/?manifest=https%3A%2F%2Fgithub.com%2Fjelastic-jps%2Falfresco%2Fraw%2Fmaster%2Fmanifest.jps)

To deploy this package to Jelastic Private Cloud, import [this JPS manifest](../../raw/master/manifest.jps) within your dashboard ([detailed instruction](https://docs.jelastic.com/environment-export-import#import)).

More information about Jelastic JPS package and about installation widget for your website can be found in the [Jelastic JPS Application Package](https://github.com/jelastic-jps/jpswiki/wiki/Jelastic-JPS-Application-Package) reference.