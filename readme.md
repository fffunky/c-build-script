# C Build Script

running the executable `./buildproj` will create a directory containing the project template. Thisincludes a 'log' module I created for C projects and a standard catch-all makefile.

Passing in no arguments you will be prompted to enter a project name. Alternatively, you can pass an argument as the project name.

Running the command `./buildproj hello` creates the following directory:
```
hello
    + build
    + src
        - hello.c
        + log
            - log.c
            - log.h
    - makefile
```
