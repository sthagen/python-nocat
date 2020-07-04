# python-nocat
Python No Cat is a client communicating via text protocol to endpoints of certain kinds.

## Synopsis
Simple module that offers client functionality adding a few ease of use aspects when compared to plain `netcat` usage. 

You can configure facts about the protocol used like e.g. the special commands inside `JSON` configuration files that are read upon start.

A sample configuration is provided that should get you started easily.

In case a working `readline` module is detected upon start, the usual UNIX command line comfort like navigation, incremental search and history are not blocked ;-).

If such an install is not present, a minimal history functionality is offered but otherwise no interactive fun aspect ...

## Install

Not yet on the cheese shop, but when this is done, a simple `pip install nocat` should be sufficient.

## Development

A simple example (including a specific text protocol definition and macros) will be provided.

	```
	Todo
	```

### Test

Tests will be provided based on the usual `unittest`, `doctest`, and `pytest`. 
Presumably `tox` will be used to ensure regression tests on all relevant platforms are being run easily.

	```
	Todo
	```



Enjoy!

Note: The default branch is `default` :wink:
