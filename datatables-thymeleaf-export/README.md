datatables-thymeleaf-export
=================================================================

A sample which shows how to export data using both DOM and AJAX sources, based on Spring3.

## Technology stack

 - Thymeleaf 2.1.4.RELEASE
 - Dandelion-Datatables 1.1.0
 - Jackson 1.9.13
 - Spring 3.2.10.RELEASE
 - Hibernate 4.3.5.Final / JPA 2.0
 - H2 database
 
## Features

 - __Data source type__: DOM + AJAX + server-side processing
 - Filter-based export (DOM sources)
 - Controller-based export (DOM and AJAX sources)
 - Customized column content
 - Customized export

## Running this sample

Using __Apache Tomcat__:

    mvn tomcat7:run

Using __Jetty__:

    mvn jetty:run

Using __Docker__ (Tomcat 7):

    docker run -p 9090:8080 dandelion/dt-tml-export

You can then access the sample here: [http://localhost:9090/datatables-thymeleaf-export](http://localhost:9090/datatables-thymeleaf-export)

## Bug/improvement

Please report it using the corresponding issue tracker: [https://github.com/dandelion/dandelion-datatables-samples/issues](https://github.com/dandelion/dandelion-datatables-samples/issues)

=
The [Dandelion team](http://dandelion.github.io/team/).