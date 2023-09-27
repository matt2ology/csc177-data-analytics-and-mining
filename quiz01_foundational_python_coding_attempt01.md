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

[Pennstate 1(b) .1 - What is Data](https://online.stat.psu.edu/stat857/node/31/#:~:text=Continuous%20Attribute,temperature%20of%20a%20day%2C%20etc.)

### Ratio attribute

- [x] Real Number as values
- [ ] Noise
- [ ] Mode
- [ ] Geometric Mean
- [ ] Brings challenges

> Measurements where both difference and ratio are meaningful,
> e.g. Temperature in Kelvin, Length, Counts.
>
> In statistics and data analysis, a ratio attribute is a type of quantitative
> attribute that has real numbers as values and possesses a meaningful zero
> point. Examples of ratio attributes include age, height, weight, and income.
> These attributes can be measured on a continuous scale and support meaningful
> mathematical operations like addition, subtraction, multiplication, and
> division. However, they also bring challenges in terms of handling outliers
> and dealing with zero values, which may require special consideration in data
> analysis.

### Continuous attribute

- [x] Real Number as values
- [ ] Noise
- [ ] Mode
- [ ] Geometric Mean
- [ ] Brings challenges

> A continuous attribute is a type of attribute in statistics and data analysis
> that has real numbers as values and is measured on a continuous scale.
> Examples of continuous attributes include variables like age, height, weight,
> temperature, and income. These attributes can take on any value within a
> certain range and can be measured with a high degree of precision. Continuous
> attributes are not limited to specific, discrete values like categories or integers.
>
> However, continuous attributes can also bring challenges in data analysis,
> such as dealing with outliers, selecting appropriate statistical methods, and
> addressing issues related to data distribution and assumptions.

### Higher dimensionality

- [ ] Real Number as values
- [ ] Noise
- [ ] Mode
- [ ] Geometric Mean
- [x] Brings challenges

> Higher dimensionality refers to datasets or spaces that have a large number
> of features or variables. In data analysis and machine learning, higher
> dimensionality can pose several challenges, including increased computational
> complexity, the risk of overfitting, and the curse of dimensionality. It can
> make it more challenging to visualize and interpret data and may require
> specialized techniques for analysis and dimensionality reduction.

### Nominal

- [ ] Real Number as values
- [ ] Noise
- [x] Mode
- [ ] Geometric Mean
- [x] Brings challenges

> Nominal
>> Qualitative variables that do not have a natural order,
>> e.g. Hair color, Religion, Residence zipcode of a student.
>
> Nominal is a level of measurement or a data type used to categorize data into
> distinct categories or labels that don't have any inherent numerical meaning
> or order. Nominal data is used for qualitative variables, such as colors,
> gender, types of animals, or categories of products. In nominal data, you can
> determine the mode, which is the most frequently occurring category, but you
> cannot perform mathematical operations like calculating the mean or geometric
> mean, as the categories are not numeric in nature.
>
> Dealing with nominal data can bring challenges in terms of encoding, handling
> missing values, and performing statistical analyses, as specialized methods
> are often required for these types of variables.

### Modified original attribute value

- [ ] Real Number as values
- [ ] Noise
- [ ] Mode
- [ ] Geometric Mean
- [x] Brings challenges

## Question 02 (2 pts)

In an exam the score for each question is P points if the answer is correct
and -P points (negative points) if the answer is incorrect.
The maximum total score is for 100 points. What is the total points attribute?

- [ ] Nominal
- [x] Ratio
- [ ] Interval
- [ ] Ordinal

> The total points attribute in this scenario is a **Ratio attribute**.
>
> In a ratio attribute, there is a meaningful zero point, and you can perform
> meaningful mathematical operations like addition, subtraction, multiplication,
> and division. In this case, a correct answer gives you positive points (P),
> an incorrect answer gives you negative points (-P), and the maximum total
> score is 100 points. Since there is a clear, meaningful zero point (no points)
> and you can perform arithmetic operations with these scores, it falls under
> the category of a ratio attribute.

## Question 3 (2 pts)

what is the answer to this program snippet?

```python
intlist = [1, 3, 5]
print(intlist * 3)
```

- [x] \[1, 3, 5, 1, 3, 5, 1, 3, 5\]
- [ ] \[3, 9, 15\]
- [ ] \[1, 1, 1, 3, 3, 3, 5, 5, 5\]
- [ ] \[1\*3, 3\*3, 5\*3\]

## Question 4 (1 pts)

All measurements preserve ordering and additive properties.

- [x] True
- [ ] False

> Yes, measurements are typically designed to preserve ordering
> and additive properties in many contexts.

## Question 5 (1 pts)

Calendar dates have the Ratio property.

- [ ] True
- [x] False

> Calendar dates, such as days, months, and years, do not
> inherently possess the ratio property. The ratio property, in mathematics,
> typically refers to a property where the relationship between two quantities
> is expressed as a ratio or fraction. Ratios are often used to compare two
> quantities of the same type, such as lengths, weights, or volumes.
> For example, if you have two lengths, you can express their
> ratio as a fraction, like 2:3 or 1/2.

## Question 6 (1 pts)

A Nominal attribute possesses only distinctness and order

- [ ] True
- [x] False

> A nominal attribute possesses distinctness, but it does not possess order.
> Nominal attributes are categorical attributes that represents distinct
> categories or labels, but these categories does not have inherent order
> or ranking.

## Question 7 (1 pts)

An attribute cannot be a dimension.

- [ ] True
- [x] False

> An attribute can be a dimension in context; for example, data modeling and/or
> analytics.

## Question 8 (1 pts)

An object is a sample.

- [ ] True
- [x] False

> No because one data value does not make a collection of data to be a "sample"

## Question 9 (2 pts)

Consider the program snippet and select the correct answer for the output:

```python
MItuple = ('MI', 'Michigan', 'Lansing')
CAtuple = ('CA', 'California', 'Sacramento')
TXtuple = ('TX', 'Texas', 'Austin')

states = [MItuple, CAtuple, TXtuple] # this will create a list of tuples

print(states[1][1:])
```

- [x] ('California', 'Sacramento')
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
- [x] dict_keys(\['MI', 'MN', 'TX', 'CA'\])
- [ ] dict_keys(\[MI, MN, TX, CA\])
- [ ] \['MI', 'MN', 'TX', 'CA'\]

## Question 11 (2 pts)

Consider the snippet:

```python
fruits = {'apples': 3, 'oranges': 4, 'bananas': 2, 'cherries': 10}
fruitnames = [v for (k,v) in fruits.items()]

print(fruitnames)
```

- [x] \(3, 4, 2, 10\)
- [ ] \[('apples', 3), ('bananas', 2), ('cherries', 10), ('oranges', 4)\]
- [ ] \[('apples', 3), ('oranges', 4), ('bananas', 2), ('cherries', 10)\]
- [ ] \['apples', 'oranges', 'bananas', 'cherries'\]

> List comprehension: each value `v` for every key-value pairs `(k, v)` items
> in the dictionary `fruits`
