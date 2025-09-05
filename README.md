# Abstract-Data-Types-implementation-with-Go

	"Please note that all implementation names and the code itself are written in Spanish.
 	We apologize for any confusion this may cause.
 	The reason is that the project was primarily developed in a Spanish-speaking environment
  	to facilitate collaboration and understanding among the original developers.

This repository contains implementations of several Abstract Data Types (ADTs) in Go, including:
<ul>
  <li>Stack – A Last-In-First-Out (LIFO) data structure.</li>
  <li>Queue – A First-In-First-Out (FIFO) data structure.</li>
  <li>Priority Queue – A queue where elements are dequeued based on priority.</li>
  <li>List – A dynamic list data structure.</li>
  <li>Dictionary – A key-value mapping data structure.</li>
</ul>
<h2>Features:</h2>
<ul>
  <li>Fully implemented in Go.</li>
  <li>Easy-to-use and modular code.</li>
  <li>Provides fundamental operations for each data type (e.g., insert, remove, peek).</li>
  <li>Good starting point for learning Go data structures or building larger projects.</li>
</ul>


<h2>Installation:</h2>
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

<h2>¿How to use each data type?</h2>


Each file defining a data type contains its structure, definition, and syntax for the primitives.


	//EstaVacia devuelve verdadero si la pila no tiene elementos apilados, false en caso contrario. <-----Explanation 
	EstaVacia() bool    <------- Primitive call name

	// VerTope obtiene el valor del tope de la pila. Si la pila tiene elementos se devuelve el valor del tope.
	// Si está vacía, entra en pánico con un mensaje "La pila esta vacia".
	VerTope() T

	// Apilar agrega un nuevo elemento a la pila.
	Apilar(T)

	// Desapilar saca el elemento tope de la pila. Si la pila tiene elementos, se quita el tope de la pila, y
	// se devuelve ese valor. Si está vacía, entra en pánico con un mensaje "La pila esta vacia".
	Desapilar() T
------
License:

This project is open source and available under the MIT License.
