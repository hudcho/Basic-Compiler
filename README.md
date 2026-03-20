# Lexical Analyzer
Created by: Hudson Cho

Description: The goal of this assignment was to create a lexical analyzer that would parse an input file into tokens, adding fields like position, kind, and value, to be later used by a syntax analyzer. Currently main is configured to simply output all tokens processed.

## Build Instructions:
*Note: These instructions assume user is operating on UNIX based sytem. Instructions may vary slightly for Windows systems. Windows Subsystem for Linux may be used if building on Windows causes problems.*
The program can be compiled on linux using the `gcc` command:
```
gcc lexical_anaylzer.c -o lexical_analyzer.exe
```
The program may then be executed as folllows:
```
./lexical_analyzer.exe
```

## Usage:
After building and executing the program the user will be prompted to enter a path to an input file. The user should enter a path relative to the working directory. For example if the directory structure is something like

```
Lexical-Analyzer
        |-----> lexical_analyzer.c
        |-----> lexical_analyzer.exe
        |-----> textFiles
                    |-----> file.txt
```
Then the user should enter "./textFiles/file.txt" to perform a lexical analysis on file.txt

## Development Environment:
Language:           C24

Compiler:           GNU Compiler Collection (GCC 15.2.1)

Code Editory:       Vim

Debugger:           GNU Debugger (GDB 17.1-4.fc43)

Operating System:   Fedora Linux 43
