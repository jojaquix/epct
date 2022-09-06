# EPCT
## *Entorno Para Cosas Técnicas (Environment For Technical Things)*

This project is inspired in the time I have been working on C after years of work in C++, the ida is create a free matlab or
alternative and expose and learn v features for some kind of projects.

The idea is use **procedural programming technics** in some low level parts not related with the GUI where the widget abstraction (component) is the king.

The low level units use procedural programming, the high level units will be based on Clases and OOP with super easy and intuitive ala Qt4+ Api, like the engine that will expose an OO (or cuasi) api to call functions and retrieval of properties as variables, i.e clear, save enviroment to file, etc.

On the other hand, EPCT aims to make some contrubution by creating a free technical computing environment similar to octave matlab or scilab but including a scripting language we love (for creators at least :))

## Parts:
	* Common
	* Numeric Core
	* Engine
	* Parser
	* Interpreter	
	* GUI


## The language:

basic lenguaje based on modules as pascal (interface, implementation, initialization, finalization)
but in a curly way as C

The extension for script files will be: epctl

###basic examples:

* hello world
```
print("hello world!")
```


* basic function, can be call by any function in
  the same file
```
function add(x,y):z 
{
  z = x + y
} 

// this is not executed when 
// the file is used as module using use
print(add(3,5))
```

* functions can return several values
```
function ops(a, b):(z, y) 
{
	return (a + b, a - b)
}


print(ops(3,5))
```

* matrix and vector sintax is like matlab with some litle changes
```
asdf
```

* we can chain operations over data using pipe operator

x |> select(xxx) |> * 2 |> XXX 