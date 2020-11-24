# fibonacci-swift
Get the "n" number on a fibonacci series

```swift
func fibonacci(num: Int) {
        var first = 0
        var second = 1
        var third = 1
        for _ in 2...num {
            third = first + second
            first = second
            second = third
        }
        print(second)
    }
    
```
