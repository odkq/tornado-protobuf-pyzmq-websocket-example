tornado Websocket with protobuf and zmq client example
======================================================

Mashup of various examples for your viewing pleasure

Protocol buffers in Javascript:

https://github.com/dcodeIO/ProtoBuf.js/tree/master/examples/websocket

+

Tornado with Websocket:

https://github.com/hiroakis/tornado-websocket-example

+

ZMQ PUB-SUB magic:

http://zeromq.github.io/pyzmq/


Installation
------------

Install protobuf:

`sudo apt-get install python-protobuf protobuf-compiler`

Install latests tornado an pyzmq (debian's ones will not suffice)

`sudo apt-get instsall python-dev build-essential`

`pip install tornado`

`pip install pyzmq`

Generate exmple\_pb2.py from example.proto

`protoc --python_out=. example.proto`

Running the server
------------------

`./app.py server`

Open a browser to: http://localhost:8888

Changing cells with the client
------------------------------

`./app.py client 3 'new id' 500`

`./app.py client 5 'new id' whatever`

