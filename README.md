# postman
Playground for postman testing using trello api. 
https://developer.atlassian.com/cloud/trello/rest/api-group-actions/

To run the collection you'll need a trello account and to generate an api key and token. You can do that by visiting the following page - https://trello.com/app-key/. The api key and token will then need to be placed into the collection variables. 

For the schema test for create new board I used the following site to convert the response json into a schema - https://www.liquid-technologies.com/online-json-to-schema-converter
The schema was then added as a variable in the pre-request script of the request and referenced in the tests.
