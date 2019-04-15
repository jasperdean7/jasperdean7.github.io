---
title: "Go: for loop and switch"
excerpt: "Example of the `for` statement with a `switch`."
last_modified_at: 2019-01-06T19:27:01-05:00
categories:
  - Golang
tags: 
  - code
  - golang
  - go
---

## Go
Example of the `for` statement with a `switch` in the block.
```go
package main

import "fmt"

func main() {
	for i := 0; i <= 3; i++ {
		switch i {
		case 0:
			fmt.Println(i, "Zero")
		case 1:
			fmt.Println(i, "One")
		case 2:
			fmt.Println(i, "Two")
		default:
			fmt.Println(i, "Unknown Number")
		}
	}
}
```
