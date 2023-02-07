AirBnB Clone Console

This is the beginning of a series of AirBnB clones, including a simple console to interface with data.

Usage
Once within the interpreter, you can now use it to interact and manipulate data within the python package. If you type 'help' into the CLI, you will be given a list of commands available for use. These commands are:

EOF - Exits the program

all - Prints a string representation of all stored classes. Can be used with an argument to identify a specific class (ie. all BaseModel)

create - Creates a new instance of the indicated class and assigns it a unique id. It must be given an argument. (ie. create BaseModel)

destroy - Destroys and instance based on class name and id. Requires an argument consisting of classname.id (ie. destroy BaseModel.123456)

help - Displays the documented commands

quit - Exits the program

show - Prints string representation of singular instance. Requires an argument consisting of classname.id (ie. show BaseModel.123456)

update - Allows an update to be made to an instance. Requires 3 arguments: classname.id attribute value (ie. BaseModel.123456 name "Tom") This updates or creates a new key/value pair within the instance.

Examples
$ ./console

(hbtn) help

Documented commands (type help ):

"========================================"

EOF all create destroy help quit show update

$ ./console (hbtn) create BASEMODEL

e6fca61d-f937-427c-8b33-3f52cc10aba7

$ ./console

(hbtn) all

(Lists all objects. Can specify which model)
