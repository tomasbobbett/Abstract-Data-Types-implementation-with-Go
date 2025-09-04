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
<ol>
	<li>
Clone the repository:

    git clone https://github.com/tomasbobbett/Abstract-Data-Types-implementation-with-Go.git
</li>
<li>
Move the repo clone to your workspace
</li>
<li>
Make sure to include the repo clone route in your go.work file lke this:

    go 1.22 <-Your specific Go version
    
    use (
	    ./Abstract-Data-Types-implementation-with-Go
	    ./YOUR_PROJECT
    )
</li>
<li>
Run your Go program making the import in your desired project:

    import ("tdas/stack")
</li>
</ol>

Usage:

Each folder contains the implementation of a specific data type. You can import and use them in your projects as needed:

    import ("tdas/stack")
    
    func main() {
        s := stack.NewStack()
        s.Push(10)
        fmt.Println(s.Pop()) // 10
    }
------
License:

This project is open source and available under the MIT License.
