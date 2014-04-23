Rust Protocol Buffers
=====================

[Protocol buffer](https://developers.google.com/protocol-buffers/) definitions for Rust (the game, not the language).

Compiling
---------

````
$ protoc --cpp_out=. item.proto object.proto quaternion.proto savedobject.proto vector.proto vitals.proto worldsave.proto
````

Usage
-----

worldsave.proto can be used to read/write world saves (*.sav files).
