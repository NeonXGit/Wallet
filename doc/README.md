NeonX Core
==========

This is the official reference wallet for NeonX digital currency and comprises the backbone of the NeonX peer-to-peer network. You can [download NeonX Core](https://www.neonx.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run NeonX Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/neonx-qt` (GUI) or
- `bin/neonxd` (headless)

### Windows

Unpack the files into a directory, and then run neonx-qt.exe.

### macOS

Drag NeonX Core to your applications folder, and then run NeonX Core.

### Need Help?

* See the [NeonX documentation](https://docs.neonx.org)
for help and more information.
* Ask for help on [NeonX Discord](http://stayneonxy.com)
* Ask for help on the [NeonX Forum](https://neonxcoin.com//forum)

Building
---------------------
The following are developer notes on how to build NeonX Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The NeonX Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* See the [NeonX Developer Documentation](https://neonx.readme.io/)
  for technical specifications and implementation details.
* Discuss on the [NeonX Forum](https://neonxcoin.com//forum), in the Development & Technical Discussion board.
* Discuss on [NeonX Discord](http://stayneonxy.com)
* Discuss on [NeonX Developers Discord](http://chat.neonxdevs.org/)

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [neonx.conf Configuration File](neonx-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [I2P Support](i2p.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [PSBT support](psbt.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
