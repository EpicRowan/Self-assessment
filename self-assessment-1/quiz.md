# Knowledge Quiz

<!--
For multiple choice questions, mark your answer by
replacing [ ] with [x]. For example:

* [ ] One possibility

* [x] I choose this one!

* [ ] Another possibility
-->

## Algorithms

### Which of the following is false regarding algorithms?

* [ ] There are multiple appropriate algorithms that can be used to solve a maze

* [ ] Algorithms are language-specific

* [ ] Binary search is a common algorithm used for sorting unordered collections

* [ ] A brute force approach is a valid way to solve a problem but it's usually
      grossly inefficient


## Filesystem

Use the diagram below to answer the questions in this section.

```
~
├── Documents/
│   └── todo.txt
└── src/
    ├── game/
    │   ├── game.py
    │   └── static/
    │       ├── avatar.png
    │       └─── cursor.png
    └── notes/
        ├── project.txt
        └── week-###txt
```

### What command successfully renames `todo.txt` to `todo-items.txt`?

* [ ] `cp todo.txt todo-items.txt`

* [ ] `cd ~/Documents/todo-items.txt`

* [ ] `mv todo.txt ~/todo-items.txt`

* [ ] `mv todo.txt todo-items.txt`

### Which of the following is NOT a valid way to change directories from `static` to `notes`?

* [ ] `cd ~/Documents/../notes/`

* [ ] `cd ~/src/notes`

* [ ] `cd ../../notes/`

* [ ] `cd ../../../src/notes`


## Git

### In order to track a file using git, you must

* [ ] Initialize a git repository in a local directory

* [ ] Authenticate using Github

* [ ] Run the command `git log`

* [ ] Upload the file to Github

### In the context of Git, a working directory is

* [ ] The copy of the repository shared by the entire team

* [ ] Your particular copy of a repository

* [ ] The most recent copy of the repository on Github

* [ ] The name of the directory that most recently changed


## Lists, tuples, sets

### Lists are mutable because

* [ ] They can be redefined as another list

* [ ] Their contents can be modified without changing location in memory

* [ ] They can be looped over

* [ ] They are ordered and iterable

### Which of the following are immutable and ordered?

* [ ] Lists and Sets

* [ ] Tuples and Sets

* [ ] Lists and Tuples

* [ ] Strings and Tuples

### What is the output of this code snippet?

(Do not run this block of code in Python)

```python
flowers = ["poppy", "mum", "daisy", "sunflower", "rose", "tiger lily"]
my_num = len(flowers) - 1
flowers = flowers[1:my_num]
flowers_ordered = sorted(flowers)
print(flowers_ordered)
```

* [ ] `['daisy', 'mum', 'rose', 'sunflower']`

* [ ] `None`

* [ ] `['daisy', 'mum', 'rose', 'sunflower', 'tiger lily']`

* [ ] `IndexError: list index out of range`

### Which of the following is not a valid approach to creating a tuple?

* [ ] `info = tuple('densuke')`

* [ ] `info = tuple(['densuke'])`

* [ ] `info = ('densuke')`

* [ ] `info = ('densuke',)`

### Given the following code snippet, which of the following is valid Python code?

```python
months = set(["Jan", "Feb", "Mar"])
ratings = [5, 4, 5, 5, 2]
dog_info = ('Arfy', 'kibble', 5)
```

* [ ] `dog_info[2] = 6`

* [ ] `months.add("Apr")`

* [ ] `ratings[5] = 3`

* [ ] `months.append("May")`

### A constructor function...

* [ ] Is the only way to make a set

* [ ] Can only create empty data structures

* [ ] Is one of a few ways to create lists, tuples, and sets

* [ ] Must be imported

### Given the following code block, which of the choices are equivalent to the expression ``my_name is your_name`` ?

```python
my_name = "Balloonicorn"
your_name = "Programmer Extraordinaire"
```

* [ ] `my_name is = your_name`

* [ ] `id(my_name) == id(your_name)`

* [ ] `my_name == your_name`

* [ ] `my_name != your_name`

## Fill in the blank

<!-- Fill in the blank by replacing the blank lines -->

```
A function _____________ is what a function takes as its parameters along
with what it returns.
```

```
Git is a _____________, whereas Github is a _____________.
```

## Long answer

### In a 2-3 sentences, describe the difference between variables in Python and variables in the C programming language.

<!-- Start your answer here! -->
