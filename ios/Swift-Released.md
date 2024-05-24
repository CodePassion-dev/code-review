# Reference documents:

- [Document Revision History](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/revisionhistory/)

# Swift 5.10

# Swift 5.9

# Swift 5.8

# Swift 5.7

- [Swift 5.7 Released!](https://www.swift.org/blog/swift-5.7-released/)

### 1. Short form of if-let / guard-let to the Optional Binding:

✅ Do this:

```swift
if let myNumber {
    print("My number is \(myNumber)")
}
```

```swift
guard let myNumber else {
    return
}
```

❌ Don't do this:

```swift
if let myNumber = myNumber {
    print("My number is \(myNumber)")
}
```

```swift
guard let myNumber = myNumber else {
    return
}
```
