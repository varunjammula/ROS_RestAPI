# RESTful API in Node and Express to interact with Rosbridge suite.

This package creates a server that runs on Express node package. This server also functions as an endpoint for a REST api. I integrated roslibjs-client node package to extend the REST api to interact with any ROS environment. This server can be deployed and maintained easily rather than chaging the application code. 


## Changes Made
- Integrated [roslibjs-client](https://www.npmjs.com/package/roslibjs-client) node package.

## Usage

- Rest API can be used to subscribe, publish and call_service to ROS environment directly.
- Simple Http verb protocols instead of creating sockets (a pain in C# and Unity).
- Can be used with HoloLens/UWP simply by using HttpClient from namespace Windows.Web.Http

### Credits
Skeleton from [the tutorial](http://scotch.io/tutorials/javascript/build-a-restful-api-using-node-and-express-4)
