# LLM-Literature-Review

### I used ChatGPT for my LLM

### My Question:
My frist question was how are programming languages designed. From here, I asked what is the difference betweeen compiled and interpreted languages. Next, I asked if compiled languages are faster and easier to catch errors what is the benefit of interpreted languages. Finally, I asked why are interpreted languages better for machine learning.

## My First Question

### How are Programming Languages Created?

## Response:
Programming languages are created through a combination of design, theory, and engineering. The process typically involves several steps:
### 1. Purpose and Design Goals:
* **Define the Purpose:** The creators start by identifying the purpose of the language. Some languages are created for general-purpose use (like Python or Java), while others target specific tasks, such as web development (JavaScript), system programming (C), or data analysis (R).
* **Design Principles:** These include deciding whether the language will prioritize performance, ease of use, flexibility, or safety. Trade-offs are made based on the target audience and use cases.

### 2. Syntax Design:
* **Language Syntax:** This involves creating the rules for how code is written, like how to define variables, write loops, and manage functions. Syntax affects readability, ease of learning, and the language's power.
* **Semantics:** This step involves defining the meaning behind the syntax. The creators must determine what a particular piece of code is meant to do at a deeper level.

### 3. Development of a Compiler or Interpreter:
* **Interpreter:** Some languages (e.g., Python, JavaScript) are interpreted, meaning the code is executed line by line by an interpreter program. This makes development more interactive but often less efficient.
* **Compiler:** Compiled languages (e.g., C, C++) translate the entire source code into machine code (or an intermediate form) before execution, often resulting in better performance.
* **Hybrid Models:** Some languages (like Java) are compiled into an intermediate bytecode that is then interpreted by a virtual machine (JVM in Java’s case), blending the strengths of both approaches.

### 4. Standard Library and Ecosystem:
* A programming language often comes with a standard library that provides essential tools like handling files, networking, or working with data structures (e.g., lists, strings). This forms the core ecosystem that developers rely on to build their programs.
* **Third-party Ecosystem:** Over time, languages often grow a broader ecosystem, with tools, frameworks, and libraries provided by the community.

### 5. Iteration and Evolution:
* Once a language is in use, feedback from developers helps guide its evolution. New features are added, bugs are fixed, and sometimes significant overhauls (like Python 2 to Python 3) take place.

### 6. Formal Specification:
* Many languages (like C, Java) are formally specified, meaning that they have a detailed, standardized description of how the language works. This ensures consistency across different compilers or interpreters and makes it easier to understand edge cases and complex behaviors.


Creating a programming language requires a mix of deep theoretical knowledge in computer science, especially in areas like compiler theory, and practical engineering skills.

## My Second Question:

### What Is The Difference Between Interpreted And Compiled Languages?

## Response:
The key difference between interpreted and compiled languages lies in how the code is translated into machine-readable instructions that the computer can execute.

### 1. Compiled Languages:
* **Process:** In a compiled language, the entire source code is translated (or compiled) into machine code (binary code) by a compiler before the program is run. The resulting machine code is then executed directly by the computer's CPU.
* **Speed:** Compiled programs generally run faster than interpreted programs because the translation to machine code happens just once during compilation, and the machine code is optimized for the specific hardware.
* **Error Checking:** Since the entire code is compiled before execution, syntax errors and other issues are caught early, before the program runs.
* **Portability:** The compiled code is typically platform-specific, meaning a program compiled for one type of operating system (e.g., Windows) may not run on another (e.g., macOS) without recompilation.
* **Examples:** C, C++, Rust, Go, and Fortran are all examples of compiled languages.

### Advantages:
* Faster execution
* More efficient memory usage
* Early error detection

### Disadvantages:
* Requires a compilation step before execution
* Platform dependence (unless cross-compilation tools are used)

### 2. Interpreted Languages:
* **Process:** In an interpreted language, the source code is translated on the fly, line by line, into machine code by an interpreter at runtime. There is no separate compilation step; the interpreter executes the code directly
* **Speed:** Interpreted programs generally run slower than compiled programs because the translation happens during execution, which adds overhead
* **Error Checking:** Errors (syntax or runtime) are detected as the program runs, which means bugs might not be found until the relevant part of the code is executed
* **Portability:** Since the interpreter translates the code at runtime, interpreted languages are usually more portable across different platforms. As long as the interpreter is available on a system, the same code can run without modification
* **Examples:** Python, JavaScript, Ruby, PHP, and Perl are examples of interpreted languages

### Advantages:
* Easier debugging and code testing, as code can be run immediately without a separate compilation step
* Platform independence, as long as the interpreter exists for the platform
* More flexibility during runtime (dynamic typing, reflection, etc.)

### Disadvantages:
* Slower execution
* Errors may go undetected until the program is running

### 3. Hybrid Approaches:
Some languages combine both approaches. For example:
* **Java** is compiled into an intermediate bytecode, which is then interpreted or JIT-compiled (Just-In-Time) by the Java Virtual Machine (JVM) at runtime. This provides portability (the same bytecode runs on any platform with a JVM) while maintaining good performance
* **Python** also compiles its source code into bytecode (.pyc files) and then interprets the bytecode using the Python interpreter

### Summary:
* **Compiled languages:** Translate all code into machine code before execution, resulting in faster runtime performance but requiring a compilation step
* **Interpreted languages:** Translate code during execution, which allows for more flexibility and ease of development but at the cost of slower execution
























