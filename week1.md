# week 1

**Curriculum:**

- Scratch
- C
- algorithms
- memory
- buggy codes
- data structures
- python
- databases
- third-party frameworks

### Computational thinking

Essentially, computer programming is about taking some input and creating some output - thus solving a problem. What happens in between the input and output, what we could call a black box, is the focus of this course.

![image](https://github.com/pol-dev-shinroo/cs50-harvard/assets/102004753/50eb6556-ca3e-4df0-ac04-35adf1c56cab)

For instance, we want to take attendance for a class. How we do this, which approach to take, is what happens between the input and output.

```python
000 0
001 1
010 2
011 3
100 4
101 5
110 6
111 7
```

**Place values** for multi-digit binary number is useful when interpreting or calculating the **decimal equivalent** of a binary number.

```python
 2^2  2^1  2^0
  4    2    1
```

### Numeral systems

1. **Unary System**
   Numbers are represented using only one symbol
   The number 3 is represented as 'III' (three repetitions of the symbol 'I').

2. **Binary System**
   Binary is a base-2 numeral system commonly used in computing and digital systems.
   It uses two symbols, typically 0 and 1, to represent numbers. This 0s and 1s are called bits.

3. **Decimal system**
   The decimal system, also known as the base-10 system, is the most widely used numeral system in everyday life.

### Algorithms

- Approach to solving a problem.

**Example**

- finding a person in the phone book.
  ![image](https://github.com/pol-dev-shinroo/cs50-harvard/assets/102004753/08a51030-820e-418e-bb87-53cbbb0c1653)

- For binary search, where you **repeatedly divide the phone book into half**, the time taken to get to the person, will be **log2N**

### PseudoCode

Helps to think through the logic of your problem in advance.

```python
  1  Pick up phone book
  2  Open to middle of phone book
  3  Look at page
  4  If person is on page
  5      Call person
  6  Else if person is earlier in book
  7      Open to middle of left half of book
  8      Go back to line 3
  9  Else if person is later in book
  10     Open to middle of right half of book
  11     Go back to line 3
  12 Else
  13     Quit
```

- Function: lines begin with verbs (ex. pick up)
- Conditionals: if and else if
- Boolean: True or False
- Loops: "Go back to line 3"
