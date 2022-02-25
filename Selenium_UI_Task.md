# Selenium UI Task

## Description

Use the [following](https://www.saucedemo.com/) public website for your automation task.

The following tools/libraries can be used:
* Selenium [here](https://www.selenium.dev/)
* Language of your choice that supports Selenium

Organize your solution in a zip archive and send it back. 
Note! Please remove all the compiled/built data, if any. 

## Scenario Variant 1
1. Use the standard user and password (they are prone to change, think how to obtain them)
	- Log in with the standard user
	- Add the first and the last item in the cart, verify the correct items are added
	- Remove the first item and add previous to the last item to the cart, verify the content again
	- Go to checkout
	- Finish the order
	- Verify order is placed
	- Verify cart is empty
	- Logout from the system

2. Verify when items are sorted via "Price (high to low)"
	- the items are sorted in the correct manner.

## Scenario Variant 2
Implement the tasks written in **Scenario Variant 1** and do the following as well:
	- Add an ability to filter tests for the test execution 
	- Add custom reporting for the test execution
	- Tests need to be able to be executed on multiple environments (dev, testing, staging, etc..), add necessary configurations.
	- Chrome and Firefox should be supported browsers

#As a bonus, per your choice
	- Support different browser resolutions