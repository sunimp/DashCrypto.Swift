# DashCrypto.Swift

## Requirements

* Xcode 15.4+
* Swift 5.10+
* iOS 14.0+

## Installation

### Swift Package Manager

The [Swift Package Manager](https://swift.org/package-manager/) is a tool for automating the distribution of Swift code
and is integrated into the `swift` compiler. It is in early development, but DashCryptoKit does support its use on
supported platforms.

Once you have your Swift package set up, adding DashCryptoKit as a dependency is as easy as adding it to
the `dependencies` value of your `Package.swift`.

```swift
dependencies: [
    .package(url: "https://github.com/sunimp/DashCrypto.Swift.git", .upToNextMajor(from: "1.1.0"))
]
```

DashCryptoKit include bls.xcframework from https://github.com/dashevo/dashsync-iOS.git ('develop' branch) with legacy bls library and X11 crypto methods.

## License

BlsKit is available under the MIT license. See the LICENSE file for more info.
