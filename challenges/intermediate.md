# Intermediate

## 1. [Fibonacci closure](https://tour.golang.org/moretypes/26)

  Implement a fibonacci function that returns a function (a closure) that returns successive fibonacci numbers (0, 1, 1, 2, 3, 5, ...).

  ```golang
  package main

  import "fmt"

  // fibonacci is a function that returns
  // a function that returns an int.
  func fibonacci() func() int {
  }

  func main() {
    f := fibonacci()
    for i := 0; i < 10; i++ {
      fmt.Println(f())
    }
  }
  ```

## 2. [rot13Reader](https://tour.golang.org/methods/23)

## 3. Implement linked list

## 4. Exercism - PaasIO

## 5. Write your own http server using standard library

Implement a simple http server.

- Send your name from the client and process it on the server
- Switch the data types for the payload, see how they behave
- Write few more handlers and call them on the server side
- Experiment with `encoding/xml`
