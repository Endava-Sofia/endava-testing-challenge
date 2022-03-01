# REST API Task

## Description

Use the [following](https://reqres.in/) public REST API to complete scenario steps.

The following tools/libraries can be used:
* JMeter -> Download [here](https://jmeter.apache.org/download_jmeter.cgi)
* Postman -> Download [here](https://www.postman.com/downloads/)
* Pure code implementation for testing REST services (REST-Assured for Java, RestSharp for .Net, Requests for Python or any other)

Organize your solution in a zip archive and send it back. 
Note! Please remove all the compiled/built data, if any. 

## Scenario
1. List available users
	- GET */api/users?page=1*
	- Execute one or many JSON Response Assertions
	- Extract single user details (Id, Email)
	- (Optional) Extract all users, sort them by First Name alphabetically. Print sorted collection.
2. Get extracted user details
	- GET */api/users/{USER_ID}*
	- Execute one or many JSON Response Assertions
3. Try to get details of user that doesn't exist
	- GET */api/users/{USER_ID}*
	- Execute one or many Assertions
4. Create UNIQUE new user
	- POST */api/users*
	- Execute one or many JSON Response Assertions
5. Delete newly created user
	- DELETE */api/users/{USER_ID}*
	- Execute one or many Assertions
6. Parameterize base URL
