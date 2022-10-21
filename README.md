# JPMC Task 2

## Tasks
- Make sure the graph update continuously instead of having to click it abunch of times. 
Serve a line graph whose y axis is the stock’s top_ask_price and x-axis is the stock’s timestamp

- Disregard the duplicate data we saw earlier

## Steps
- Update the IState typescript interface to include the new data by defining the property of the showGraph State.
- Define the initial state of the graph as hidden by setting showGraph to false in the state constructor.
- Added a condition to render the Graph when the showState property is true by wrapping the return in an if-else statement
- Modified the getDataFromServer method to ensure we get data from server continuosly by using the seInterval function
- Ensured the funct

- Extended the HTMLElement class from the perspectiveViewerElement
- Modified the lifecycle to the Graph Component by using the ComponentDidUnmount method.
- Added more attribute to the graph element by using setAttribute