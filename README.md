# Core-Language-Interpreter

The files, including CoreInterpreterPart1ShrtPkgSrcPartDist, Runfile, Documentation and 22 java files which are Assign, 
Comp, Cond, Decl, DeclSeq, Exp, Id, IdList, If, In, InputData, Loop, Main, Op, Out, PrettyPrint, Prog, Stmt, StmtSeq, Tokenizer, 
TokenKind and Trm. All of the 22 java files are also in the Path: ../CoreInterpreterPart1ShrtPkgSrcPartDist/src/edu/c3341
CoreInterpreterPart1ShrtPkgSrcPartDist is the structure provided by instructor.
Runfile contains a single line of test that show how to run my program from the command line.
Documentation contains the description of the design of my interpreter.
Assign.java	Implementation of parser print and executor of Assign Object.
Comp.java 	Implementation of parser print and executor of Comp Object.
Cond.java 	Implementation of parser print and executor of Cond Object.
Decl.java 	Implementation of parser print and executor of Decl Object.
DeclSeq.java 	Implementation of parser print and executor of DeclSeq Object.
Exp.java 	Implementation of parser print and executor of Exp Object.
Id.java 	Implementation of parser print and executor of Id Object.
IdList.java 	Implementation of parser print and executor of IdList Object.
If.java 	Implementation of parser print and executor of If Object.
In.java 	Implementation of parser print and executor of In Object.
InputData.java 	Help class to read the integer object from the data file.
Loop.java 	Implementation of parser print and executor of Loop Object.
Main.java 	Main class of the whole interpreter.
Op.java 	Implementation of parser print and executor of Op Object.
Out.java 	Implementation of parser print and executor of Out Object.
PrettyPrint.java 	Help class to print the program.
Prog.java 	Implementation of parser print and executor of Prog Object.
Stmt.java 	Implementation of parser print and executor of Stmt Object.
StmtSeq.java 	Implementation of parser print and executor of StmtSeq Object.
Tokenizer.java 	A java that can split all the token.
TokenKind.java 	Eum class.
Trm.java 	Implementation of parser print and executor of Trm.

How to compile my program (In stdlinux):
Compile:
1. Going to the path ../CoreInterpreterPart1ShrtPkgSrcPartDist/src/edu/c3341/
2. Under this path, compile them by using "javac *.java"
3. After the compiled file generated, move them, 4 '.class' files to the bin folder by using "mv *.class ../../../bin/edu/c3341"

Execute:
4. Going to the bin folder, you can use "cd ../../../bin" to do that
5. In the bin folder, Run the program by using "java edu/c3341/Main ../data/<coreProgram> ../data/<InputData> <print/doNotPrint>"
(Here I add /data/ because I put the test case provided by instructor into the data folder)
