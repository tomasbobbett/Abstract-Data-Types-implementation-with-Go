# Abstract-Data-Types-implementation-with-Go
This repository contains implementations of several Abstract Data Types (ADTs) in Go, including:
<ul>
  <li>Stack – A Last-In-First-Out (LIFO) data structure.</li>
  <li>Queue – A First-In-First-Out (FIFO) data structure.</li>
  <li>Priority Queue – A queue where elements are dequeued based on priority.</li>
  <li>List – A dynamic list data structure.</li>
  <li>Dictionary – A key-value mapping data structure.</li>
</ul>
Features:
<ul>
  <li>Fully implemented in Go.</li>
  <li>Easy-to-use and modular code.</li>
  <li>Provides fundamental operations for each data type (e.g., insert, remove, peek).</li>
  <li>Good starting point for learning Go data structures or building larger projects.</li>
</ul>


Installation:

Clone the repository:

    git clone https://github.com/tomasbobbett/Abstract-Data-Types-implementation-with-Go.git
    
Navigate to the project folder:

    cd Abstract-Data-Types-implementation-with-Go
Run your Go program:

    go run main.go

Usage:

Each folder contains the implementation of a specific data type. You can import and use them in your projects as needed:

    import "github.com/tomasbobbett/Abstract-Data-Types-implementation-with-Go/stack"
    
    func main() {
        s := stack.NewStack()
        s.Push(10)
        fmt.Println(s.Pop()) // 10
    }
License:

This project is open source and available under the MIT License.
