# mean course
M101x Introduction to MongoDB using the MEAN Stack


Overview of the course : 

1. Fundamentals 
2. MongoDB Schema design 
3. REST APIs 
4. Angular JS
5. Iconic Framework




1. Fundamentals 
   
   	MongoDB - document store ; mongod -- mongo core ; mongo - shell 
	MongoDB stores documents in BSON format -- binary JSON format 

	If you interested ; take course on M101 JS / M102 as well to master 

	Nodejs - runtime environment ; nodejs comes with npm included 
	package.json -- a way to declare dependencies 

	Examples:
		underscore 
	
	Some NodeJS modules, including the MongoDB NodeJS driver, use NodeJS C plus plus add-ons.
	These add-ons are compiled during the npm install command

	npm install -- creates ./node_modules/<dependecies ..>

	mongoose -- is an ODM -- object document mapper  -- It does the schema validation on top of the mongodb nodejs driver 

	mongodb driver to be added package,json 

	callback function usually have two parameters ; 
		if the operation fails, the callback gets an error as first argument 
		if the operation is success, the callback gets as null as the first argument and result of operation as second argument 


	callbacks hints concurrency model ; 
	java script running in a loop --   callbacks are asynchronous ;



Chapter - 5 in fundamentals 
	require function : 
		includes external modules 
		also useful to share code between files 
		require can call on file -- which looks for module.exports and returns the function 
		require can call on folder -- which looks for the index.js file inside the folder 
		-- module.exports and exports -- both are same 


Chapter - 6 in fundamentals 
	mocha testing -- popular framework 
	mocha is meant to test as stories than tests
	mocha is BDD 
	to run : ./node_modules/.bin/mocha  test.js

	


