# Programming Language
- Programming language can be classified into
  - Interpreted language, Compiled language and Hybrid language
  - Dynamic typing language and Static typing language
  - Strong typing language and Weak typing languae
## Interpreted language, Compiled language and hybrid language
Both Compiled language and interpreted language are transfer high-level language into low-level language.
### Compiled Language
- Compiled language will analyze all code first and which will take a lot of time. Then it will throw errors.
- If no errors, the compiler will convert source code to the **Object Code**.
- Linker will link all the **Object code** into the execution file.
- This is best for the production Environment

#### Advantages
- Because source code has been compiled, its execution time is less.
- Execution file can be run independently from the original code. It also doesn't require compiler in the memory.
- Because compiler has seen the code upfront, so it can optimize the code.
#### Disadvantages
- If the code need be modified, it should be compiled again.
- Bounded to the specific machine and cannot be portable.
- It will generate intermediate code in the memory or on the disk.

### Interpreted Language
- Interpreted Language does not have analysis procedure and will be translate at the execution time.
- Interpreter will translate and execute line by line.
- If there is an error it will throw it out and stop.
- It supports the dynamic typing
- It is best suited for the development environment.
#### Advantages
- Does not save any machine code, it will save memory
- In web environment, loading time can be noticed, so interpreted language is better than compiled language.
#### Disadvantages
- When code executed, the machine should have the corresponding interpreter.
- Interpreter runs slower.
- Do not have output machine code, so every time the code need be executed, it should be interpreted first.
- Interpreter should in the memory when code executed.
- Interpreter can just see one line code each time, so it can not be optimized.
### Hybrid language
- Java, C# are hybrid Language
- This means the source code will be compiled into an intermideate code(byte code), then the byte code will be interpreted by a interpreter or Just-In-Time(JIT) compiler. 
  - Java will be compiled to the byte code then be compiled by the JIT compiler in the JVM. 
  - C# will be compiled to IL(Intermediate Language) then it will be compiled by JIT compiler into machine code in the CLR(Common Language Runtime, which is a implementation of CLI(Common Language Infrastructure)). CLR is a part of .NET Framework.
#### JIT(Just-In-Time) compilation
- This compilation happens during the execution time not prior to it.
- Goal: Combine the speed of the compiled code and the flexibility of interpration
- [Referece](https://www.geeksforgeeks.org/what-is-just-in-time-jit-compiler-in-dot-net/)
#### Advantages
- Less memory used, other method will be executed will be compiled
- Less page fault
- Can perform the AOT optimization faster
- Can perform the runtime optimization
- Executing the machine code is faster than interpration
#### Disadvantages
- Startup delay
- Security issues: The machine code will be directly stored in the memory
#### Optimization
- Detect the frequent used code or loop then cache them

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
