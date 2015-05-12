# amfnode

AMF module for NodeJS based on [amflib](https://github.com/timwhitlock/node-amf)

## About

A pure JavaScript implementation of [AMF](http://en.wikipedia.org/wiki/Action_Message_Format) designed for NodeJS.
Can be used to create an AMF web services gateway over HTTP allowing a Flash Player client to communicate with a remote server.

Run "node test.js" to perform a simple serialize & deserialize test. Check that the output matches the variables show in the script.

To test a simple AMF gateway: configure and run the HTTP server in examples/http-server, then configure and run the Flash client in example/http-client.

Also in this project is some experimental work implementing RTMP. This should probably be split into its own project.


## Status

* The AMF library is largely complete and working, but not thoroughly tested.
* The RTMP work is experimental and not ready for use.
* The ByteArray type can be use.


## Known issues

AMF0 is only partially supported, due to it being depreciated. AMF3 should be used by all clients.


## License

amfnode is dual licensed under the MIT and GPL licenses, See LICENSE.
