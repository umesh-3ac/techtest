# techtest
Java script method to process data from file

1. Navigate to ruffer_llp_test folder in command prompt
2. npm install - installs all dev dependencies required for this project
3. node ./scripts/processTransactionData  to run main programm
4. npm test - to run tests 

Folder structure Explained:
ruffer_llp_test - Main folder
	input - contains input text file from where data is read an validated
	libs - transaction.js is the main method which has core logic of reading from file and doing necessary validations
	node_modules - NPM packages
	scripts - processTransactionData.js - consumes transaction.js file. Passes input file path to main method
	tests - Mocha -chai tests
	package.json : contains dev dependencies
