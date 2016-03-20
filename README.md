#MEAN After Burner
Contains steps to start a Node.js project using TypeScript

##Installing required applications
1. Install node.js from [nodejs.org](https://nodejs.org/)
   This includes NPM, this is the only recommended way of installing NPM.
2. Install Python version < 3, note version 3.0+ will throw errors while installing NPM packages and running Node.js applications.
3. Update NPM package manager 
	```
    npm install npm -g
    ```
4. Install TypeScript compilers/transpiler, 
	```
    npm install typescript -g
    ```
   Install TypeScript if you prefer to use TypeScript over Javascript. To know advantages of TypeScript refer http://www.typescriptlang.org/
5. Install typings 
    ```
    npm install typings -g
    ```
   Typings installs strongly typed definitions of various third party modules, this helps one know declaration syntax of function, property and class in third party modules.
   Note: DefinitelyTyped is deprecated, it is recommended to use Typings.

##Starting a Node.js application
1. Make a directory to contain Node.js project
2. Open command prompt and naviget to above directory
3. Install express-generator, this will install package to generate Node.js web application
    ```	
    npm install express-generator -g
    ```
	Ref. [Express generator](http://expressjs.com/en/starter/generator.html)
4.  Use express generator to create Node.js web application project
    ```
    express <app name>
    ```
5.  Navigate inside project directory created in step 4
    ```
    cd <app name>
    ```
6.  Install all required packages specified in package.json
    ```
    npm install
    ```
7. Try running web app

    On Linux or Mac
	```
    DEBUG=myapp:* npm start
    ```
	On Windows
	```
    set DEBUG=myapp:* & npm start
    ```
   If no error is displayed try opening [localhost:3000](http://localhost:3000) in browser, it should show "Express" on web page and you have your basic web application running.

##Structure of web application
