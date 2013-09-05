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

sudo apt-get install python-protobuf protobuf-compiler
sudo apt-get instsall python-dev build-essential
pip install tornado
pip install pyzmq

protoc --python\_out=.

Running the server
------------------

python app.py server


Open a browser to: http://localhost:8888

Changing cells with the client
------------------------------

python app.py client 3 'new id' 500
