# Selenium Automation
Test Scenario: Purchasing a Mobile phone item from ebay.com

1. Launch a Chrome Browser
2. Navigate to URL https://www.ebay.com/
3. Get the page URL and verify if it is the correct page that is opened.
4. Select “Cell Phones & Accessories” from main drop-down box (All categories drop down)
5. Type “Mobile phone” on search bar
6. Click on Search button icon [ Left hand side]
7. Select brand as “Apple” from side panel[checkbox]
8. Select the first search item.
9. Navigate to a new window.
10. Select Storage, Color etc. from drop downs if available.
Hint: use try catch when check the element availability 
11. Get item Name and print in console.
12. Get item Price and print in console.
13. Get Condition and print in console.
14. Get Quantity and print in console.
Hint: use “value” attribute to get input field value
15. Select “Add to cart”
16. Assert selected details in Shopping Cart page [Name, Price]
17. Assert the ‘quantity of the Item (should not be empty) and print in console.
18. Assert the Shopping cart checkout Subtotal equal to item price.
19. Get Shipping value and print in console.
20. Close the Browser.


## Guideline

###### * Create a maven project.
###### * Test Scenario completion up-to the last step.
###### * Creating TestNG xml Test Suite.
###### * Creating Java classes [Define project hierarchy, create separate classes per each page and run using TestNG test suite level will be given additional marks]
###### * Structuring the program by using TestNG Annotations (@BeforeTest, @Test and @AfterTest etc) and add all programs to TestNG xml as test cases.
###### * Adding parameterized TestNG methods, to pass values.
######  [Ex: Url]
######  Adding assertions, recommended methods and validation messages.
###### * TestNG Test Suite, parallel execution for other browsers.
