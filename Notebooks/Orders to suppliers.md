# Orders to suppliers

## Introduction

*The Company* is placing four orders to its suppliers to produce the new M04 device. Each order consists of an amount in dollars agreed with the supplier to produce a number of units for one of the three core markets (Europe/EU, North America/NA and Japan/JP).

* Order to supplier 1
    * Dollar total amount: 952000
    * Unit type: M04
    * Location: EU
    * Number of units: 4000
* Order to supplier 2
    * Dollar total amount: 2384400
    * Unit type: M04
    * Location: NA
    * Number of units: 10000
* Order to supplier 3
    * Dollar total amount: 1200550
    * Unit type: M04
    * Location: EU
    * Number of units: 5000
* Order to supplier 4
    * Dollar total amount: ?
    * Unit type: M04
    * Location: JP
    * Number of units: ?
        
## Part A [PY-02E]
As an introduction to basic Python code, we will answer the following questions:
* Following the orders placed, how many units are needed for EU?
* If this is the average monthly unit order, how many units would be ordered in one year?
* What is the average cost of a unit for North America (NA)? And EU?
* Create the Japan (JP) order details. Total budget: 200000 USD, price per unit: 243.63
* Is the cost per unit of each supplier in EU the same?
* Is it True that (on average) JP is more expensive than NA and NA more expensive than EU?
* Create the string to print the label of the shippment (Unit type, location, units, separated by dash)
* Create a second label for shipping with a different carrier, all in lower-case letters and without the dash.
* From the second label, extract the unit type, location, and number of units.

## Part B [PY-03E]
* Using a function, recalculate the average cost per unit for EU devices.
* Use the function for NA.
* Create a function to print on screen the two lables required for shipping:

## Part C [PY-04E]
Take the following code definitions before answering the questions. The elements of `components`, `quantity` and `regional` are related; all elements with in the same position go together. For example: the component cabling is different based on the region (`regional` is `True`) and only 1 component is required to manufacture an M04 device.

`components = ('cabling', 'processorr', 'memory', 'camera', 'network interface', 'battery', 'charger', 'high_resolution_screen')`

`quantity = ('1', '4', '1', '6', '1', '2', '1', '1')`

`regional = (True, False, False, False, False, True, False, False)`

`labels = ['M04-EU-3000', 'M04-NA-10000']`

Questions:
* Fix the first label, as there has been an error. The label should be M04-EU-4000.
* Fix the typo in the word "processor" in components.
* Create a new list with the models, number of required units and the countries. For example: 'M04-EU-4000', model is M04, number of required units is 4000 and country is EU.
* Check if model M03 and M04 are in the required models
* Create a dictionary with components and quantity required to build the component
* Create a dictionary with components and quantity required to fulfill the orders

## Part D [PY-05E]

Use the following variable assignments:

`components = ('cabling', 'processor', 'memory', 'camera', 'network interface', 'battery', 'charger', 'high_resolution_screen')`

`quantity = ('1', '4', '1', '6', '1', '2', '1', '1')`

`regional = (True, False, False, False, False, True, False, False)`

`labels = ['M04-EU-40', 'M04-EU-37', 'M04-NA-30', 'M04-NA-80', 'M04-EU-80']`

Questions:
* Create a function that given the index of the list, returns the cost of a component. Components that are regional specific have an additional cost of 5/unit (EU) and 4/unit (JP).
* Create a function that returns the total cost based on the label. Calculate the cost of each order.
* Capacity for the next production cycle is limited to 100 units. How many units will be made for each country, assuming that the orders are done in the same order as the list?
* What happens if we change the limit to 1000 units?
