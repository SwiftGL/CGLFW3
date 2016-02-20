# Swift C bindings for GLFW v3

[GLFW home page]
(http://www.glfw.org)

This is a package for the open source Swift. Usage:

- Install GLFW version 3.
- Include dependency in your `Package.swift`:
```swift
let package = Package(
    dependencies: [
        .Package(url: "https://github.com/SwiftGL/CGLFW3.git", majorVersion: 1)
    ]
)
```
- `import CGLFW3` in your swift file.
- Use as a C API. [Read the Apple docs to learn how.]
  (https://developer.apple.com/library/mac/documentation/Swift/Conceptual/BuildingCocoaApps/InteractingWithCAPIs.html)
