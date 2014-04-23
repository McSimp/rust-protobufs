Rust Protocol Buffers
=====================

[Protocol buffer](https://developers.google.com/protocol-buffers/) definitions for Rust (the game, not the language).

Compiling
---------

````
$ protoc --cpp_out=. avatar.proto awayevent.proto blueprint.proto item.proto object.proto quaternion.proto savedobject.proto vector.proto vitals.proto worldsave.proto
````

Usage
-----

* worldsave.proto: world saves (*.sav files)
* avatar.proto: avatar files (avatar.bin)
