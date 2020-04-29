# Logger
A library with logging and tracing utilities for the Arduino environment.

# Support
Tested on both Arduino Mega and ESP8266. Should probably work on other Arduino platforms...

# Example

The following shows an excerpt of a log generated by the SimpleLog example.

```log
[00:01.041072	<DFT> i 07]	This is an information message
[00:01.046004	<DFT> + 08]	This is a debug message
[00:01.050804	<DFT> # 09]	This is a warning
[00:01.054628	<DFT> ! 10]	This is an error message
[00:01.058048	<DFT> ? 11]	This is a critical error message
[00:01.063172	<DFT> ! 14]	Messages with level >= ERROR are still visible
[00:01.070436	<DFT> ? 15]	Messages with level >= ERROR are still visible

[00:01.098232	<DFT> + 19]	TRACE: simpleLog.ino:80 (void f())
[00:01.215120	<DFT> + 24]	TIME: block at simpleLog.ino:58 took 87 ms
```