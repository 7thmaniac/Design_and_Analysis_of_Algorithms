# Design and Analysis Of Algorithms

##### Notion of an Algorithm

![Notion of an Algorithm](Pictures/Notion_of_an_Algorithm.png "Notion of an Algorithm")

##### Algorithm

* An Algorithm, is a sequence of unambiguous instructions to solve a problem.

    i.e, for obtaining a required output for any legitimate input in a finite amount of time.

    To obtain this, an algorithm must have some properties

    - Definiteness --> Each instruction is clear and unambiguous.
    - Effectiveness --> Every instruction must be very basic so that it can be carried out, in priciple, by a person using pencil and paper.
    - Finiteness --> If we trace out the instruction of an algorithm, then for all cases, the algorithm must terminate after a finite number of steps.
    - i/p --> 0 or more quantities are externally supplied.
    - o/p --> atleast one quantity is produced.

##### Algorithm Specification

![Algorithm Specification](Pictures/Algorithm_Specification.png "Algorithm Specification")

##### Psuedo-Code Conventions

* Comments begin with // and continue until the end of line.
* Blocks are indicated with matching braces { and }.
* An identifier begins with a letter. The datatypes of variables are not explicitly declared.
* Assignment of values to variables is done using the assignment statement.
    < Variable >:=< expression >;
* There are two Boolean values TRUE and FALSE.
    - Logical Operators: AND, OR, NOT
    - Relational Operators: <, <=, >, >=, =, !=
* The following looping statements are employed.
    while, For and repeat-until
* A conditional statement has the following forms.

    - If < condition > then < statement >
    - If < condition > then < statement >
      else < statement >
    
* There is only one type procedure:
  Algorithm, contains:
  - heading
  - body

  Algorithm Name (Parameter Lists) -----> heading

  {
    ......
    ......    -----------> body
  }


  ##### Performance Analysis

  1. Space Complexity.
  2. Time Complexity.