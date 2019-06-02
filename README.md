#  iDRAC Fan Suppresssor

A simple app to suppress the fans for iDRAC controlled machines.

This was built to support a R720XD (NX3200) but will most likely work with any modern iDRAC controlled machines.

# Installation

Binaries are provided in the releases. Download them onto your machine and run

# Contributing

* You must not lower the test coverage on the repo.

* Go tools compliant (go get, go test, etc.). It needs to be vendorable somewhere else.

# Dependencies

Dependencies are managed using dep. Please refer to its documentation if needed.

# License

I'm not responsible for your server if you run this application against it.

Running this will lower your fan speeds below Dell recommendations.

Your system temperatures will increase as a result which will lower the lifespan of your hardware.