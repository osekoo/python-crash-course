# Python Crash Course

## Objective
- Walk through basic concepts of Python programming
- Install Python on your operating system (OS)
- Prepare your programming environment
- Run your first Python program

## Basic Concepts of Python Programming
- **Python is a cross-platform programming language**
  * any working python program should run on any operating system
- **Python is a scripting language**
  * Python codes (scripts) are interpreted at runtime by an interpreter
  * Python codes are not compiled into code machine (binary format) before execution
  * errors can only be raised at runtime
- **the interpretation of the codes could depend on the version of Python interpreter**
  * Python has two major versions: 2.x and 3.x
  * some 2.x codes might not run with 3.x interpreter
  * In this course, we’ll only focus on the 3.x version
- **Python is the 3rd most popular programming languages behind Java and C**
  * it’s used for various purposes:
    - academic (to experiment some theoretical concepts)
    - research (artificial intelligence, data science, analytics, etc.)
    - industry (effective production software)
  * large community contributes to Python expansion

## Setting up the programming environment

- **Installing Anaconda for Python 3 (3.x)**
    * follow the instruction described at https://docs.anaconda.com/anaconda/install/ to install Anaconda on your system
    * select the appropriate version according to your operating system
    * launch Anaconda:
      - Linux/MacOs: run the command `anaconda-navigator`
      - Windows: from menu `Programs`
    * walking through this tutorial to learn how to use Anaconda https://docs.anaconda.com/anaconda/user-guide/getting-started/ (read the section related to your operating system)
  
- **Installing Jupyter Notebook and get familiar with it**
    * Jupyter notebook is a live coding tool
    * install Jupyter Notebook from Anaconda dashboard (`Install` button)
    * run Jupyter Notebook (`Launch` button)
    * run your first code:
        - insert new cell and execute this code:
        ```
        print("Hello world! This is my first python code!")
        ```
## Congratulations! 
You successfully run your first Python code.  
For further: navigate through https://python.org and get inspired!


# Python Code interpretation

The Python interpreter performs multiple validations and actions during the code execution
* checks if Python keywords are correctly spelled: **semantic analysis**
    - try to replace print by pront in our previous example
    - what do you get as output?
* checks if the keywords and are correctly combined or used (syntax): **syntactic analysis**
    - try to execute this code:  `print “Hello world! This is my first Python code!)`
    - what do you get as output?
    - Can you fix the problem?
* replaces **user defined variables** by their values (see next section)
* checks the **the data types**
* runs the resulting code (may succeed or fail)
