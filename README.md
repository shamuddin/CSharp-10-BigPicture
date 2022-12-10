# C#10-BigPicture

### [1] C#
* Approachable
* Strongly typed (with compiler inference)
* Resilience to change - "HallMark of C#"
* Object-Oriented
* Open source & cross-platform

### [2] Code Execution Models
* Compiled | Native --> C++
	* Strong/Static typing
	* Compile-time type safety
	* Manual memory management
	* Fast(est) performance profile

* Interpreted | Dynamic (REPL) --> Py
	* Loose/dynamic typing
	* Permissive runtime type conversion
	* Automatic memory management
	* Slow performance profile

* Managed | Execution Engine --> C#
	* Strongly typing
	* Runtime type safety
	* Garbage collection
	* Native code performance

* C# code is compiled into IL assemblies.
* IL is JIT-complied at runtime if/when used.
* JITed code exhibits native preformance.
* The CLR ensure runtime type safety.
* The BCL includes general purpose libraries & app framework functionality.