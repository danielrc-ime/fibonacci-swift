# Fibonacci-swift
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
# For n = 0
```swift
func fibonacci(n: Int) {
        var first = 0
        var second = 1
        var third = 0
        var fibArray: [Int] = []
        let num = n - 1
        for _ in 0...num {
            third = first + second
            fibArray.append(first)
            first = second
            second = third
        }
        print(fibArray)
        print("Fib number \(n) = \(fibArray.last)")
    }
```
