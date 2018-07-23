# Documentation Tools and Services

## User Manual

User(here the 3rd party developer) manual should be short and easy to understand. It may define Scenarios/Stories and happy paths,
and it will be a part of the Swagger UI, might be collapsed or hidden in normal view, asciidocs/markdown and 
swagger/springfox can be used for that.

## Technical Reference

May contain design desitions, UML diagrams and in-depth explaination. It will also be a part of the Swagger UI, 
might be collapsed or hidden in normal view, asciidocs/markdown and swagger/springfox can be used for that.


## REST API Documentation

Swagger UI/Springfox will be used, it will be generated at runtime and it will available to test online. REST API 
documentation should also contain Postman Collections as a ZIP file.


## Multiple Swagger UIs

Since REST API application will be deployed as separate applications, there has to be a single entry point to 
whole documentation which should have links to all Swagger UIs, Q&A site, Slack and other tools.
