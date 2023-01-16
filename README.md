# bash-scraps
A collection of bash scripts to make life easier

## Contents: 
`chx` Modifies the last edited file to be executable [chmod +x].

`gccx` Compiles the last edited c file with gcc.

`lab` Probably unusable unless you have the same file system as me. Looks at the current path and opens the relevant dcu labsheet. Adding any additional command line argument will open that module's einstein latest upload page. My file system: Documents/[module code]/week1.

`mkdircd` Creates a folder and then cd's into it.

`ppx` Runs the last edited python file.

`subl_create` Creates a file given in cli argument 1, and fills it with standard boilerplate code. The boilerplate code follows the format of the template matching the file extension. template files should be in the format `template_[suffix]`. Any language is supported by `subl_create` as long as there is a matching template file. The template files should be stored in `~/bin`.

`jccx` compiles and executes the last java file edited.
