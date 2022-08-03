# TestSuite

* 1 Check the normal behavior of the mainMenu() method of the Main class
  * Interact with the console and check inputs and outputs
  
* C2 Test the Coffee machine doesn't accept a different number of recipe ingredients

* C3 Test that the Coffee machine only accepts unique recipe names

* C4 Test that a recipe can be deleted
  * The recipe has to exist previously
  * The current recipe should be listed among the existing ones
  * Finally, the state of the Coffee Machine should turn to _waiting state_
  * Lastly, it should appear an informative message

* C5 Test the edition of a recipe
  * The recipe has to exist previously
  * The current recipe should be listed among the existing ones
  * Check that a recipe's name cannot be changed
  * Finally, the state of the Coffee Machine should turn to _waiting state_
  * Lastly, it should appear an informative message

* C6 Test the inventory additions
  * It has to be accesible from the menu
  * Check that only coffee, milk, sugar, and chocolate are valid types of inventory
  * Test its correct calculations

* C7 Test the checking of the inventory
  * It has to be accesible from the menu
  * Test its correct calculations
  * Check if the state of the Coffee Machine turns to _waiting state_

* C8 Test if the purchase works fine
  * The _money_ input has to be an integer
  * Test that the money should be enough to buy a beverage
  * Check if there is enough inventory items
  * Finally, the state of the Coffee Machine should turn to _waiting state_
  * Lastly, it should appear an informative message

* C9 Test that the state of the Coffee Machine go back to the _waiting state_
  * Test it for every independent test case context