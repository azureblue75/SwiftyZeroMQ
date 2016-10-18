# ZeroMQ Swift Bindings for iOS

[![Swift][swift-badge]][swift-url]
[![Platform][platform-badge]][platform-url]
[![License][mit-badge]][mit-url]

This package provides [Swift](http://swift.org) API bindings for the famous
[ZeroMQ](http://zeromq.org) library for iOS.

**Note: At the moment, please consider the project experimental.**

> ZeroMQ (also spelled ØMQ, 0MQ or ZMQ) is a high-performance asynchronous
> messaging library, aimed at use in distributed or concurrent applications. It
> provides a message queue, but unlike message-oriented middleware, a ZeroMQ
> system can run without a dedicated message broker. The library's API is
> designed to resemble that of Berkeley sockets.

## Project Goals

- [ ] Provide an easy to use API to ZeroMQ using Swift language idioms
- [x] Provide up to date ZeroMQ binaries for iOS
- [ ] Support linux and macOS plaforms for server-side projects
- [x] Support iOS platform for mobile app projects
- [ ] CocoaPods support
- [ ] Carthage support
- [ ] Swift package manager support
- [ ] More official ZeroMQ examples written
- [ ] Wrap more ZeroMQ API

## Example

```swift
import ZeroMQ

let (major, minor, patch) = ZMQ.version
print("ZeroMQ library version is \(major).\(minor).\(patch)")
```

More examples can be found in the
[examples](https://github.com/azawawi/swift-zmq-examples) github repository.

## CocoaPods

TODO

## Carthage

TODO

## Installation

Please check [LibZMQ](https://github.com/azawawi/swift-libzmq) for installation
instructions.

## Testing

TODO


## Troubleshooting

TODO

## See Also

- [Zewo's ZeroMQ swift bindings](https://github.com/ZewoGraveyard/ZeroMQ)

## Author

[Ahmad M. Zawawi](https://github.com/azawawi)

## License

MIT License

[swift-badge]: https://img.shields.io/badge/Swift-3.0-orange.svg?style=flat
[swift-url]: https://swift.org
[platform-badge]: https://img.shields.io/badge/Platforms-iOS-lightgray.svg?style=flat
[platform-url]: https://swift.org
[mit-badge]: https://img.shields.io/badge/License-MIT-blue.svg?style=flat
[mit-url]: https://tldrlegal.com/license/mit-license
