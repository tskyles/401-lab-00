# Code401: lab-00 Pre-work Deployment Workshop

### Author: Travis Skyles

### Links and Resources
* [submission PR](https://github.com/tskyles/401-lab-00/pull/1)
* [travis](https://travis-ci.com/tskyles/401-lab-00/jobs/286721129)
* [heroku](https://tskyles-401-lab-00.herokuapp.com/)

#### Documentation
* [jsdoc](https://nataliealway-lab-00.herokuapp.com/docs/)

### Modules
#### `pol.js`
##### Exported Values and Methods

###### `isAlive(dead) -> boolean`
The isAlive() method returns a boolean based on the arg sent in.

### Setup
#### `.env` requirements
* `PORT` - Port Number

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns true or false
* Endpoint: `/docs`
  * Renders Developer Documentation
  
#### Tests
* Unit Tests: `npm run test`
* Lint Tests: `npm run lint`
* Assertions Made
  * Assert that isAlive() properly returns a boolean
* Assertions Remaining
  * placeholder for notes to TAs about tests I haven't written yet

#### UML  
*(the following image is from CodeFellows's Deployment Tutorial)*

![UML Diagram](whiteboard.jpg)