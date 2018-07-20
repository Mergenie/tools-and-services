# Testing Tools and Services

## Development Time Tests

BDD should be applied for server-side and client-side projects. Each feature should be mapped to one or more scenarios, 
and scenarios should be mapped to stories, and each story can be implemented as a test in the project. Other than BDD
tests, for java and javascript application unit tests should be implemented. The coverage should be more then 90%.

Also regression, integration and UI tests should be implemented to cover all the features and API definitions(such as swagger APIs).

For API testing postman tests can be used from command line with the newman tool. 
Postman tests for API and all the Postman environment should be distributed with the source code, and it should be 
available from API documentation, such as swagger-ui.


#### Tools

JBehave or cucumber can be used for server-side, jasmin can be used for client-side, selenium can be used for UI and
postman can be used for API test, and postman also be used for runtime health and diagnostic checks.


