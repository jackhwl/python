## Introduction
  - Course Overview

'''

    The Zen of Python, by Tim Peters

    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts.
    Special cases aren't special enough to break the rules.
    Although practicality beats purity.
    Errors should never pass silently.
    Unless explicitly silenced.
    In the face of ambiguity, refuse the temptation to guess.
    There should be one-- and preferably only one --obvious way to do it.
    Although that way may not be obvious at first unless you're Dutch.
    Now is better than never.
    Although never is often better than *right* now.
    If the implementation is hard to explain, it's a bad idea.
    If the implementation is easy to explain, it may be a good idea.
    Namespaces are one honking great idea -- let's do more of those!

'''
  - Running Python
    - Create virtual environments
      - python3.9 -m venv .v39.  // rm -rf .v39
      - source .v39/bin/activate
      - deactivate
    - Installing Packages
      - pip install -r requirements.txt
      - pip freeze
    - Running Python
      - jupyter notebook
    - Python Basics
      - Objects
        - (0.125).as_integer_ratio()
      - Variables - Lecture
      - Variables - Coding
      - Arithmetic Operations - Lecture
      - Arithmetic Operations - Coding
      - Operator Precedence - Lecture
      - Operator Precedence - Coding
      - Integer Division and Modulus - Lecture
        - a % b = a - b (a // b)
      - Integer Division and Modulus - Coding
      - Comparison Operators - Lecture
      - Comparison Operators - Coding
      - Boolean Operators - Lecture
      - Boolean Operators - Coding
    - Conditional Execution
      - Introduction - Conditional Execution
      - if...else... - Lecture
      - if...else... - Coding
      - elif - Lecture
      - elif - Coding
      - Ternary Conditional Operator - Lecture
      - Ternary Conditional Operator - Code
    - Sequence Types
      - Introduction - Sequence Types
        - homogeneous
          - strings (immutable)
        - heterogeneous
          - lists (mutable)
          - tuples (immutable)
      - Lists - Lecture
      - Lists - Coding
      - Tuples - Lecture
      - Tuples - Coding
      - Strings - Lecture
      - Strings - Coding
      - Slicing - Lecture
      - Slicing - Coding
      - Manipulating Sequences - Lecture
      - Manipulating Sequences - Coding
        - timeit('l.append(1), globals=globals(), number=100_000)
      - Copying Sequences - Lecture
        - shallow copy 
          - applies to mutable sequence types only 
          - my_list[:]
          - my_list.copy()
        - deep copy
      - Copying Sequences - Coding
        - m2 = deepcopy(m1)
      - Unpacking Sequences - Lecture
      - Unpacking Sequences - Coding
        - a, b = b, a
      - Exercises
    - Strings
      - Introduction
      - Unicode - Lecture
      - Unicode - Coding
      - Common String Methods - Lecture
        - https://docs.python.org/3/library/stdtypes.html#str
      - Common String Methods - Coding
      - String Interpolation - Lecture
      - String Interpolation - Coding
        - f"bid: {bid:.4f}, ask: {ask:.4f}, spread: {ask-bid:.4f}"
      - Exercises
    - Iteration
      - Introduction
      - the range Function - Lecture
      - the range Function - Coding
      - For Loops - Lecture
      - For Loops - Coding
      - While Loops - Lecture
      - While Loops - Coding
      - Continue, Break and Else - Lecture
      - Continue, Break and Else - Coding
    - Dictionaries
      - Introduction
      - Associative Arrays and Dictionaries - Lecture
      - Associative Arrays and Dictionaries - Coding
      - Iterating Dictionaries - Lecture
      - Iterating Dictionaries - Coding
      - Working with Dictionaries - Lecture
      - Working with Dictionaries - Coding
      - Exercises
    - Sets
      - Intruduction - Sets
      - Python Sets - Lecture
      - Python Sets - Coding
      - Common Set Operations - Lecture
      - Common Set Operations - Coding
      - Exercises
    - Comprehensions
      - Introduction
      - List Comprehensions - Lecture
        - [expression for item in iterable]
        - comprehensions are actually functions
        - [expression1 for item in iterable if expression2]
      - List Comprehensions - Coding
      - Dictionary and Set Comprehensions - Lecture
      - Dictionary and Set Comprehensions - Coding
      - Exercise
    - Exceptions
      - Introduction - Exceptions
        - LBYL
        - EAFP
      - Raising Exceptions - Lecture
      - Raising Exceptions - Coding
      - Handling Exceptions - Lecture
      - Handling Exceptions - Coding
      - Execercises
    - Iterables and Iterators
      - Introduction Iterables and Iterators
      - Iterables and Iterators - Lecture
      - Iterables and Iterators - Coding
      - Generators - Lecture
      - Generators - Coding
      - Exercises
    - Functions
      - Introduction - Functions