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
let sum: (Int, Int) -> Int = { num1, num2 in
	print(num1 + num2)
}
```