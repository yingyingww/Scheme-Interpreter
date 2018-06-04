# Interpreter for Scheme (R5RS) written in C.

## Phases of this project
### Phase 1: Linked List
To implement a linked list that will be used throughout the interpreter project.
###### Main files at this phase: linkedlist.c xx

### Phase 2: Talloc("tracked malloc")
To create a garbage collector to manage memory usage throughout the interpreter project.
###### Main files at this phase:

### Phase 3: Tokenizer
To implement a tokenizer for Scheme in C.
###### Main files at this phase:

### Phase 4: Parser
To parse the tokens into a syntax tree.
###### Main files at this phase:

### Phase 5: Eval
To evaluate the Scheme code. Specifically allow the evaluation of
bounded variables, if, let and quote special forms.
###### Main files at this phase:

### Phase 6: Apply
Extend the evaluator's ability to handle define and lambda special forms.
###### Main files at this phase:

### Phase 7: Primitives
To support applying Scheme primitive functions implemented in C; to implement a few primitive functions.
###### Main files at this phase:

### Phase 8: Interpreter
To add a myriad of features to the interpreter including:
##### Main files at this phase:

#### Primitive procedures:
*, -, /, <=, eq?, pair?, and apply.
#### Library procedures:
=, modulo, zero?, equal?, list, and append.
(please find =, modulo, zero?, equal?, in math.scm)

#### Special forms: 
lambda, let*, letrec, and, or, cond, set!, and begin.

#### Garbage collection
A Scheme program is a list of S-expressions. A simple version of mark-and-sweep that cleans up between evaluating these top-level S-expressions is can drastically improve the memory usage. 
#### A simple interface
The classic core of an interpreter is the read–eval–print loop, a.k.a. REPL. Adding this functionality to our code allows for interactive usage.
#### ' as the shorthand for quote special form
For example, '(2 2 8) as the shorthand for (quote (2 2 8))
#### The function load
The expression (load "tofu.scm") reads in the file and excutes the Scheme code within as if it were typed directly as part of the input.
#### More built-in functions to manipulate lists.
In a file called lists.scm, implement the following functions (refer to R5RS, Dybvig, or Racket reference for specification) using only special forms and primitives that you've implemented (e.g., car, cdr, cons, null?, pair?, and apply).
#### More built-in functions with regards to arithmetic.
To implement the following functions using only special forms and primitives that we've implemented (e.g., +, -, *, /, and <=) in a file called math.scm.
#### More to come. Please be patient :)





## Author: 
* **Yitong Chen** - [yitongc19](https://github.com/yitongc19)
* **Yingying Wang** - [yingyingww](https://github.com/yingyingww)
* **Megan Zhao** - [meganzhao](https://github.com/meganzhao)
