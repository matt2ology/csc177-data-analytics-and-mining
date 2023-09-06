# Quiz 01 - Foundational and Python coding

- [Quiz 01 - Foundational and Python coding](#quiz-01---foundational-and-python-coding)
  - [Question 01 (5 pts)](#question-01-5-pts)
    - [Ratio attribute](#ratio-attribute)
    - [Continuous attribute](#continuous-attribute)
    - [Higher dimensionality](#higher-dimensionality)
    - [Nominal](#nominal)
    - [Modified original attribute value](#modified-original-attribute-value)
  - [Question 02 (2 pts)](#question-02-2-pts)
  - [Question 3 (2 pts)](#question-3-2-pts)
  - [Question 4 (1 pts)](#question-4-1-pts)
  - [Question 5 (1 pts)](#question-5-1-pts)
  - [Question 6 (1 pts)](#question-6-1-pts)
  - [Question 7 (1 pts)](#question-7-1-pts)
  - [Question 8 (1 pts)](#question-8-1-pts)
  - [Question 9 (2 pts)](#question-9-2-pts)
  - [Question 10 (2 pts)](#question-10-2-pts)
  - [Question 11 (2 pts)](#question-11-2-pts)

## Question 01 (5 pts)

### Ratio attribute

- [ ] Real Number as values
- [ ] Noise
- [ ] Mode
- [ ] Geometric Mean
- [ ] Brings challenges

### Continuous attribute

- [ ] Real Number as values
- [ ] Noise
- [ ] Mode
- [ ] Geometric Mean
- [ ] Brings challenges

### Higher dimensionality

- [ ] Real Number as values
- [ ] Noise
- [ ] Mode
- [ ] Geometric Mean
- [ ] Brings challenges

### Nominal

- [ ] Real Number as values
- [ ] Noise
- [ ] Mode
- [ ] Geometric Mean
- [ ] Brings challenges

### Modified original attribute value

- [ ] Real Number as values
- [ ] Noise
- [ ] Mode
- [ ] Geometric Mean
- [ ] Brings challenges

## Question 02 (2 pts)

In an exam the score for each question is P points if the answer is correct
and -P points (negative points) if the answer is incorrect.
The maximum total score is for 100 points. What is the total points attribute?

- [ ] Nominal
- [ ] Ratio
- [ ] Interval
- [ ] Ordinal

## Question 3 (2 pts)

what is the answer to this program snippet?

```python
intlist = [1, 3, 5]
print(intlist * 3)
```

- [ ] \[1, 3, 5, 1, 3, 5, 1, 3, 5\]
- [ ] \[3, 9, 15\]
- [ ] \[1, 1, 1, 3, 3, 3, 5, 5, 5\]
- [ ] \[1\*3, 3\*3, 5\*3\]

## Question 4 (1 pts)

All measurements preserve ordering and additive properties.
Group of answer choices

- [ ] True
- [ ] False

## Question 5 (1 pts)

Calendar dates have the Ratio property. Group of answer choices

- [ ] True
- [ ] False

## Question 6 (1 pts)

A Nominal attribute possesses only distinctness and order

- [ ] True
- [ ] False

## Question 7 (1 pts)

An attribute cannot be a dimension.

- [ ] True
- [ ] False

## Question 8 (1 pts)

An object is a sample.

- [ ] True
- [ ] False

## Question 9 (2 pts)

Consider the program snippet and select the correct answer for the output:

```python
MItuple = ('MI', 'Michigan', 'Lansing')
CAtuple = ('CA', 'California', 'Sacramento')
TXtuple = ('TX', 'Texas', 'Austin')

states = [MItuple, CAtuple, TXtuple]    # this will create a list of tuples

print(states[1][1:])
```

- [ ] ('California', 'Sacramento')
- [ ] ('Texas', 'Austin')
- [ ] ('Michigan', 'Lansing')
- [ ] ('CA', 'California', 'Sacramento')

## Question 10 (2 pts)

Consider the following snippet:

```python
abbrev = {}
abbrev['MI'] = "Michigan"
abbrev['MN'] = "Minnesota"
abbrev['TX'] = "Texas"
abbrev['CA'] = "California"

print(abbrev.keys()) 
```

- [ ] keys(\['MI', 'MN', 'TX', 'CA'\])
- [ ] dict_keys(\['MI', 'MN', 'TX', 'CA'\])
- [ ] dict_keys(\[MI, MN, TX, CA\])
- [ ] \['MI', 'MN', 'TX', 'CA'\]

## Question 11 (2 pts)

Consider the snippet:

```python
fruits = {'apples': 3, 'oranges': 4, 'bananas': 2, 'cherries': 10}
fruitnames = [v for (k,v) in fruits.items()]

print(fruitnames)
```

- [ ] (3, 4, 2, 10)
- [ ] \[('apples', 3), ('bananas', 2), ('cherries', 10), ('oranges', 4)\]
- [ ] \[('apples', 3), ('oranges', 4), ('bananas', 2), ('cherries', 10)\]
- [ ] \['apples', 'oranges', 'bananas', 'cherries'\]
