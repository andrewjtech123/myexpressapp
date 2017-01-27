## Testing Dredd

This is the beginning of a proof of concept to show how we can use dredd to test the implementation of our API endpoints using swagger spec.

To follow along with the first part of this solution validation

* Clone the project
* `cd` to the directory
* run the server with `$ node app.js &`
* test the APi implementation with ``$ dredd api-description.yml http://localhost:3000  # Swagger`

The test uses swagger.yaml file to test against backend api implementation of app.js
