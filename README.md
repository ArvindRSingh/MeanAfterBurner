# MeanAfterBurner
Contains steps to start a Node.js project using TypeScript

1. Install node.js
	https://nodejs.org/
	This includes NPM, this is the recommended and only way of installing NPM.
2. Install Python version <3, note version 3.0+ will throw errors while install NPM packages and running Node.js applications
3. Update NPM package manager 
	>npm install npm -g
4. Install TypeScript compilers/transpiler, 
	>npm install typescript -g
   Install TypeScript if you prefer to use TypeScript over Javascript. To know advantages of TypeScript refer http://www.typescriptlang.org/
5. Install typings 
	>npm install typings -g
   Typings are strongly typed definitions of various third party modules, this helps one know declaration syntax of function, property and class in third party modules.
   Note: DefinitelyTyped is deprecated, it is recommended to use Typings.

Starting a Node.js application
1. Make a directory to contain Node.js project
2. Open command prompt in the above directory
3. Install express-generator, this will install package to generate Node.js web application
	>npm install express-generator -g
	Ref. http://expressjs.com/en/starter/generator.html
4. >express <app name>
5. >cd <app name>
6. npm install
	This installs required packages mentioned in package.json created by express-generator
7. Try running web app
	On Linux or Mac
	$ DEBUG=myapp:* npm start
	On Windows
	> set DEBUG=myapp:* & npm start
	If no error is displayed try opening http://localhost:3000/ in browser, it should show "Express" on web page. 
	You have your web app running.
