# wcubed-project
A Dev Project directory


## Requirements:
`
npm install -g concurrently @angular/cli typescript nodemon
`
To run wcubed-api, you must install mysql. 

## Errors
* You may receive a TSC error about `body` not existing on `Request`, 
   * You may have to edit that type to add it (this is because of Middleware not being typed) (koa's Request type)
* You may receive a node error about `regeneratorRuntime`.
   * You will have to edit easypost.js and add the variable.
   
