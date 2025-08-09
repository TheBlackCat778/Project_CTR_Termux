# Building
## On Termux.
### Requirements
* Install `build-essential`
* Install `binutils`

### Using Makefile
* `make` (default) - Compile program
	* Compiling the program requires local dependencies to be compiled via `make deps` beforehand
* `make clean` - Remove executable and object files
* `make deps` - Compile locally included dependency libraries
* `make clean_deps` - Remove compiled library binaries and object files
