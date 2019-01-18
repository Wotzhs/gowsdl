# WSDL to Go

## This is a fork of https://github.com/hooklift/gowsdl/

This forked version adds the ability to log the soap call request and response.

Currently it is only set to log to the stdout.

## Usage

```go
client := NewClient("https://someurl.com")
client.Debug(True)  // this turns on the logging
client.Debug(False) // this turns off the logging
```