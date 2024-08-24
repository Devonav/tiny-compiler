PL/0 Compiler
This project is a basic implementation of a compiler for the PL/0 programming language. The compiler performs lexical analysis, parsing, and code generation for a subset of the PL/0 language.

Features
Lexical Analysis: Scans the input PL/0 source code and converts it into tokens.
Parsing: Verifies the syntactic structure of the program using recursive descent parsing.
Code Generation: Generates intermediate code for the PL/0 virtual machine.
Error Handling: Identifies and reports various errors such as undeclared identifiers, invalid symbols, and syntax errors.
Symbol Table Management: Manages variables, constants, and procedures in a symbol table.
Execution: The generated code can be executed by a PL/0 virtual machine.
Files
main.c: The main C file containing the implementation of the PL/0 compiler.
tokens.txt: Output file that contains the list of tokens generated during lexical analysis.
elf.txt: Output file that contains the generated assembly code for the PL/0 virtual machine.
```
tiny-compiler
├─ actual_output1.txt
├─ correct
│  ├─ elf16.txt
│  ├─ elf17.txt
│  ├─ elf18.txt
│  ├─ elf19.txt
│  ├─ elf20.txt
│  ├─ elf21.txt
│  ├─ elf22.txt
│  ├─ elf23.txt
│  ├─ elf26.txt
│  ├─ input16.txt
│  ├─ input17.txt
│  ├─ input18.txt
│  ├─ input19.txt
│  ├─ input20.txt
│  ├─ input21.txt
│  ├─ input22.txt
│  ├─ input23.txt
│  ├─ input26.txt
│  ├─ output16.txt
│  ├─ output17.txt
│  ├─ output18.txt
│  ├─ output19.txt
│  ├─ output20.txt
│  ├─ output21.txt
│  ├─ output22.txt
│  ├─ output23.txt
│  └─ output26.txt
├─ errors
│  ├─ input1.txt
│  ├─ input10.txt
│  ├─ input11.txt
│  ├─ input12.txt
│  ├─ input13.txt
│  ├─ input14.txt
│  ├─ input15.txt
│  ├─ input2.txt
│  ├─ input24.txt
│  ├─ input25.txt
│  ├─ input3.txt
│  ├─ input4.txt
│  ├─ input5.txt
│  ├─ input6.txt
│  ├─ input7.txt
│  ├─ input8.txt
│  ├─ input9.txt
│  ├─ output1.txt
│  ├─ output10.txt
│  ├─ output11.txt
│  ├─ output12.txt
│  ├─ output13.txt
│  ├─ output14.txt
│  ├─ output15.txt
│  ├─ output2.txt
│  ├─ output22.txt
│  ├─ output23.txt
│  ├─ output24.txt
│  ├─ output25.txt
│  ├─ output26.txt
│  ├─ output3.txt
│  ├─ output4.txt
│  ├─ output5.txt
│  ├─ output6.txt
│  ├─ output7.txt
│  ├─ output8.txt
│  └─ output9.txt
├─ input1.txt
├─ input10.txt
├─ input11.txt
├─ input12.txt
├─ input13.txt
├─ input14.txt
├─ input15.txt
├─ input2.txt
├─ input3.txt
├─ input4.txt
├─ input5.txt
├─ input6.txt
├─ input7.txt
├─ input8.txt
├─ input9.txt
├─ output.txt
├─ output1.txt
├─ output10.txt
├─ output11.txt
├─ output12.txt
├─ output13.txt
├─ output14.txt
├─ output15.txt
├─ output2.txt
├─ output3.txt
├─ output4.txt
├─ output5.txt
├─ output6.txt
├─ output7.txt
├─ output8.txt
├─ output9.txt
├─ parsercodegen
├─ parsercodegen.c
├─ run_tests.sh
├─ run_tests1.sh
└─ test_results.log

```
