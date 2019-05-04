# Programming Language
- Programming language can be classified into
  - Interpreted language, Compiled language and Hybrid language
  - Dynamic typing language and Static typing language
  - Strong typing language and Weak typing languae
## Interpreted language, Compiled language and hybrid language
Both Compiled language and interpreted language are transfer high-level language into low-level language.
### Compiled Language
- Compiled language will analysis all code first and which will take a lot of time. Then it will throw  errors.
- If no errors, the compiler will convert source code to the **Object code**.
- Linker will link all the **Object code** into the excution file.
- This is best for the production Environment

#### Advantages
- Because source code has been compiled, its execution time is less.
- Execution file can be run independently from the original code. It also doesn't require compiler in the memory.
- Because comiler has see the code upfront, so it can optimize the code.
#### Disadvantages
- If the code need be modified, it should be compiled again.
- Bounded to the specific machine and cannot be ported.
- It will generate intermediate code in the memory or on the disk.
### Interpreted Language
- Interpreted Language does not have analysis procedure and will be translate at the execution time.
- Interpreter will translate and execute line by line.
- If there is an error it will throw it out.
- It supports the dynamic typing
- It is best suited for the development environment.

#### Advantages
- Does not save any machine code, it will save memory
- In web environment, loading time can be noticed, so interpreted language is better than compiled language.
#### Disadvantages
- WHen code executed, the machine should have the corresponding interpreter.
- Interpreter runs slower.
- Do not have output machine code, so every time the code need be executed, it should be interpreted first.
- Interpreter should in the memory when code executed.
- Interpreter can just see one line code each time, so it can not be optimized.
### Hybrid language
- Java, C# are hybrid Language
- //TODO TO BE CONTINUED...

## Dynamic typing and static typing
### Dynamic typing language
- Dynamic typing language is that the language which will do the type checking in the run time.
- If the type is not the appropraite one, an exception will be thrown
- "Duck typing" is just dynamic typing
#### Advantages
- Easy to use and save time
#### Disadvantages
- If there isn't a declaration for the type, it will easily to have an error by spelling mistake

### Static typing language
- Static typing language is the language which will do the type checking in the compile time.
- //TODO Type Inference in java

#### Advantages
- This can reduce errors and helps in efficiency.

## Strong typing and weak typing
### Strong typing language
- Strong typing language means when a variable is specified to a type, then it cannot be changed.
- It also be called "type safety"
### Weak typing language
- Type can be changed after assignment and the value will be converted by the interpreter/compiler automatically.
