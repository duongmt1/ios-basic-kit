# Closure


#### Closures are self-contained blocks of code that can be passed around your project

## Closure Syntax
```swift
{(parameters) -> return type in
 statements
}
```

## Closure Example
```swift
// With Closure
var sumClosure: (Int, Int) -> (Int) = { num1, num2 in
    return (num1 + num2)
}

// Without closure
func sumNotClosure(_ num1: Int, _ num2: Int) -> Int {
    return num1 + num2
}

sumClosure(1,2)		// 3	
sumNotClosure(1, 2) // 3
```