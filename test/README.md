# TEST

One of the importanst step during the development and also the product release is the testing.


## Data

Data consist of:
* Input data: <uid>_input_data
* Expected output data. <uid>_expected_data
* Application is executed and the output is saved as <uid>_output_data. Note: <uid>_output_data is not commited to the repo.

## Unit testing

* Unit test focus on the test cases as required by the algorithm. 
* Unit test covers different set of scenarios and use-cases of the algorithm.
* Uses Data folder "Input data", generate "Output data" and compares with "Expected data".
* Unit test is passed, if the "Output data" and "Expected Output data" matches else the test is failed.

## Integration testing

* The Integration testing script/code test the overall application. 
* The script/code executes the unit-test and 
* Test scritp/code to test communication between the different modules.
* Uses Data folder "Input data", generate "Output data" and compares with "Expected data".
* Integration test is passed, if the "Output data" and "Expected Output data" matches else the test is failed.
