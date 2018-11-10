
<h1 style="margin-bottom: 0px;"> PG Program in ML and AI December 2018 Preprogram Preparatory Content </h1>
<h4 style="margin-top: 0px;"> Nishant Upadhyay</h4>
<h4 style="margin-top: 0px;"> Data Scientist (Infosys)</h4>
<h4 style="margin-top: 0px;"> Pune</h4>

<h2 style="margin-top: 0px;"> Module 2 Introduction to Python</h2>
<h3 style="margin-top: 0px;"> Session 2 Data Structures in Python</h3>

Study sources:

Beginners level:

[Think Python](http://greenteapress.com/wp/think-python-2e/)

[The hitchhiker's guide to Python](https://docs.python-guide.org/intro/learning/)

[A byte of Python](https://python.swaroopch.com/)

Advanced Learner's level:

[Problem-solving with algorithms ](http://interactivepython.org/runestone/static/pythonds/index.html)



### Getting Started — Installation

Anaconda is an open-source distribution that simplifies package management and deployment. Package versions are managed by the package management system 'Conda'.

Advantages of using Anaconda

+ Easy to manage and get started with most requirements for ML/AI problems

+ Anaconda comes with many libraries such as NumPy, OpenCV, SciPy, PyQt, the Spyder IDE, etc.

 

Anaconda can be downloaded from [anaconda.org](https://www.anaconda.com/download/) and can be installed like any other normal software. There is no need to download Python separately; the Anaconda installer will do this for you.

### Jupyter Notebook

You’ll use the Jupyter IPython Notebook as the main environment for writing Python code throughout this program. The main advantage of using Jupyter Notebook is that you can write both code and normal text (using the Markdown format in Jupyter) in the notebooks. These notebooks are easy to read and share and can even be used to present your work to others. Here’s a brief overview of [Jupyter Notebook](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/index.html).

The document given below provides instructions for installing Python and the Jupyter Notebook using Anaconda.

[ installing Python and the Jupyter Notebook using Anaconda](https://cdn.upgrad.com/UpGrad/temp/187b8549-50bc-49ae-9771-f6a54b0a56ae/Installing+Python.1.pdf)

[Jupyter Notebook quick start guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/index.html)

[Jupyter Notebook Magic Commands](https://ipython.readthedocs.io/en/stable/interactive/magics.html)

## Introduction to Jupyter Notebook

Jupyter IPython Notebook as the main environment for writing Python code throughout this program. The main advantage of using Jupyter Notebook is that you can write both code and normal text (using the Markdown format in Jupyter) in the notebooks. These notebooks are easy to read and share, and can even be used to present your work to others. 


```python
# The blue color outside the cell represents command mode.
# And the green color indicates edit mode.
# Press 'Esc' to get into command mode.
# Press 'Enter' to go back into edit mode.
# Press 'P' to view the list of all available commands.
```


```python
# This is a coding cell.
# Let's write your first Python program here.

Name = input("Enter your name: ")
print("Hello,", Name)

# Press 'Shift + Enter' to execute the cell.
```

    Enter your name: Nishant
    Hello, Nishant



```python
# Writing comments in a code cell can sometimes creates confusion. Jupyter notebook works both as a notebook and a coding console. 
# To write explanatory texts, you can use a markdown cell which enables you to format your comments well to create a more
# readable code.

# Let's now learn about markdown cells, then.
# Press 'M' in command mode to convert a code cell to a Markdown cell.
```

This is a Markdown Cell. Double click on a markdown cell or press 'Enter' to see how it's written. And again, press 'Shift + Enter' to execute the cell.

Let's further learn about the various customizations in a markdown cell to create a more readable and understandable code.

# This is a title
## This is a heading
### This is a subheading
#### This is as small as a heading can get
##### The fifth hash makes it Italic. Wow!

## Formatting in Markdown cells

### Emphasis

__"This will appear bold."__

**"So will this."**

_"Just one dash makes it italic."_

*"And one star on either side as well."*

***"This one's both bold and italic."***


### Monospace Fonts

Use a back single quotation mark (\`) to get monospace fonts.

`This text will appear in monospace font.`
`Python is a beautiful language.`


### Line Breaks

Sometimes in the markdown cells, you don't get a line break where you want simply by pressing enter. In such cases use `<br>` to get a manual line break.

I want a line break here.
But I don't get it. :/
<br>
So I used a manual line break <br>
There we go! :)

### Indenting

Use `&gt;` to indent your text.

This is the first line
&gt; This indents the second line.
&gt;&gt; This further indents it.
&gt;&gt;&gt; And this goes on and on.

### Bullets and Numbering

-  A dash followed by two spaces, i.e. `'-  '` creates a bullet.
    -  Pressing a tab before doing the above creates a sub-bullet.

1. Start with a simple `1. ` (1 followed by a dot and a space) to get a numbered list.
2. And keep doing it for further numbers.
    1. Again, just a tab for the sub-bullet.

### Coloring
 
-  <font> This text will be blue. </font>
-  <font> I hate this color! </font>

### Adding an Image

You can add an image from the web by using `<img src="image_path">`

Example:
<img src="https://blog.upgrad.com/wp-content/uploads/2016/06/logo.png">

### LaTeX Equations

Jupyter notebook also supports LaTeX equations. Use a `$` on either side to write a LaTeX equation.

The below example is just a hypothetical equation to explain how you can write LaTeX equations in Jupyter notebook. 
<br>

$(\frac{a_1}{a_2} + \frac{a_3}{a_4})^2 = a_5^3$

Go through this [link](https://en.wikibooks.org/wiki/LaTeX/Mathematics) if you want to learn the LaTeX syntax. 

### Basic Commands

That was all about markdown cells. Now let us take a look at the most useful commands that you require everyday while coding in the Jupyter notebook.

#### Command Mode Shortcuts
-  `Esc`: To go into command mode
-  `Enter`: To go back to edit mode
-  `M`: To convert a cell to a markdown cell
-  `Y`: To convert a cell back to a code cell
-  `A`: To insert new cell above
-  `B`: To insert new cell below
-  `D + D`: To delete cell
-  `Z`: Undo last operation
-  `F`: To find and replace on your code
-  `Shift + Up/Down`: To select multiple cells
-  `Space`: Scroll notebook downwards
-  `Shift + Space`: Scroll notebook upwards

#### Edit Mode Shortcuts
-  `Shift + Enter`: To execute the code in the current cell and go to the next cell
-  `Alt + Enter`: To execute the code in the current cell and insert new cell below
-  `Shift + Tab`: To get a brief documentation of the object that you have just typed in the coding cell
-  `Ctrl + Shift + -`: To split the cell at cursor
-  `Shift + M`: To merge selected cells

Apart from this, you can also use `H` to open the list of keyboard shortcuts and even add new shortcuts or customize the existing shorcuts according to your personal requirements.

#### Qs 1

Surrounding the text with which of the following elements will give you the monospace font in a markdown cell?  
Ans:A back single quotation mark (`) on either side of the text converts it into monospace.

#### Qs 2

`Jupyter Notebook Commands`
Which of the following commands will execute the current cell and move the navigator to the next cell?  
Ans:`Shift + Enter` executes the current cell and moves the navigator to the next cell.

### The Basics

Python is a general-purpose programming language that was named after [Monty Python](https://en.wikipedia.org/wiki/Monty_Python). It is simple and incredibly readable since it closely resembles the English language. But still, why should you use Python? Python is a language that has a use in nearly every domain you can think of. Its [official website](https://www.python.org/about/apps/) will give you an overview of this. In addition to this, its simplicity, as well as the way it ensures tasks can be performed using fewer lines of code, is encouraging many developers across the world to take it up. 

#### Some basic data types and also look at some basic operations that can be carried out in Python


```python
print("This is my first line of code in python")
```

    This is my first line of code in python



```python
print("Hello\nThis is in the next line")
```

    Hello
    This is in the next line



```python
a = 6
b = 7
print(a + b)  

print(a - b) 
print(a * b) 
print(a / b)
print(a // b)
print(a % b) 
print(a ** b)
```

    13
    -1
    42
    0.8571428571428571
    0
    6
    279936



```python
#BEDMAS
print(4 * 5 - 9 + 6 / 7)
```

    11.857142857142858



```python
inc = 9
inc += 1
print(inc)
inc -= 1
print(inc)
```

    10
    9



```python
#Logical
print(3 < 4)
print(True and False) 
print(True or False)
print(a!=b) 
print(True and not False)
```

    True
    False
    True
    True
    True



```python
small = "i am upper cased"
print(small.upper())

large = "I AM LOWER CASED"
print(large.lower())

```

    I AM UPPER CASED
    i am lower cased



```python
some_sentence = "There is a space at the end    "
print(some_sentence)
print(some_sentence.rstrip())

```

    There is a space at the end    
    There is a space at the end



```python
increment = '4%'
print(increment.rstrip('%')) 
```

    4



```python
start = "   There is space at the start"
print(start)
print(start.lstrip())
```

       There is space at the start
    There is space at the start



```python
spaces = "   Trim whitespaces  "
print(spaces)
print(spaces.strip())
```

       Trim whitespaces  
    Trim whitespaces



```python
num_with_chars = '*444#'
print(num_with_chars.rstrip('#').lstrip('*'))
```

    444



```python
### Python_1

##Qs: Remove the leading spaces from the string  input_str = '         This is my first code'

# Reading the input as a string; ignore the following two lines
import ast, sys
input_str = sys.stdin.read()

# Write your code here
input_str = '         This is my first code'  
print(input_str.lstrip()) ## removing leading spaces


```

    This is my first code



```python
val = "2 apples"
no_of_apples = val[0] 
print('number of apples is', no_of_apples)

```

    number of apples is 2



```python
what = val[2:]
print(what)
```

    apples



```python
#slicing by specifying start and end index
print(val[2:5])

```

    app



```python
batch = "5 oranges 3 monkeys n"
fruits = batch[ :9]
print(fruits)
```

    5 oranges



```python
print(batch[ :-2])
```

    5 oranges 3 monkeys



```python
animals = batch[10:-2]
print(animals)
```

    3 monkeys



```python
nums = '123456789'
even_nums = nums[1::2]
print(even_nums)
```

    2468



```python
odd_nums = nums[0::2]
print(odd_nums)
```

    13579



```python
odd_nums_again = nums[ :: 2]

```


```python
first_name = "Monty"
last_name = 'Python'
```


```python
name = first_name + " " + last_name
print(name)
```

    Monty Python



```python
age = 30
my_age = ("I am "+ str(age) + " years old")
print(my_age)
```

    I am 30 years old



```python
My_age = "I am {0} years old".format(age) 
print(My_age)
```

    I am 30 years old



```python
A = "Data"
B = "Analysis"
C = "Pandas"

print("{0} {1} using {2}".format(A,B,C))

```

    Data Analysis using Pandas



```python
#concat and update
name += ' ' + my_age
print(name)
```

    Monty Python I am 30 years old



```python
## Questions:1/1

#Split the string input_str = 'Kumar_Ravi_003' 
#to the person's second name, first name and unique customer code.
#In this example, second_name= 'Kumar', first_name= 'Ravi', customer_code = '003'.


input_str = 'Kumar_Ravi_003'

first_name = input_str[6:10]
second_name = input_str[0:5]
customer_code = input_str[11:]
print(first_name)
print(second_name)
print(customer_code)

```

    Ravi
    Kumar
    003


# Questions:1/5

Arithmetic Operators  
Read [this](https://docs.python.org/3/tutorial/introduction.html#using-python-as-a-calculator) document, and answer the following question.

Qs:What is the difference between '/' and '//'?  
Ans:'/' performs classic division and returns a float value while '//' perform floor division and discards the fractional part.

Qs:The '%' operator returns the ________?   
Ans:'%' returns the remainder value. Forex. 3%2 =1.

Qs:What is the use of '\n'?     
Ans:\n produces a new line with print() while without print(), \n is included in the output.

Qs:How will you extract Python from the string word "I love Python programming"? (More than one answers may be correct.)    
Ans:word[7:13]   
The index value of P in Python is 7 and the index value of N in Python is 12, so while indexing we include the starting value while the ending value is not included. So word[7:13] will give Python, while word[7:12] will give Pytho.

word[-18:-12]    
Note that since -0 is the same as 0, negative indices start from -1.


```python
word="I love Python programming"
word[7:13]
```




    'Python'




```python
word[-18:-12]
```




    'Python'




```python
#String Function
#What is the output of the python code 'len('Python')'?
len('Python')
```




    6



Yes, Right answer. P = 1, Y=2, T=3, H=4, O=5, N=6

Instead of using commands, you can also use simple mathematical operators between sets to perform the various operations. Go through the below link to understand how:

 + [Operations on Sets](https://docs.python.org/3/tutorial/datastructures.html#sets)

# Data Structures

Data structures are a special way of storing and accessing data. Every programming language has some built-in data structures such as arrays, lists, dictionaries etc.

Data structures refer to the collection or group of data in a particular structure.

## Lists

Lists are the most commonly used data structure. Think of it as a sequence of data that is enclosed in square brackets and data are separated by a comma. Each of these data can be accessed by calling it's index value.

Lists are declared by just equating a variable to '[ ]' or list. We can use lists to hold an ordered sequence of values.


```python
initial_list = []
print(initial_list)
```

    []


Lists can contain different types of variable, even in the same list.


```python
DA_languages = ['R','Python', 'SAS', 'Scala', 42]
print(DA_languages)
```

    ['R', 'Python', 'SAS', 'Scala', 42]



```python
print(DA_languages[0])
```

    R



```python
print(DA_languages[1:3])

```

    ['Python', 'SAS']



```python
print(DA_languages[0:2])
```

    ['R', 'Python']



```python
print(DA_languages[-1])
```

    42



```python
print(DA_languages[2:])
```

    ['SAS', 'Scala', 42]



```python
print(DA_languages[ : -3])
```

    ['R', 'Python']


# List Methods

| Method Name | Use | Explanation |
|----|---|
| append | alist.append(item) | Adds a new item to the end of a list |
| insert	| alist.insert(i,item) |	Inserts an item at the ith position in a list |
|pop	|alist.pop()	|Removes and returns the last item in a list|
|pop|	alist.pop(i)|	Removes and returns the ith item in a list|
|sort|	alist.sort()|	Modifies a list to be sorted|
|reverse|	alist.reverse()|	Modifies a list to be in reverse order|
|del|	del alist[i]|	Deletes the item in the ith position|
|index|	alist.index(item)|	Returns the index of the first occurrence of item|
|count|	alist.count(item)|	Returns the number of occurrences of item|
|remove|	alist.remove(item)|	Removes the first occurrence of item|

In contrast with tuples, lists are variable-length and their contents can be modified.in-placeLists are mutable; their contents can change as more statements are interpreted.

### Concatenating and combining lists  
Similar to tuples, adding two lists together with + concatenates them:


```python
[4, None, 'foo'] + [7, 8, (2, 3)]
```




    [4, None, 'foo', 7, 8, (2, 3)]



**faster than the concatenative alternative**

`everything = []
for chunk in list_of_lists:
    everything.extend(chunk)`


```python
DA_languages = ['R','Python', 'SAS', 'Scala', 42]
DA_languages.append('Java')
print(DA_languages)
```

    ['R', 'Python', 'SAS', 'Scala', 42, 'Java']



```python
DA_languages.pop()
```




    'Java'




```python
DA_languages.pop(0) 
print(DA_languages)
```

    ['Python', 'SAS', 'Scala', 42]



```python
DA_languages.pop(1)
print(DA_languages)
```

    ['Python', 'Scala', 42]



```python
DA_languages.append('R')
DA_languages.remove('R')
print(DA_languages)

```

    ['Python', 'Scala', 42]



```python
print(DA_languages.append('R'))

```

    None


- The above below creates two different references (named `DA_languages` and `new_list`) to the *same* value `['R','Python', 'SAS', 'Scala', 42]`

- Because lists are mutable, changing them can have side-effects on other variables.

- If we append something to `DA_languages` what will happen to `new_list`?


```python
new_list = DA_languages
DA_languages.append('Java')
print(new_list)

```

    ['Python', 'Scala', 42, 'R', 'Java']



```python
print(id(DA_languages))
```

    140320027770376



```python
print(id(new_list))
```

    140320027770376



```python
new_list = DA_languages[:]
print(id(new_list))
```

    140320029066824



```python
another_list = DA_languages.copy()
print(id(another_list))
```

    140320027896968



```python
myList = [1,2,3,4]
A = [myList]*3
print(A)
myList[2]=45
print(A)
```

    [[1, 2, 3, 4], [1, 2, 3, 4], [1, 2, 3, 4]]
    [[1, 2, 45, 4], [1, 2, 45, 4], [1, 2, 45, 4]]



```python
a_sentence = "Hi Saif, this is to inform you that I'm not well today."
```


```python
words_in_sentence = a_sentence.split() 
print(words_in_sentence)
```

    ['Hi', 'Saif,', 'this', 'is', 'to', 'inform', 'you', 'that', "I'm", 'not', 'well', 'today.']



```python
a_mail = "Hi Saif, this is to inform you that I'm not well today. I won't be coming to office, but I'm available on call. Thanks."
```


```python
sentences_in_mail = a_mail.split('.')
print(sentences_in_mail)
```

    ["Hi Saif, this is to inform you that I'm not well today", " I won't be coming to office, but I'm available on call", ' Thanks', '']



```python
mail = " ".join(sentences_in_mail)
print(mail)
```

    Hi Saif, this is to inform you that I'm not well today  I won't be coming to office, but I'm available on call  Thanks 



```python
mail_new = " & ".join(sentences_in_mail)
print(mail_new)
```

    Hi Saif, this is to inform you that I'm not well today &  I won't be coming to office, but I'm available on call &  Thanks & 



```python
my_list = ["Hi"]
print(my_list*5)
```

    ['Hi', 'Hi', 'Hi', 'Hi', 'Hi']



```python
names = ['Earth','Air','Fire','Water']

## Lets check if the items 'Air' and 'Wind' are present in the list or not

'Wind' in names
```




    False




```python
'Air' in names
```




    True



## Sorting

You can sort a list in-place (without creating a new object) by calling its `sort` function:


```python
nums = [2,6,9,3,2,1]
print(len(nums))
```

    6



```python
nums.sort()
nums
```




    [1, 2, 2, 3, 6, 9]



### sorted

The sorted function returns a new sorted list from the elements of any sequence:


```python
print(sorted(nums))
```

    [1, 2, 2, 3, 6, 9]


sort has a few options that will occasionally come in handy. One is the ability to pass a secondary sort `key` —that is, a function that produces a value to use to sort the objects.


```python
b = ['saw', 'small', 'He', 'foxes', 'six']
b.sort(key=len)
b
```




    ['He', 'saw', 'six', 'small', 'foxes']




```python
names = ['Earth','Air','Fire','Water']

names.sort()
print(names)
names.sort(reverse=True)
print(names)
```

    ['Air', 'Earth', 'Fire', 'Water']
    ['Water', 'Fire', 'Earth', 'Air']



```python
print(max(nums))
```

    9



```python
print(min(nums))
```

    1


In a list with elements as string, **max( )** and **min( )** is applicable. **max( )** would return a string element whose ASCII value is the highest and the lowest when **min( )** is used. Note that only the first index of each element is considered each time and if they value is the same then second index considered so on and so forth.


```python
mlist = ['bzaa','ds','nc','az','z','klm']
print(max(mlist))
print(min(mlist))
```

    z
    az


Here the first index of each element is considered and thus z has the highest ASCII value thus it is returned and minimum ASCII is a. But what if numbers are declared as strings?


```python
nlist = ['1','94','93','1000']
print(max(nlist))
print(min(nlist))
```

    94
    1


Even if the numbers are declared in a string the first index of each element is considered and the maximum and minimum values are returned accordingly.

But if you want to find the **max( )** string element based on the length of the string then another parameter 'key=len' is declared inside the **max( )** and **min( )** function.


```python
names = ['Earth','Air','Fire','Water']
print(max(names, key=len))
print(min(names, key=len))
```

    Earth
    Air


## Reversing


```python
print(names)
print(list(reversed(names)))
```

    ['Water', 'Fire', 'Earth', 'Air']
    ['Air', 'Earth', 'Fire', 'Water']



```python
nest = [[1, 2, 3, 4], [ 5, 6, 7], [8, 9, 10]]

print(nest[1])

```

    [5, 6, 7]



```python
print(nest[0][1])
```

    2



```python
print(nest[0:2])
```

    [[1, 2, 3, 4], [5, 6, 7]]



```python
##### Questions:1/1

#Remove SPSS from input_list=['SAS', 'R', 'PYTHON', 'SPSS'] and add 'SPARK' in its place.

input_list=['SAS', 'R', 'PYTHON', 'SPSS']
input_list.pop(3)
input_list.append('SPARK')
print(input_list)

```

    ['SAS', 'R', 'PYTHON', 'SPARK']



```python
## Aliter

import ast,sys
input_list =['SAS', 'R', 'PYTHON', 'SPSS']
input_list.remove('SPSS')
input_list.append('SPARK')
print(input_list)
```

    ['SAS', 'R', 'PYTHON', 'SPARK']


#### string to list conversion

Description 

A string can be converted into a list by using the list() function.


```python
list('UpGrad')
```




    ['U', 'p', 'G', 'r', 'a', 'd']



 

Questions:Convert a string input_str = 'I love Data Science &amp; Python' to a list by splitting it on ‘&amp;’. The sample output for this string will be:  
['I love Data Science ', ' Python']


```python
input_str = 'I love Data Science & Python'

input_str_split=input_str.split('&')
print(input_str_split)
```

    ['I love Data Science ', ' Python']


List of words? Let's try using .split() which splits a string on the basis of spaces.


```python
test_string = 'I will now convert this to a list of words'
print(test_string.split())
```

    ['I', 'will', 'now', 'convert', 'this', 'to', 'a', 'list', 'of', 'words']


What about splitting on something else? Like a period? and then try to make it like a normal sentence using .join?


```python
string_to_split = 'Hi.Can.we.get.rid.of.the.periods.here'
list_var = string_to_split.split('.')
print(list_var)
```

    ['Hi', 'Can', 'we', 'get', 'rid', 'of', 'the', 'periods', 'here']



```python
#Let's join it back with spaces and reassign it to the original name
string_to_split = " ".join(list_var)
print(string_to_split)
```

    Hi Can we get rid of the periods here



```python
#Let's do it as a one-liner
string_to_split = 'Hi.Can.we.get.rid.of.the.periods.here'
out =  " ".join(string_to_split.split('.'))
print(out)
```

    Hi Can we get rid of the periods here


### List to String

Description

Qs:Convert a list ['Pythons syntax is easy to learn', 'Pythons syntax is very clear'] to a string using ‘&amp;’. The sample output of this string will be:   
`Pythons syntax is easy to learn &amp; Pythons syntax is very clear`


```python
input_str=['Pythons syntax is easy to learn', 'Pythons syntax is very clear']

string_1 = ' & '.join(input_str)
print(string_1)
```

    Pythons syntax is easy to learn & Pythons syntax is very clear


#### Nested List  

Description  
Qs:Extract `Python` from a nested list input_list =  [['SAS','R'],['Tableau','SQL'],['Python','Java']]


```python
input_list = [['SAS','R'],['Tableau','SQL'],['Python','Java']]
    
answer = input_list[2][0]
print(answer)

```

    Python


# State and identity

- The state referred to by a variable is *different* from its identity.

- To compare *state* use the `==` operator.

- To compare *identity* use the `is` operator.

- When we compare identity we check equality of references.

- When we compare state we check equality of values.



```python
X = [1, 2]
Y = [1]
Y.append(2)
```


```python
X == Y
```




    True




```python
X is Y
```




    False




```python
Y.append(3)
X
```




    [1, 2]



## List  Slicing

Indexing was only limited to accessing a single element, Slicing on the other hand is accessing a sequence of data inside the list. In other words "slicing" the list.

Slicing is done by defining the index values of the first element and the last element from the parent list that is required in the sliced list. It is written as parentlist[ a : b ] where a,b are the index values from the parent list. While the element at the start index is included, the stop index is not included.If a or b is not defined then the index value is considered to be the first value for a if a is not defined and the last value for b when b is not defined.

#### List Slicing

Read [this document](https://docs.python.org/3/tutorial/introduction.html#lists), and answer the following question.

Given a non-empty list 'names', which of the following statements would extract the first three elements from the list?(More than one answer may be correct.)


```python
names=['nishant','simant','motu','dad','mom']

print(names[:3])  ## If we leave the starting index value, it will be taken as zero. So in this case names[:3] will be equivalent to names[0:3].
print(names[0:3]) # names[0:3] will return values with indexes 0, 1, 2.
```

    ['nishant', 'simant', 'motu']
    ['nishant', 'simant', 'motu']



```python
num_range = [0,1,2,3,4,5,6,7,8,9]
print(num_range[0:4])
print(num_range[4:])
```

    [0, 1, 2, 3]
    [4, 5, 6, 7, 8, 9]


### Copying a list  
Most of the new python programmers commit this mistake. Consider the following,


```python
lista= [2,1,4,3]
```


```python
listb = lista
print(listb)
```

    [2, 1, 4, 3]


Here, We have declared a list, lista = [2,1,4,3]. This list is copied to listb by assigning it's value and it get's copied as seen. Now we perform some random operations on lista.


```python
lista.pop()
print(lista)
lista.append(9)
print(lista)
```

    [2, 1, 4]
    [2, 1, 4, 9]



```python
print(listb)
```

    [2, 1, 4, 9]


listb has also changed though no operation has been performed on it. This is because you have assigned the same memory space of lista to listb. So how do fix this?

If you recall, in slicing we had seen that parentlist[a:b] returns a list from parent list with start index a and end index b and if a and b is not mentioned then by default it considers the first and last element. We use the same concept here. By doing so, we are assigning the data of lista to listb as a variable.


```python
lista = [2,1,4,3]
listb = lista[:]
print(listb)
lista.pop()
print(lista)
lista.append(9)
print(lista)
```

    [2, 1, 4, 3]
    [2, 1, 4]
    [2, 1, 4, 9]



```python
print(listb)
```

    [2, 1, 4, 3]


Take a look at the next block of code to get familiar with the list methods


```python
myList = [1024, 3, True, 6.5]
myList.append(False)
print(myList)
myList.insert(2,4.5)
print(myList)
print(myList.pop())
print(myList)
print(myList.pop(1))
print(myList)
myList.pop(2)
print(myList)
myList.sort()
print(myList)
myList.reverse()
print(myList)
print(myList.count(6.5))
print(myList.index(4.5))
myList.remove(6.5)
print(myList)
del myList[0]
print(myList)
```

    [1024, 3, True, 6.5, False]
    [1024, 3, 4.5, True, 6.5, False]
    False
    [1024, 3, 4.5, True, 6.5]
    3
    [1024, 4.5, True, 6.5]
    [1024, 4.5, 6.5]
    [4.5, 6.5, 1024]
    [1024, 6.5, 4.5]
    1
    2
    [1024, 4.5]
    [4.5]


#### List Casting

Qs:If word = ['1','2','3','4'], what will be the output of the following code?

word[ : ] = [ ] 
print(word)


```python
word = ['1','2','3','4']
word[ : ] = [ ] 
print(word)
```

    []


We are indexing all the elements of the list word to an empty list hence the final output will be an empty list. So this method can also be used to delete all the items from a list.

## List Indexing

- Lists can be indexed using square brackets to retrieve the element stored in a particular position.  
- Indexing is exactly similar to indexing in strings except that indexing in lists returns the entire item at that position whereas in strings, the character at that position is returned


### negative indexing



```python
from IPython.display import Image
Image(filename='pictures/neg.PNG',width=700,height=200)
```




![png](output_159_0.png)



##### List Indexing

Suppose list_1 is [2, 33, 222, 14, 25]. What is list_1[-1]?


```python
list_1= [2, 33, 222, 14, 25]
list_1[-1]
```




    25



Index value -1 returns the last element. If list_2 = ['a', 'b', 'c', 'd'] then list_2[-2] will be 'c'.

##### List Indexing 2

Suppose list_1 is [2, 33, 222, 14, 25]. What is list_1[-3]?


```python
list_1= [2, 33, 222, 14, 25]
list_1[-3]
```




    222



Index value -3 returns the third-last element. If list_2 = ['a', 'b', 'c', 'd'] then list_2[-2] will be 'c'.

### Built-in Sequence Functions  
Python has a handful of useful sequence functions that you should familiarize yourself
with and use at any opportunity


### enumerate

It’s common when iterating over a sequence to want to keep track of the index of the current item. A do-it-yourself approach would look like:

    `i = 0  
    for value in collection:  
      #do something with value  
       i += 1`
   
Since this is so common, Python has a built-in function, enumerate, which returns a sequence of (i, value) tuples:

    `for i, value in enumerate(collection):
        #do something with value`
    
When you are indexing data, a helpful pattern that uses enumerate is computing a dict mapping the values of a sequence (which are assumed to be unique) to their locations in the sequence:


```python
some_list = ['foo', 'bar', 'baz']
mapping = {}
for i, v in enumerate(some_list):
    mapping[v] = i
    
mapping
```




    {'bar': 1, 'baz': 2, 'foo': 0}



### zip

zip **“pairs”** up the elements of a number of lists, tuples, or other sequences to create a list of tuples:


```python
seq1 = ['foo', 'bar', 'baz']
seq2 = ['one', 'two', 'three']

zipped = zip(seq1, seq2)
list(zipped)
```




    [('foo', 'one'), ('bar', 'two'), ('baz', 'three')]




```python
## A very common use of zip is simultaneously iterating over multiple sequences, possibly also combined with enumerate:
for i, (a, b) in enumerate(zip(seq1, seq2)):
    print('{0}: {1}, {2}'.format(i, a, b))
```

    0: foo, one
    1: bar, two
    2: baz, three


Given a “zipped” sequence, zip can be applied in a clever way to “unzip” the sequence. Another way to think about this is onverting a list of rows into a list of columns. The syntax, which looks a bit magical, is:


```python
pitchers = [('Nolan', 'Ryan'), ('Roger', 'Clemens'),('Schilling', 'Curt')]
first_names, last_names = zip(*pitchers)
print(first_names)
print(last_names)
```

    ('Nolan', 'Roger', 'Schilling')
    ('Ryan', 'Clemens', 'Curt')


##### Additional Reading

+ [Python data structures](https://docs.python.org/3/tutorial/datastructures.html)
+ [Problem-solving with algorithms](http://interactivepython.org/runestone/static/pythonds/Introduction/GettingStartedwithData.html#built-in-collection-data-types)

## Tuples

Tuples are data structures that are similar to lists in all aspects except in the way they are
declared and how much they allow themselves to be modified. **A tuple once created
cannot be modified.**


- Tuples are another way to combine different values.

- The combined values can be of different types.

- Like lists, they have a well-defined ordering and can be indexed.

- To create a tuple in Python, use round brackets instead of square brackets

As you saw in the previous segment, lists can be changed, and sometimes when you're
storing important information in a list and using it somewhere else in your code, you run
the risk of accidentally modifying the list and losing data or corrupting it. Tuples help you
solve this problem.

A tuple is a fixed-length, immutable sequence of Python objects. The easiest way to
create one is with a comma-separated sequence of values:

`In [1]: tup = 4, 5, 6
In [2]: tup
Out[2]: (4, 5, 6)`


```python
from IPython.display import Image
Image(filename='pictures/3.PNG')
```




![png](output_175_0.png)




```python
first_tuple = ("Monty Python", 30, "Baker Street", 5.8)
print(first_tuple[0])

```

    Monty Python



```python
city_tuple = ("Mumbai", 18.9949521, 72.8141853) 
print(city_tuple)
```

    ('Mumbai', 18.9949521, 72.8141853)



```python
new_tuple = city_tuple
print(new_tuple)
```

    ('Mumbai', 18.9949521, 72.8141853)


## Tuples are immutable

- Unlike lists, tuples are *immutable*.  Once we have created a tuple we cannot add values to it.


```python
new_tuple[1] = 13.8877
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-4-44a3e32d1d19> in <module>()
    ----> 1 new_tuple[1] = 13.8877
    

    TypeError: 'tuple' object does not support item assignment



```python
b = city_tuple[:-1]
print(b)
print(len(b))
```

    ('Mumbai', 18.9949521)
    2



```python
## convert any sequence or iterator to a tuple by invoking `tuple`

c = list(b)
print("c is: {0}".format(c))
c= tuple(c)
print("c is now a tuple: {0}".format(c))
```

    c is: ['Mumbai', 18.9949521]
    c is now a tuple: ('Mumbai', 18.9949521)


Tuples are similar to lists but only big difference is the elements inside a list can be changed but in tuple it cannot be changed. Think of tuples as something which has to be True for a particular something and cannot be True for no other values. For better understanding, let's use the **divmod()** function.


```python
xyz = divmod(10,3)
print(xyz)
print(type(xyz))
```

    (3, 1)
    <class 'tuple'>


Here the quotient has to be 3 and the remainder has to be 1. These values cannot be changed whatsoever when 10 is divided by 3. Hence divmod returns these values in a tuple.

**If you want to directly declare a tuple it can be done by using a comma at the end of the data.**


```python
27,
```




    (27,)



27 when multiplied by 2 yields 54, But when multiplied with a tuple the data is repeated twice.


```python
2*(27,)
```




    (27, 27)



Values can be assigned while declaring a tuple. It takes a list as input and converts it into a tuple or it takes a string and converts it into a tuple.


```python
tup3 = tuple([1,2,3])
print(tup3)
tup4 = tuple('Hello')
print(tup4)
```

    (1, 2, 3)
    ('H', 'e', 'l', 'l', 'o')


**Multiplying a tuple by an integer, as with lists, has the effect of concatenating together that many copies of the tuple**


```python
('foo', 'bar') * 4
```




    ('foo', 'bar', 'foo', 'bar', 'foo', 'bar', 'foo', 'bar')



## Slicing  
*Slicing is similar to lists*


```python
print(tup3[1])
tup5 = tup4[:3]
print(tup5)
```

    2
    ('H', 'e', 'l')


**A common use of variable unpacking is iterating over sequences of tuples or lists**


```python
seq = [(1, 2, 3), (4, 5, 6), (7, 8, 9)]
for a, b, c in seq:
    print('a={0}, b={1}, c={2}'.format(a, b, c))
```

    a=1, b=2, c=3
    a=4, b=5, c=6
    a=7, b=8, c=9


## Built In Tuple functions  
**count()** function counts the number of specified element that is present in the tuple.  
**index()** function returns the index of the specified element. If the elements are more than one then the index of the first element of that specified element is returned


```python
example = ("Mumbai","Chennai","Delhi","Kolkatta","Mumbai","Bangalore")
print(example.count("Mumbai"))

print(example.index("Delhi"))
```

    2
    2


### Qs

Tuple

Description  

Add the element ‘Python’ to a tuple `input_tuple = ('Monty Python', 'British', 1969)`. Since tuples are immutable, one way to do this is to convert the tuple to a list, add the element, and convert it back to a tuple.


```python

input_tuple = ('Monty Python', 'British', 1969)
c=list(input_tuple)
c.append("Python")
tuple_2=tuple(c)
print(tuple_2)
```

    ('Monty Python', 'British', 1969, 'Python')


### Tuple Methods

1: Can a tuple consist of a list as an element?   
Ans:Yes.**A tuple can contain mutable objects.**



```python
# If an object inside a tuple is mutable, such as a list, you can modify it in-place:
tup = tuple(['foo', [1, 2], True])
tup[1].append(3)
tup
```




    ('foo', [1, 2, 3], True)




```python
### 2:Suppose t = (1, 2, 4, 3). Which of the following statements will result in an error?
t = (1, 2, 4, 3)
print(t[3])
print(t[1:3])
print(len(t))
t[3] = 5
#Ans Tuples cannot be modified.
```

    3
    (2, 4)
    4



    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-24-1580232a654d> in <module>()
          4 print(t[1:3])
          5 print(len(t))
    ----> 6 t[3] = 5
          7 #Ans Tuples cannot be modified.


    TypeError: 'tuple' object does not support item assignment



```python
### 3:Which of the following is a Python tuple?
print(type((1,2,3)))
print(type({1,2,3}))
print(type([1,2,3]))
```

    <class 'tuple'>
    <class 'set'>
    <class 'list'>


## Dictionaries

The first thing that comes to mind when you hear about dictionaries is the Oxford dictionary, where you can look up meanings of words. So, you can imagine how dictionaries work. **A dictionary is a collection of words along with their meanings or simpler explanations.**

At a broader level, you could call a dictionary `a mapping of words with their synonyms or meanings`. A more common
name for it is `_hash map or associative array_`.

Dictionaries are more used like a database because here you can index a particular sequence with your user defined string. To define a dictionary, equate a variable to { } or dict()

It is a flexibly sized collection of `key-value` pairs, where `key` and `value` are Python objects. One approach for creating one is to use `curly braces {}` and `colons` to separate keys and values:

`empty_dict = {}
d1 = {'a' : 'some value', 'b' : [1, 2, 3, 4]}
d1
--&gt;{'a': 'some value', 'b': [1, 2, 3, 4]}`



```python
from IPython.display import Image
Image(filename='pictures/2.PNG') 
```




![png](output_207_0.png)




```python
empty_dictionary = {}
print(type(empty_dictionary))

first_dict = {}
second_dict = dict()
print(type(first_dict), type(second_dict))
```

    <class 'dict'>
    <class 'dict'> <class 'dict'>


## Dictionary Operators


| Operator | Use | Explanation |
|----|---|
| [ ] | myDict[k] |Returns the value associated with k, otherwise its an error |
| in	| key in adict |	Returns True if key is in the dictionary, False otherwise |
| del	|del adict[key]	|Removes the entry from the dictionary|

Dictionary works somewhat like a list but with an added capability of assigning it's own index style.


```python
first_dict['One'] = 1
first_dict['Twelve'] = 12 
print(first_dict)
```

    {'One': 1, 'Twelve': 12}



```python
'One' in first_dict
```




    True




```python
del first_dict['One']
print(first_dict)
```

    {'Twelve': 12}


## Dictionary Methods


| Method | Use | Explanation |
|----|---|
| keys | adict.keys() |Returns the keys of the dictionary in a dict_keys object |
| values	| adict.values() |	Returns the values of the dictionary in a dict_values object |
| items	|adict.items()	|Returns the key-value pairs in a dict_items object|
| get	|adict.get(k)	|Returns the value associated with k, None otherwise|
| get	|adict.get(k,alt)	|Returns the value associated with k, alt otherwise|



```python
bio_data = {'Name': 'Bob Marley', 'Age':35, 'Height':"5.6 ft", 'Hobby': 'Music'}
print(bio_data)
```

    {'Name': 'Bob Marley', 'Age': 35, 'Height': '5.6 ft', 'Hobby': 'Music'}



```python
credentials = { 'UserA' : 'wkliopnc' , 'UserB': 98760 , 'UserC' :98760 } 
```


```python
hobby = bio_data['Hobby']
print(hobby)
```

    Music



```python
age = bio_data['Age']
print(age)
```

    35



```python
age = bio_data.get('Age')
print(age)
```

    35



```python
profession  =  bio_data.get('Profession','NA')
print(profession)
```

    NA



```python
## More exercise

capitals = {'Maharashtra':'Mumbai','Tamil Nadu':'Chennai'}

#get the capital of Maharashtra
print(capitals['Maharashtra'])

#create a new key Rajasthan whose capital(value) is Jaipur
capitals['Rajasthan']='Jaipur'
print(capitals)

#create another key-value pair
capitals['Punjab']='Chandigarh'
print(len(capitals))
```

    Mumbai
    {'Maharashtra': 'Mumbai', 'Tamil Nadu': 'Chennai', 'Rajasthan': 'Jaipur'}
    4


Dictionary keys are unique and hence we cannot have two similar keys. Values can be the same though.


```python
capitals['Haryana'] = 'Chandigarh'
print(capitals)
```

    {'Maharashtra': 'Mumbai', 'Tamil Nadu': 'Chennai', 'Rajasthan': 'Jaipur', 'Punjab': 'Chandigarh', 'Haryana': 'Chandigarh'}


## Dict_Error

Description

From a Dictionary `input_dict={'Name': 'Monty', 'Profession': 'Singer' }`, get the value of a key ‘Label’ which is not a part of the dictionary, in such a way that Python doesn't hit an error. If the key does not exist in the dictionary, Python should return 'NA'.



```python
input_dict={'Name': 'Monty', 'Profession': 'Singer' }
answer=input_dict.get('Label','NA')
print(answer)
```

    NA



```python
bio_data['Age'] = 36
print(bio_data)
```

    {'Name': 'Bob Marley', 'Age': 36, 'Height': '5.6 ft', 'Hobby': 'Music'}



```python
#add a key, val
bio_data['Profession'] = 'Singer'
print(bio_data)
```

    {'Name': 'Bob Marley', 'Age': 36, 'Height': '5.6 ft', 'Hobby': 'Music', 'Profession': 'Singer'}



```python
print('Profession' in bio_data)
```

    True


The `keys` and `values` method give you iterators of the dict’s keys and values, respectively.  

**keys( )** function returns a list with all the keys in the dictionary./


```python
print(bio_data.keys())
#get list of keys
print(list(bio_data.keys()))
print(type(bio_data.keys()))
```

    dict_keys(['Name', 'Age', 'Height', 'Hobby', 'Profession', 'Country'])
    ['Name', 'Age', 'Height', 'Hobby', 'Profession', 'Country']
    <class 'dict_keys'>


**values( )** function returns a list with all the assigned values in the dictionary./


```python
print(bio_data.values())
#get list of values
print(list(bio_data.values()))
print(type(bio_data.values()))

```

    dict_values(['Bob Marley', 36, '5.6 ft', 'Music', 'Singer', 'Jamaica'])
    ['Bob Marley', 36, '5.6 ft', 'Music', 'Singer', 'Jamaica']
    <class 'dict_values'>



```python
# to convert to a list use list()
 
bio_data_list = list(bio_data.values())
print(bio_data_list)
print(type(bio_data_list))
```

    ['Bob Marley', 36, '5.6 ft', 'Music', 'Singer', 'Jamaica']
    <class 'list'>


**items( )** is returns a list containing both the list but each element in the dictionary is inside a tuple.


```python
print(bio_data.items())

#convert to list of tuples
print(list(bio_data.items()))
```

    dict_items([('Name', 'Bob Marley'), ('Age', 36), ('Height', '5.6 ft'), ('Hobby', 'Music'), ('Profession', 'Singer'), ('Country', 'Jamaica')])
    [('Name', 'Bob Marley'), ('Age', 36), ('Height', '5.6 ft'), ('Hobby', 'Music'), ('Profession', 'Singer'), ('Country', 'Jamaica')]



```python
new_dictionary = dict(Country='Jamaica', Songs=['One Love','Misty Morning'])
```


```python
bio_data.update(new_dictionary)
print(bio_data)
```

    {'Name': 'Bob Marley', 'Age': 36, 'Height': '5.6 ft', 'Hobby': 'Music', 'Profession': 'Singer', 'Country': 'Jamaica', 'Songs': ['One Love', 'Misty Morning']}



```python
del bio_data['Songs']
print(bio_data)
```

    {'Name': 'Bob Marley', 'Age': 36, 'Height': '5.6 ft', 'Hobby': 'Music', 'Profession': 'Singer', 'Country': 'Jamaica'}



```python
students_data = { 1:['Shivam Bansal', 24] , 2:['Udit Bansal',25], 3:['Sonam Gupta', 26], 4:['Saif Ansari',24], 5:['Huzefa Calcuttawala',27]}

print(students_data)

```

    {1: ['Shivam Bansal', 24], 2: ['Udit Bansal', 25], 3: ['Sonam Gupta', 26], 4: ['Saif Ansari', 24], 5: ['Huzefa Calcuttawala', 27]}



```python
print(len(students_data))

```

    5



```python
#see all the details of students. 
print(list(students_data.values()))

```

    [['Shivam Bansal', 24], ['Udit Bansal', 25], ['Sonam Gupta', 26], ['Saif Ansari', 24], ['Huzefa Calcuttawala', 27]]



```python
students_data[6] = ['Manasi Sharma', 22]
print(students_data)

```

    {1: ['Shivam Bansal', 24], 2: ['Udit Bansal', 25], 3: ['Sonam Gupta', 26], 4: ['Saif Ansari', 24], 5: ['Huzefa Calcuttawala', 27], 6: ['Manasi Sharma', 22]}



```python
del students_data[2]
print(students_data)
```

    {1: ['Shivam Bansal', 24], 3: ['Sonam Gupta', 26], 4: ['Saif Ansari', 24], 5: ['Huzefa Calcuttawala', 27], 6: ['Manasi Sharma', 22]}



```python
print(list(students_data.keys()))

```

    [1, 3, 4, 5, 6]


`update` method to merge to Dictionararies

The update method changes dicts in-place, so any existing keys in the data passed to update will have their old values discarded.


```python
d1 = {'a' : 'some value', 'b' : [1, 2, 3, 4]}

d1.update({'b' : 'foo', 'c' : 12})

d1
```




    {'a': 'some value', 'b': 'foo', 'c': 12}




```python
## More exercise

#take a look at the block of code to understand
phoneext={'Sachin':1410,'Azhar':1137}
print(phoneext)

print(phoneext.keys())

print(list(phoneext.keys()))
print(phoneext.values())
print(list(phoneext.values()))

print(phoneext.items())

print(list(phoneext.items()))

print(phoneext.get("Dhoni"))

print(phoneext.get("Dhoni","Not a part of team"))

```

    {'Sachin': 1410, 'Azhar': 1137}
    dict_keys(['Sachin', 'Azhar'])
    ['Sachin', 'Azhar']
    dict_values([1410, 1137])
    [1410, 1137]
    dict_items([('Sachin', 1410), ('Azhar', 1137)])
    [('Sachin', 1410), ('Azhar', 1137)]
    None
    Not a part of team


### Getting a Value from a Dictionary.

Description

Extract the company headed by Tim Cook from the dictionary {'Jack Dorsey': 'Twitter', 'Tim Cook': 'Apple','Jeff Bezos': 'Amazon','Mukesh Ambani': 'RJIO'}


```python
input_dict={'Jack Dorsey': 'Twitter', 'Tim Cook': 'Apple','Jeff Bezos': 'Amazon','Mukesh Ambani': 'RJIO'}
name = input_dict['Tim Cook']
print(name)
```

    Apple


### List of Values in a Dictionary.

Description

Create a SORTED list of all values from the dictionary `input_dict = {'Jack Dorsey' : 'Twitter' , 'Tim Cook' : 'Apple','Jeff Bezos' : 'Amazon' ,'Mukesh Ambani' : 'RJIO'}`


```python
input_dict = {'Jack Dorsey' : 'Twitter' , 'Tim Cook' : 'Apple','Jeff Bezos' : 'Amazon' ,'Mukesh Ambani' : 'RJIO'}
value_list = input_dict.values()
print(sorted(value_list))
```

    ['Amazon', 'Apple', 'RJIO', 'Twitter']



```python
## Qs: Initialising a Dictionary

## Which of the following statements create a dictionary? Select all that apply (More than one option may be correct).\\

d = {}
print(d)
#It will create an empty dictionary.

d = {'a':1, 'b':2}
print(d)
#This a one of the method to create a dictionary.

d = dict(a=1, b=2) 
#dict function can be used to create a dictionary.
print(d)

#d = ('a':1, 'b':2)
#print(d)
# error
```

    {}
    {'a': 1, 'b': 2}
    {'a': 1, 'b': 2}
    {'a': 1, 'b': 2}



```python
### Deleting a Key

#Suppose dict_1 = {"Python'':40, "R'':45}. What command should be used to delete the entry "R"?

dict_1 = {"Python":40, "R":45}

#dict_1.delete('R':45)
# incorrect

del dict_1['R']
print(dict_1)
#Yes, del is used to delete a dictionary key.

#dict_1.delete('R')
# incorrect
#del dict_1('R':40)
# incorrect
```

    {'Python': 40}



```python
d = {'Python':40, 'R':45}
print(list(d.keys()))
#.keys() returns the keys only, and list() converts these keys into the list format.
```

    ['Python', 'R']


### Default values


It’s very common to have logic like:

`if key in some_dict:
value = some_dict[key]
else:
value = default_value`

Thus, the dict methods get and pop can take a default value to be returned, so that the above if-else block can be written simply as:

`value = some_dict.get(key, default_value)`

`get` by default will return None if the key is not present, while `pop` will raise an exception.With setting values, a common case is for the values in a dict to be other collections,like lists. For example, you could imagine categorizing a list of words by their first letters as a dict of lists:


```python
words = ['apple', 'bat', 'bar', 'atom', 'book']
by_letter = {}

for word in words:
    letter = word[0]
    if letter not in by_letter:
        by_letter[letter] = [word]
    else:
        by_letter[letter].append(word)
    
by_letter
```




    {'a': ['apple', 'atom'], 'b': ['bat', 'bar', 'book']}




```python
# The setdefault dict method is for precisely this purpose. The preceding for loop can be rewritten as:

by_letter1 = {}

for word in words:
    letter = word[0]
    by_letter1.setdefault(letter, []).append(word)
    
by_letter1
```




    {'a': ['apple', 'atom'], 'b': ['bat', 'bar', 'book']}




```python
# The built-in collections module has a useful class, defaultdict, which makes this even easier. To create one, you pass a type or function for generating the default value for each slot in the dict:

from collections import defaultdict
        
by_letter2 = defaultdict(list)
for word in words:
    by_letter2[word[0]].append(word)
    
by_letter2
```




    defaultdict(list, {'a': ['apple', 'atom'], 'b': ['bat', 'bar', 'book']})



## Sets

** unordered collection of unique elements**

The last type of data structure we will look at is 'sets'. Sets are a good way to get the unique elements out of a collection or to find common elements in various collections. Using sets is quick and can help solve tasks requiring deduplication.

Sets are mainly used to eliminate repeated numbers in a sequence/list. It is also used to perform some standard set operations.

A set can be created in two ways: via the `set` function or via a set literal with curly braces{}
Sets are declared as `set()` which will initialize a empty set. Also set([sequence]) can be executed to declare a set with elements


```python
first_set = set()
print(type(first_set))
```

    <class 'set'>



```python
second_set = set([1,2,2,3,3,4])
print(second_set)
```

    {1, 2, 3, 4}


## Set Methods - Built in set functions


| Method Name | Use | Explanation |
|----|---|
| union | aset.union(otherset) | Returns a new set with all elements from both sets |
| intersection	| aset.intersection(otherset) |	Returns a new set with only those elements common to both sets |
|difference	|aset.difference(otherset)	|Returns a new set with all items from first set not in second|
|issubset|	aset.issubset(otherset)|		Asks whether all elements of one set are in the other|
|add|	aset.add(item)|	Adds item to the set|
|remove|	aset.remove(item)|	Removes item from the set|
|pop|	aset.pop()|	Removes an arbitrary element from the set|
|clear|	aset.clear()|	Removes all elements from the set|


```python
from IPython.display import Image
Image(filename='pictures/13.PNG')
```




![png](output_266_0.png)




```python
students_list = ['A','A','B','C','C','E','N']

```


```python
students_set = set(students_list)
print(students_set)

```

    {'C', 'E', 'A', 'B', 'N'}



```python
print(type(students_set))

```

    <class 'set'>



```python
students_list_2 = ['A','N','F','N','G','A']

```


```python
students_set_2 = set(students_list_2)

```

- Intersection: $X \cap Y$:  
**intersection( )** function outputs a set which contains all the elements that are in both sets.


```python
print(students_set.intersection(students_set_2))
```

    {'A', 'N'}


- Union: $X \cup Y$:  
**union( )** function returns a set which contains all the elements of both the sets without repetition.


```python
print(students_set.union(students_set_2))
```

    {'C', 'G', 'B', 'E', 'A', 'F', 'N'}


- Difference $X - Y$:  
**difference( )** function ouptuts a set which contains elements that are in set1 and not in set2.


```python
print(students_set.difference(students_set_2))
```

    {'E', 'C', 'B'}


**symmetric_difference( )** function ouputs a function which contains elements that are in one of the sets.


```python
from IPython.display import Image
Image(filename='pictures/4.PNG') 
```




![png](output_279_0.png)




```python
students_set.symmetric_difference(students_set_2)
```




    {'B', 'C', 'E', 'F', 'G'}




```python
## Set_diff

#Find the difference, using difference and symmetric_difference, between two given lists - list1 and list2.

#First, convert the lists into sets and store them as set_1 and set_2. 
#Then store the difference and symmetric difference in answer_1 and answer_2 respectively. 
#Print both the answers as sorted lists, i.e. convert the final sets to lists, sort it and then return it.

list_1 = [1,2,3,4,5,6]
list_2 = [2,3,4,5,6,7,8,9]

set_1 = set(list_1)
set_2 = set(list_2)
answer_1 = sorted(list(set_1.difference(set_2)))
answer_2 = sorted(list(set_1.symmetric_difference(set_2)))

print(answer_1)
print(answer_2)

```

    [1]
    [1, 7, 8, 9]



```python
## Sets

## Qs:What gets printed with the following set of instructions?
nums = set([1,1,2,3,3,3,4])
print(len(nums))
## Set() removes duplicates and return the unique values.
```

    4


## List to set and vice-versa


```python
list_with_duplicates = ['A','B','A','C','D','C','C','B']
print(set(list_with_duplicates))
```

    {'D', 'A', 'C', 'B'}



```python
#Convert it to a list by wrapping it back to a list
print(list(set(list_with_duplicates)))
```

    ['D', 'A', 'C', 'B']



```python
from IPython.display import Image
Image(filename='pictures/14.PNG')
```




![png](output_286_0.png)



<h2 style="margin-top: 0px;"> Session 3 Control Structures and Functions</h2>

Control structures are the essence of programming since they help computers do what they do best — **automate repetitive tasks intelligently**. The most common control structures are `if-else statements, for and while loops, and (specific to Python) list and dictionary comprehensions`. This session will cover all of these.

 

Another crucial thing you will learn in is to write your own functions. Almost every powerful program — whether a web app or a machine learning algorithm — is basically a set of functions written to perform specific tasks.

 - Control structures
    - If-elif-else
    - For loop
    - While loop
    - List comprehensions
    - Dictionary comprehensions
 - Functions
 - Map
 - Filter
 - Reduce

<h2 style="margin-top: 0px;"> If-Elif-Else</h2>

The most basic control structure is a conditional statement. When you want different operations to be performed when the values of the variable vary, you need conditional statements. 

The syntax of an if statement is pretty simple:

`if &lt;condition 1=""&gt;:
    do something`&lt;/condition&gt;

The statement needs to be indented with a `tab`. In Sublime Text, at the bottom right, you can adjust the tab size to be equal to any number of white spaces. A good practice is to make use of four white spaces as the tab size for indentations. Anything outside an indentation is not a part of the if statement. So, for the following statement —

`if i&gt;10 and j&lt;8:
    c+=5
print(c)`

The print statement is not a part of if statement as it is not indented on the if statement. Now, this is how an if-else statement will look:

`if &lt;condition 1=""&gt;:
    do something
else:
    do something else`&lt;/condition&gt;

Similarly, you can have the elif statement (In R, this is 'else-if'):

`if &lt;condition 1=""&gt;:
    do something
elif &lt;condition 2=""&gt;:
    do something else
else:
    do something else`&lt;/condition&gt;&lt;/condition&gt;


```python
score = int(input("Enter your test score : "))
passing = 40
distinction = 90

```

    Enter your test score : 50



```python
if score >= distinction:
    print("You're at the top! You’ve earned a distinction!")

if score >= passing and score < distinction:
    print("You have passed!")

if score < passing:
    print("Sorry! You have failed")

```

    You have passed!



```python
if score==100:
    print("Perfect")
elif  90<=score<100:
    print("Distinction")
elif 65<=score<90:
    print("First Class")
elif 40<=score<65:
    print("Second Class")
else:
    print("Failed")

```

    Second Class



```python
statement = "The coffee is bad"
if 'bad' in statement:
    print("Bad review!")

statement2 = "This phone works great"
if 'bad' in statement2:
    print("This is not a bad review")

```

    Bad review!


### Nested If-Elif-Else loop


```python
num = int(input("Enter a number: "))
#enter 24
if num%2==0:
    print("Even")
    if num%4==0:
        print("divisible by 4")
    else:
        print("Not divisible by 4")
else:
    print("Odd")
    if num%3==0:
        print("Divisible by 3")
    else:
        print("Not divisible by 3")

```

    Enter a number: 5
    Odd
    Not divisible by 3



```python
if None:
    print("Is True")
else:
    print("Is False")
```

    Is False


**If-Else**

Qs: Write a code to check if the string in input_str starts with a vowel or not. Print capital YES  or NO.

For example, if input_str = 'analytics' then, your output should print 'YES'.


```python
input_str = 'alpha'
vowels=['a','e','i','o','u']

if input_str[0] in vowels:
    print('Yes')
else:
    print('no')
```

    Yes



```python
## Aliter
input_str = 'alpha'

if input_str[0] == 'a':
    print('YES')
elif input_str[0] == 'e':
    print('YES')
elif input_str[0] == 'i':
    print('YES')
elif input_str[0] == 'o':
    print('YES')
elif input_str[0] == 'u':
    print('YES')
else:
    print('NO')
```

    YES



```python
## Aliter
input_str = 'alpha'
if input_str[0] in ['a','e','i','o','u']:
    print('YES')
else:
    print('NO')
```

    YES



```python
## If Statements

# Given the code below, the output obtained in several runs is 'C' 'A' 'D' 'B'.
score = int(input("Enter your test score : "))

if score >= 90:
   print('A')
elif score >=80:
   print('B')
elif score >= 70:
   print('C')
elif score >= 60:
   print('D')
else:
   print('F')

# Qs:Which of the following sequences of inputs would give this output?
# Ans: 70, 91, 67, 88
# For 'C' obtained marks should be greater than or equal to 70. For 'A' obtained marks should be greater than or equal to 90.
#For 'D' obtained marks should be greater than or equal to 60. For 'B' obtained marks should be greater than or equal to 80.
```

    Enter your test score : 67
    D



```python
## If Statements (Boolean)

# Qs:What will the following segment of code print? Try doing this verbally.

if (10 < 0) and (0 < -10):
    print("A")
elif (10 > 0) or False:
    print("B")
else:
    print("C")
    
# Ans: B  (10 > 0 returns True. True or False is True. Hence, 'B' gets printed.)
```

    B



```python
## If-Else (Boolean 2)

# Qs:What will the following segment of code print? Try solving it verbally.

if True or True:
    if False and True or False:
        print('A')
    elif False and False or True and True:
        print('B')
    else:
        print('C')
else:
    print('D')
    
##Ans:B  (T or T will be a T. The code will return the value which satisfies this statements. 
#A will be returned for an F since (F and T) = F, (F or F) = F B will be returned for a T since (F and F) =F,
#(T and T) =T, (F or T) = T)

```

    B


<h2 style="margin-top: 0px;"> For &amp; While Loops</h2>

Looping is an important part of carrying out operations — whether it is looping over a range of numbers, numbers in an array, items in a list, or keys and values in a dictionary, etc. You must be familiar with the use of loops in Python.

Python makes looping much easier as the looping construct resembles the framework of a standard English sentence, making it easier to understand at a glance. 


```python
for i in range(1,5):
    print(i)

```

    1
    2
    3
    4



```python
for i in range(1,10,2):
    print(i) 
```

    1
    3
    5
    7
    9



```python
#Looping on a string

my_string = "Mary had a little lamb"

for alphabet in my_string:
    print(alphabet)

```

    M
    a
    r
    y
     
    h
    a
    d
     
    a
     
    l
    i
    t
    t
    l
    e
     
    l
    a
    m
    b


#pattern to print-

*
* *
* * *
* * * * 
* * * * *
* * * *
* * *
* *
*



```python
str1=''
for i in range(0,9):
    if i<5:
        str1 += '* '
        print(str1)
    elif i>4:
        str1 = str1[:-2]
        print(str1)

```

    * 
    * * 
    * * * 
    * * * * 
    * * * * * 
    * * * * 
    * * * 
    * * 
    * 



```python
my_string = "Mary had a little lamb"

for n,alphabet in enumerate(my_string):
    print(alphabet, n)

```

    M 0
    a 1
    r 2
    y 3
      4
    h 5
    a 6
    d 7
      8
    a 9
      10
    l 11
    i 12
    t 13
    t 14
    l 15
    e 16
      17
    l 18
    a 19
    m 20
    b 21



```python
my_string = "Mary had a little lamb"
vowels =''
for alphabet in my_string:
    if alphabet in 'aeiou':
        vowels += ' ' + alphabet
print(vowels)

```

     a a a i e a



```python
nums = '838848237890237388221'
all_even=''
all_odd = ''
for number in nums:
    if int(number)%2 == 0:
        all_even += number
    else:
        all_odd += number

print('All Evens are : '+ all_even + ' & All odds are : '+ all_odd)

```

    All Evens are : 8884828028822 & All odds are : 33793731


**Iterations** can be over any collection. The iteration in a string goes over each character; however, in lists and tuples, the iteration goes over each item in turn, and in dictionaries, you can iterate over both keys and values or any one of them. Another keyword — `'enumerate'` — can be used to introduce another iterating variable that counts the iterations. Note that it starts with 0.

Other commands that can be used are **'break', 'continue', and 'pass'**. To see the differences between them, use the following piece of code:


```python
for i in range(20):
    print(i)
    if i>10:
        break
        print("Hello")
```

    0
    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    11



```python
for i in range(20):
    print(i)
    if i>10:
        pass
        print("Hello")
```

    0
    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    11
    Hello
    12
    Hello
    13
    Hello
    14
    Hello
    15
    Hello
    16
    Hello
    17
    Hello
    18
    Hello
    19
    Hello



```python
for i in range(20):
    print(i)
    if i>10:
        continue
        print("Hello")
```

    0
    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    11
    12
    13
    14
    15
    16
    17
    18
    19


Notice how the break command breaks out of the loop once i = 11, and it is used to exit the iteration. Replace 'break' with pass'. You will now see that after the value of i exceeds 10, the string "Hello" is printed. 'Pass' does nothing and allows the remaining code to be executed. If you now replace 'pass' with 'continue', you will notice that the keyword "Hello" isn't printed at all, but the values of i are. The reason behind this is that 'continue' exits that iteration and moves to the next one, not allowing anything below it to be executed. 'Pass', on the other hand, allows for statements to be executed below it in the loop.

 


```python
list_of_inventories = ['Apple', 'Banana', 'Potato', 'Mango', 'Onion', 'Toothpaste']
fruits = ['Apple','Banana','Mango','Orange','Strawberry']
vegetables = ['Potato', 'Onion','Cucumber', 'Celery']

```


```python
#count of fruits in inventory list
count_fruits = 0
#count of vegetables in inventory list
count_veg = 0
for item in list_of_inventories:
    print(item)
    if item in fruits:
        count_fruits+=1
    elif item in vegetables:
        count_veg +=1
    else:
        continue
print(count_fruits)
print(count_veg)
```

    Apple
    Banana
    Potato
    Mango
    Onion
    Toothpaste
    3
    2



```python
sentence = "Is Python simpler than R ?"
for word in sentence.split():
    print(word)

```

    Is
    Python
    simpler
    than
    R
    ?



```python

#sentence check
tweet = '#beautiful #morning it is looking good'

for word in tweet.split():
    if word.startswith('#'):
        print(word[1:])

```

    beautiful
    morning



```python
students_data = {1:['Shivam Bansal', 24] , 2:['Udit Bansal',25], 3:['Sonam Gupta', 26], 4:['Saif Ansari',24], 5:['Huzefa Calcuttawala',27]}

```


```python
for key, val in students_data.items():
    print(key, val)

```

    1 ['Shivam Bansal', 24]
    2 ['Udit Bansal', 25]
    3 ['Sonam Gupta', 26]
    4 ['Saif Ansari', 24]
    5 ['Huzefa Calcuttawala', 27]



```python
for key in students_data.keys():
    print(key)

```

    1
    2
    3
    4
    5



```python
for val in students_data.values():
    print(val)

```

    ['Shivam Bansal', 24]
    ['Udit Bansal', 25]
    ['Sonam Gupta', 26]
    ['Saif Ansari', 24]
    ['Huzefa Calcuttawala', 27]



```python
count = 0
for key, val in students_data.items():
    if val[1]<25:
        count+=1

print(count)
```

    2


### while loop

A while loop is used when you aren't sure of the number of iterations you need to have. It should be used when your results depend on the value of a variable.


```python
#while loop
start =20
total= 0
while start<51:
    total+=start
    start+=1
    print(start)

print(total)


```

    21
    22
    23
    24
    25
    26
    27
    28
    29
    30
    31
    32
    33
    34
    35
    36
    37
    38
    39
    40
    41
    42
    43
    44
    45
    46
    47
    48
    49
    50
    51
    1085



```python
## Dictionary Iteration

## Qs:What will the output of the following be?
d = {0: 'Fish', 1: 'Bird', 2: 'Mammal'}
for i in d:
    print(i)
    
## Ans:0 1 2  (By default, the iteration is over the keys.)
```

    0
    1
    2



```python
## Iterations

d = {0, 1, 2}
for x in d:
    print(d.add(x))

# Ans: None None None (d.add(x) returns None; hence, only None gets printed.)
```

    None
    None
    None



```python
## The Continue Command

# Qs:How many lines will the output contain for the following 3 pieces of code respectively?

for i in range(1,6):
    if (i % 3 == 0):
        print(str(i) + " is Divisible by 3")
        break

    print(str(i) + " is not divisible by 3")
    
# Ans: break' will stop the loop once the 'if' condition satisfies, i.e. when the value of 'i' becomes 3. 
#It will then come out of the loop. Hence, you get 3 lines, for 1, 2, and 3. The following is the output:

print("*************")

for i in range(1,6):
    if (i % 3 == 0):
        print(str(i) + " is Divisible by 3")
        continue

    print(str(i) + " is not divisible by 3")
    
## Ans:'continue' will pass the control to the next iteration once the code reaches that line. Hence,
#it will print 5 lines. The following is the output:
    
print("************

for i in range(1,6):
    if (i % 3 == 0):
        print(str(i) + " is Divisible by 3")
        pass

    print(str(i) + " is not divisible by 3")
    
# Ans:'pass' will simply pass the control to the next line. The following is the output:

```

    1 is not divisible by 3
    2 is not divisible by 3
    3 is Divisible by 3
    *************
    1 is not divisible by 3
    2 is not divisible by 3
    3 is Divisible by 3
    4 is not divisible by 3
    5 is not divisible by 3
    *************
    1 is not divisible by 3
    2 is not divisible by 3
    3 is Divisible by 3
    3 is not divisible by 3
    4 is not divisible by 3
    5 is not divisible by 3


### Additional Reading

[Python 3 — official documentation](https://docs.python.org/3/tutorial/controlflow.html)   
[Compound statements](https://docs.python.org/3/reference/compound_stmts.html)

<h2 style="margin-top: 0px;">Comprehensions</h2>

Python comprehensions are syntactic constructs that enable sequences to be built from other sequences in a clear and concise manner. Here, we will cover **list comprehensions and dictionary comprehensions**.

### List Comprehension

Using list comprehensions is much more concise and elegant than explicit for loops. An example of creating a list using a loop and a comprehension is as follows:

** List comprehensions turns old lists into new lists**

`[expr for val in collection if condition]`

This is equivalent to the following for loop:

`result = []
for val in collection:
    if condition:
        result.append(expr)`


```python
# using a for loop

product_list = []
for i in range(10):
    for j in range(10,20):
        product_list.append(i*j)
print(product_list)
```

    [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 30, 33, 36, 39, 42, 45, 48, 51, 54, 57, 40, 44, 48, 52, 56, 60, 64, 68, 72, 76, 50, 55, 60, 65, 70, 75, 80, 85, 90, 95, 60, 66, 72, 78, 84, 90, 96, 102, 108, 114, 70, 77, 84, 91, 98, 105, 112, 119, 126, 133, 80, 88, 96, 104, 112, 120, 128, 136, 144, 152, 90, 99, 108, 117, 126, 135, 144, 153, 162, 171]



```python
#The same code using a list comprehension is as follows:

# using list comprehension
product_list = [ i*j for i in range(10) for j in range(10,20) ]
print(product_list)
```

    [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 30, 33, 36, 39, 42, 45, 48, 51, 54, 57, 40, 44, 48, 52, 56, 60, 64, 68, 72, 76, 50, 55, 60, 65, 70, 75, 80, 85, 90, 95, 60, 66, 72, 78, 84, 90, 96, 102, 108, 114, 70, 77, 84, 91, 98, 105, 112, 119, 126, 133, 80, 88, 96, 104, 112, 120, 128, 136, 144, 152, 90, 99, 108, 117, 126, 135, 144, 153, 162, 171]


You can see that in the square brackets, you need to first put in the operation/output that you desire, followed by the loops from top to bottom. 

A list comprehension consists of the following parts:

- An Input Sequence.
- A Variable representing members of the input sequence.
- An Optional Predicate expression.
- An Output Expression producing elements of the output list from members of the Input Sequence that satisfy the predicate.



```python
#Say we need to obtain a list of all the integers in a sequence and then square them:

a_list = [1, '4', 9, 'a', 0, 4]

squared_ints = [ e**2 for e in a_list if type(e) == int]
print(squared_ints)
# [ 1, 81, 0, 16 ]

```

    [1, 81, 0, 16]



```python
from IPython.display import Image
Image(filename='pictures/5.PNG') 
```




![png](output_345_0.png)




```python
from IPython.display import Image
Image(filename='pictures/6.PNG') 
```




![png](output_346_0.png)




```python
from IPython.display import Image
Image(filename='pictures/12.PNG')
```




![png](output_347_0.png)




```python
from IPython.display import Image
Image(filename='pictures/7.PNG',width=700,height=200) 
```




![png](output_348_0.png)




```python
from IPython.display import Image
Image(filename='pictures/8.PNG',width=700,height=200) 
```




![png](output_349_0.png)




```python
from IPython.display import Image
Image(filename='pictures/9.PNG')
```




![png](output_350_0.png)




```python
from IPython.display import Image
Image(filename='pictures/10.PNG',width=700,height=200)
```




![png](output_351_0.png)




```python
from IPython.display import Image
Image(filename='pictures/11.PNG',width=700,height=200)
```




![png](output_352_0.png)



Suppose we need to create a list with first 10 multiple of 6 in it, So we may do this with a normal
for loop or with list comprehensions, Let's see both of them and understand the difference.


```python
#Normal​ ​For​ ​loop
list1 =[]
for n in range(1,11):
    list1.append(n*6)
print(list1)
```

    [6, 12, 18, 24, 30, 36, 42, 48, 54, 60]



```python
#List​ ​comprehension
list1 = [n*6 for n in range(1,11)]
print(list1)
```

    [6, 12, 18, 24, 30, 36, 42, 48, 54, 60]


We got the same output using list comprehensions just by writing a line of code.

In​ ​general​ ​list​ ​comprehension

`[&lt;the_expression&gt; for &lt;the_element&gt; in &lt;the_iterable&gt;]`  
Comparing this with our example n*6 is the​ ​expression​, n is the​ ​element​, range(1,11) is the
iterable&lt;/the_iterable&gt;&lt;/the_element&gt;&lt;/the_expression&gt;


```python
squares_list= []

for x in range(1,10):
    squares_list.append(x**2)
print(squares_list)

```

    [1, 4, 9, 16, 25, 36, 49, 64, 81]



```python
squares_list = [x**2 for x in range(1,10)]
print(squares_list)
```

    [1, 4, 9, 16, 25, 36, 49, 64, 81]



```python
paragraph = ["There was a fox." , 'It was brown in color.', "It was seen near that farm sometime back"]
```


```python
# ['There', 'was', 'a', 'fox.', 'It', 'was', 'brown', 'in', 'color.', 'It', 'was', 'seen', 'near', 'that', 'farm', 'sometime', 'back']
```


```python
single_word_list =[]

for sentence in paragraph:
    for word in sentence.split():
        single_word_list.append(word)

print(single_word_list)
```

    ['There', 'was', 'a', 'fox.', 'It', 'was', 'brown', 'in', 'color.', 'It', 'was', 'seen', 'near', 'that', 'farm', 'sometime', 'back']



```python
single_word_list  = [word for sentence in paragraph for word in sentence.split()]
print(single_word_list)
```

    ['There', 'was', 'a', 'fox.', 'It', 'was', 'brown', 'in', 'color.', 'It', 'was', 'seen', 'near', 'that', 'farm', 'sometime', 'back']


**Applying​ ​list​ ​comprehension​ ​with​ ​a​ ​condition**

Now, Suppose we need to create a list of multiple of 6 for just even numbers between 1 to 10.


```python
list1 =[]
for n in range(1,11):
    if n%2==0:
        list1.append(n*6)
print(list1)

```

    [12, 24, 36, 48, 60]



```python
##Using list comprehensions
list1 = [n*6 for n in range(1,11) if n%2==0]
print(list1)
```

    [12, 24, 36, 48, 60]


In​ ​general​ ​list​ ​comprehension

`[&lt;the_expression&gt; for &lt;the_element&gt; in &lt;the_iterable&gt; if &lt;the_condition&gt;]`  
Comparing this with our example n*6 is the​ ​expression​, n is the​ ​element​, range(1,11) is the
iterable​ and n%2==0 is the​ ​condition.
&lt;/the_condition&gt;&lt;/the_iterable&gt;&lt;/the_element&gt;&lt;/the_expression&gt;


```python
#list comp with if statement
vowels = ['a','e','i','o','u']
vowels_from_sentence =[]
for sentence in paragraph:
    for word in sentence.split():
        if word[0].lower() in vowels:
            vowels_from_sentence.append(word)

print(vowels_from_sentence)

```

    ['a', 'It', 'in', 'It']



```python
#[ for sentence in paragraph]
#[ for sentence in paragraph for word in sentence.split()]

```


```python
vowels_comp = [word for sentence in paragraph for word in sentence.split() if word[0].lower() in vowels]
print(vowels_comp)
```

    ['a', 'It', 'in', 'It']


**Applying​ ​list​ ​comprehension​ ​with​ ​if-else​ ​condition**  

Now, Suppose we need to create a list of multiple of 6 for even numbers between 1 to 10 and
multiple of 5 for rest of the numbers.


```python
list1 =[]
for n in range(1,11):
    if n%2==0:
        list1.append(n*6)
    else:
        list1.append(n*5)
print(list1)

```

    [5, 12, 15, 24, 25, 36, 35, 48, 45, 60]



```python
##Using list comprehensions
list1 = [n*6 if n%2==0 else n*5 for n in range(1,11)]
print(list1)

```

    [5, 12, 15, 24, 25, 36, 35, 48, 45, 60]


**In​ ​general​ ​list​ ​comprehension**

`[&lt;the_expression&gt; if &lt;the_condition&gt; else &lt;other_expression&gt; for &lt;the_element&gt; in&lt;the_iterable&gt;]`  
Comparing this with our example n*6 is the​ ​expression​, n%2==0 is the​ ​condition,​ ​n*5 is the
other​ ​expression​, n is the​ ​element​ and range(1,11) is the​ ​iterable&lt;/the_iterable&gt;&lt;/the_element&gt;&lt;/other_expression&gt;&lt;/the_condition&gt;&lt;/the_expression&gt;

**Applying​ ​list​ ​comprehension​ ​with​ ​Nested​ ​loops**  

Now, Suppose we need to multiply n ranging from 1 to 10 with first 1 then 2 and then 3.


```python
list1 =[]
for i in range(1,4):
    for j in range(1,11):
        list1.append(i*j)
print(list1)
```

    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30]



```python
list1 = [i*j for i in range(1,4) for j in range(1,11) ]
print(list1)
```

    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30]


**In​ ​general​ ​list​ ​comprehension**

`[ &lt;the_expression&gt; for &lt;element_a&gt; in &lt;iterable_a&gt; (optional if &lt;condition_a&gt;)
for &lt;element_b&gt; in &lt;iterable_b&gt; (optional if &lt;condition_b&gt;)
for &lt;element_c&gt; in &lt;iterable_c&gt; (optional if &lt;condition_c&gt;)
... and so on ...]`

Comparing this with our example i*j is the​ ​expression​, i is the​ ​element_a​, j is the​ ​element_b​,
range(1,4) is the​ ​iterable_a​ and range(1,11) is the​ ​iterable_b.&lt;/condition_c&gt;&lt;/iterable_c&gt;&lt;/element_c&gt;&lt;/condition_b&gt;&lt;/iterable_b&gt;&lt;/element_b&gt;&lt;/condition_a&gt;&lt;/iterable_a&gt;&lt;/element_a&gt;&lt;/the_expression&gt;


```python
squared_dictionary = {num : num**2 for num in range(0, 25)}
print(squared_dictionary)
```

    {0: 0, 1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64, 9: 81, 10: 100, 11: 121, 12: 144, 13: 169, 14: 196, 15: 225, 16: 256, 17: 289, 18: 324, 19: 361, 20: 400, 21: 441, 22: 484, 23: 529, 24: 576}



```python
students_data = {1:['Shivam Bansal', 24] , 2:['Udit Bansal',25], 3:['Sonam Gupta', 26], 4:['Saif Ansari',24], 5:['Huzefa Calcuttawala',27]}

```


```python
names_dict ={}

#iterate over each key, val pair
for roll_num,details in students_data.items():
    if roll_num%2==0:
        names_dict[roll_num]= details[0]
print(names_dict)
```

    {2: 'Udit Bansal', 4: 'Saif Ansari'}



```python
names_comp = {roll_num:details[0] for roll_num,details in students_data.items() if roll_num%2==0}
print(names_comp)
```

    {2: 'Udit Bansal', 4: 'Saif Ansari'}



```python
## List Comprehension

# Qs:What will the output of the following code be?

print([i+j for i in "abc" for j in "def"])
```

    ['ad', 'ae', 'af', 'bd', 'be', 'bf', 'cd', 'ce', 'cf']


Ans:For every value of j, i and j are concatenated in a list.

### Creating a List Comprehension

Qs:You are given an integer 'n' as the input. Create a list comprehension containing the squares of the integers from 1 till n^2 (including 1 and n), and print the list. 

For example, if the input is 4, the output should be a list as follows:`[1, 4, 9, 16]`

The input integer 'n' is stored in the variable 'n'.  


```python
n = int(input())

squared_n=[n**2 for n in range(1,n+1,1)]
print(squared_n)
```

    4
    [1, 4, 9, 16]


### List Comprehensions

Qs:Extract the words that start with a vowel from a list input_list=[wood, old, apple, big, item, euphoria] using list comprehensions.


```python
# Using naive for loop
input_list=['wood', 'old', 'apple', 'big', 'item', 'euphoria']
for word in input_list:
    if word[0] in 'aeiou':
        print(word)
```

    old
    apple
    item
    euphoria



```python
input_list=['wood', 'old', 'apple', 'big', 'item', 'euphoria']

list_vowel =[w for w in input_list if w[0] in 'aeiou']
print(list_vowel)
```

    ['old', 'apple', 'item', 'euphoria']



```python
## Aliter oneline answers
input_list=['wood', 'old', 'apple', 'big', 'item', 'euphoria']
print([w for w in input_list if w[0] in 'aeiou'])

vowel = 'a', 'e', 'i', 'o', 'u'
print([w for w in input_list if w.startswith(vowel)])
```

    ['old', 'apple', 'item', 'euphoria']
    ['old', 'apple', 'item', 'euphoria']


## Dictionary Comprehension

A dict comprehension looks like this:

`dict_comp = {key-expr : value-expr for value in collection if condition}`

A set comprehension looks like the equivalent list comprehension except with curly braces instead of square brackets:

`set_comp = {expr for value in collection if condition}`

You are given an integer input n.

Qs:Write a program to generate a dictionary that contains the key-value pairs i: i**2 where ' i ' is an integer number from 1 to n (both 1 and n included). 

For example, if the input is n=8, the output should be a dictionary as follows:

`{1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64}`


```python
## Naive for loop
n=int(input("Input a number "))
d = dict()

for x in range(1,n+1):
    d[x]=x*x

print(d) 
```

    Input a number 4
    {1: 1, 2: 4, 3: 9, 4: 16}



```python
## Solving with dict comprehension

n = int(input())

dictionary = {n:n*n for n in range(1,n+1)}
print(dictionary)
```

    4
    {1: 1, 2: 4, 3: 9, 4: 16}



```python
##Dictionary Comprehension

#Qs:What will the output of the following code be?

d = {x.upper(): x*3 for x in 'acbd'}
print(d)
#Ans: a*3 will return aaa and a.upper() will return 'A
```

    {'A': 'aaa', 'C': 'ccc', 'B': 'bbb', 'D': 'ddd'}


### Additional Reading

- [Comprehensions explained visually](https://treyhunner.com/2015/12/python-list-comprehensions-now-in-color/)
- [Python 3 idioms test](https://python-3-patterns-idioms-test.readthedocs.io/en/latest/Comprehensions.html)

<h2 style="margin-top: 0px;">Functions</h2>

Functions, as the name suggests, perform a task or function. They are **blocks of code that can be reused at various parts of the code as well as various files**. When you import any package and call any of its methods, you make use of the functions defined in it. This makes determining the use of each portion of the code significantly easier.

As a rule of thumb, if you anticipate needing to repeat the same or very similar code more than once, it may be worth writing a reusable function. Functions can also help make your code more readable by giving a name to a group of Python statements.

Functions are declared with the `def` keyword and returned from with the `return` keyword:

`def my_function(x, y, z=1.5):
    if z &gt; 1:
        return z * (x + y)
    else:
        return z / (x + y)`
        
Each function can have `positional` arguments and `keyword` arguments. Keyword arguments are most commonly used to specify default values or optional arguments. In the preceding function, x and y are positional arguments while z is a keyword argument. This means that the function can be called in any of these ways:

`my_function(5, 6, z=0.7)
 my_function(3.14, 7, 3.5)
 my_function(10, 20)`


```python
def scream():
    print('Hello World')
scream()

```

    Hello World



```python
def square(num):
    out = num**2
    return(out)

```


```python
sq_3 = square(3)
print(sq_3)
```

    9



```python
def square(num):
    out = num**2
    print(out)

```


```python
q = square(4)
print("Q is"+str(q))

```

    16
    Q isNone



```python
def factorial(n):
    if n>1:
        return n*factorial(n-1)
    else:
        return n

fact = factorial(5)
print(fact)

```

    120



```python
def addition(*args):
    print(args)
    return(sum(args))

```


```python
print(addition(4,5,6,7,8,9))
print(addition(1,2))
```

    (4, 5, 6, 7, 8, 9)
    39
    (1, 2)
    3



```python
def proper(some_text):
    some_text = some_text.strip()
    some_text = " ".join([word[0].upper() + word[1:] for word in some_text.split()])
    return some_text

captain = proper("mahendra singh dhoni")
print(captain)

```

    Mahendra Singh Dhoni


### Function

Qs:Create a function squared(),  which takes x and y as arguments and returns the x**y value. For e.g., if x = 2  and y = 3 , then the output is 8.


```python
input_list=['2','3']
x = int(input_list[0])
y = int(input_list[1])

def squared(x,y):
    square=x**y
    return square

#Write your code here

print(squared(x,y))
```

    8



```python
##Functions

# Qs:What is the output of the following program?

def say(message, times = 1):
    print(message * times)

say('Hello')
say('World', 5)

#Ans: or some functions, you may want to make some parameters optional and use default values in case the user does not want
#to provide values for them. This is done with the help of default argument values. You can specify default argument values 
#for parameters by appending to the parameter name in the function definition of the assignment operator (=), followed by 
#the default value. The function 'say' is used to print a string as many times as specified. If you don’t supply a value, 
#then by default, the string is printed just once. You achieve this by specifying a default argument value of 1 to the 
#parameter ‘times’. In the first usage of ‘say’, you supply only the string, and it prints the string once. 
#In the second usage of ‘say’, you supply both the string and an argument 5, stating that you want to say the string message
#five times. 
```

    Hello
    WorldWorldWorldWorldWorld


**Id Function**

**Id** function accepts a single parameter and is used to return the identity of an object. This identity has to be **unique and constant for this object during the lifetime**. Two objects with non-overlapping lifetimes may have the same id() value. If we relate this to C, then they are actually the memory address, here in Python it is the unique id. This function is generally used internally in Python.

Qs:Which of the following is the use of the id() function in Python?
Ans:Python has a unique identification number for each object created, id() return the id number of that object.


```python
## Ex


# This program shows various identities 
str1 = "geek"
print(id(str1)) 
  
str2 = "geek"
print(id(str2)) 
  
# This will return True 
print(id(str1) == id(str2)) `b 

```

    140089933200664
    140089933200664
    True
    140089933198872
    140089933200608
    False



```python
# Use in Lists 
list1 = ["aakash", "priya", "abdul"] 
print(id(list1[0])) 
print(id(list1[2])) 
  
# This returns false 
print(id(list1[0])==id(list1[2]))
```

    140089933198872
    140089933200608
    False


### Lambda Expressions (Anonymous  Functions)

Lambda expressions are also another way of defining functions but with a difference. They aren't capable of multiple expressions and can only handle single expressions. The format of lambda statements is as follows:

`function_name  = lambda &lt;space&gt;  input_parameters  :  output_parameters`

Eg: `join_by_comma = lambda x : ','.join(x)` 

This will create a function called `join_by_comma` and will return a string with each item of the list separated by a comma.&lt;/space&gt;


```python
string_to_list = lambda x: x.split()
print(string_to_list(captain))
print(type(string_to_list))

```

    ['Mahendra', 'Singh', 'Dhoni']
    <class 'function'>


Similar to if-else and the for loop, the parts belonging to a function are indented on it. There is no need for brackets except for the input parameters that are specified just after the function name.


```python
product = lambda x, y : x*y
print(product(3,4))

```

    12


### Lambda

Qs:Create a lambda function 'greater', which takes two arguments x and y and return x if x&gt;y otherwise y.
If x = 2 and y= 3, then the output should be 3.


```python
input_list=['9','3']
a = int(input_list[0])
b = int(input_list[1])

greater=lambda a,b:a if a>b else b

print(greater(a,b))
```

    9



```python
## Aliter:using vanila function
input_list=['9','3']
a = int(input_list[0])
b = int(input_list[1])

def greater(x,y):
    if x>y:
        return x
    else:
        return y
    
greater(a,b)
```




    9




```python
##Lambdas

# Qs:What is the output of this program?

min = (lambda x, y: x if x < y else y)
min(101*99, 102*98)
```




    9996



### Additional Reading

- [A byte of Python: Functions](https://python.swaroopch.com/functions.html)
- [Defining functions of your own](http://anh.cs.luc.edu/python/hands-on/3.1/handsonHtml/functions.html)

You can also go through the list of all built-in functions in Python from the following link:

- [Built-in function in Python](https://docs.python.org/2/library/functions.html)

<h2 style="margin-top: 0px;">Map, Filter, and Reduce</h2>

Map is a function that works like list comprehensions and for loops. It is used when you need to map or implement functions on various elements at the same time.

Map applies a unary function to each element in the sequence and returns a new sequence containing the results, in the same order. Map applies a function to all the items in an input_list.

`map(function_to_apply, list_of_inputs)`


```python
first_list = [2, 4, 5]
print(first_list**2)

```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-16-1f41c4b43dbf> in <module>()
          1 first_list = [2, 4, 5]
    ----> 2 print(first_list**2)
    

    TypeError: unsupported operand type(s) for ** or pow(): 'list' and 'int'



```python
print(map(lambda x: x**2, first_list))
```

    <map object at 0x7f693a76a668>



```python
first_list = [2,4,5]
print(list(map(lambda x: x**2, first_list)))
```

    [4, 16, 25]



```python
list(map(lambda k: 2**k, [1, 2, 3, 4]))
```




    [2, 4, 8, 16]



Qs:Using the Map function, create a list 'cube', which consists of the cube of numbers in input_list.

For e.g. if the input list is `[5,6,4,8,9]`, the output should be `[125, 216, 64, 512, 729]`.


```python
input_list = [5,6,4,8,9]

cube=list(map(lambda x:x**3,input_list))

print(cube)
```

    [125, 216, 64, 512, 729]


### Map Function

Using the function Map, count the number of words that start with ‘S’ in input_list.


```python
input_list =['San Jose', 'San Francisco', 'Santa Fe', 'Houston']

print(sum(list(map(lambda x: x.startswith('S'),input_list))))
```

    3



```python
first_list = [2, 4, 5]
```


```python
def squareit(n):
    return n**2
print(list(map(squareit, first_list)))

```

    [4, 16, 25]



```python
sums_list = [3,5,9,7]
sums_list2 = (4,5,6,7)
print(list(map(lambda x,y : x+y, sums_list,sums_list2)))

```

    [7, 10, 15, 14]



```python
list_of_names = ['nikola', 'james', 'albert']
list_of_names2 = ['tesla','watt','einstein']
proper = lambda x, y: x[0].upper()+x[1:] +' '+ y[0].upper()+y[1:]
print(list(map(proper, list_of_names,list_of_names2)))

```

    ['Nikola Tesla', 'James Watt', 'Albert Einstein']


### Map Function

Qs:Create a list ‘name’ consisting of the combination of the first name and the second name from list 1 and 2 respectively. 

For e.g. if the input list is: `[ ['Ankur', 'Avik', 'Kiran', 'Nitin'], ['Narang', 'Sarkar', 'R', 'Sareen']]`

the output list should be the list:`['Ankur Narang', 'Avik Sarkar', 'Kiran R', 'Nitin Sareen']`


```python
input_list=[ ['Ankur', 'Avik', 'Kiran', 'Nitin'], ['Narang', 'Sarkar', 'R', 'Sareen']]
first_name = input_list[0]
last_name = input_list[1]

name = list(map(lambda x,y:x+" "+y,first_name,last_name))

print(name)


```

    ['Ankur Narang', 'Avik Sarkar', 'Kiran R', 'Nitin Sareen']


### Filter

**'Filter'** is a similar operation, but it requires the function to look for a condition and then, only returns those elements from the collection that satisfy the condition. As the name suggests, **filter creates a list of elements for which a function returns true** i.e.subset of the input list.Its a built-in function in python

**'Reduce'** is an operation that breaks down the entire process into pair-wise operations and uses the result from each operation, with the successive element.It is NOT a built-in function in python




```python
#Filter
divby3 = lambda x:  x % 3 == 0
my_list = [3,4,5,6,7,8,9]
div = filter(divby3, my_list)
print(list(div))


```

    [3, 6, 9]



```python
number_list = range(-5, 5)
less_than_zero = list(filter(lambda x: x < 0, number_list))
print(less_than_zero)
```

    [-5, -4, -3, -2, -1]


### Filter Function

Qs: Extract a list of numbers that are multiples of 5 from a list of integers named input_list.


```python
input_list=[1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50]

list_answer = list(filter(lambda x:x%5==0,input_list))

print(list_answer)
```

    [5, 10, 15, 20, 25, 30, 35, 40, 45, 50]


Qs:You are given a list of strings such as `input_list =['soap','sharp','shy','silent','ship','summer','sheep']`.

Extract a list of names that start with an ‘s’ and end with a ‘p’ (both 's' and 'p' are lowercase) in input_list.


```python
input_list =['soap','sharp','shy','silent','ship','summer','sheep']

sp = list(filter(lambda x:x.startswith('s')and x.endswith('p'),input_list))

print(sp)
```

    ['soap', 'sharp', 'ship', 'sheep']



```python
#Reduce
from functools import reduce
q  = reduce(lambda x, y: x+y, range(1,4))
print(q)

```

    6



```python
list_of_nums = [22,45,32,20,87,94,30]
print(reduce(lambda x,y: x if x>y else y,list_of_nums))

```

    94


### Reduce Function

Qs:Using the Reduce function, concatenate a list of words in input_list, and print the output as a string.  
If `input_list = ['I','Love','Python']`, the output should be the string 'I Love Python'.




```python
from functools import reduce

input_list=['All','you','have','to','fear','is','fear','itself']

concat=reduce(lambda x, y: x+" "+y, input_list)

print(concat)
```

    All you have to fear is fear itself



```python
## Qs:You are given a list of numbers such as input_list = [31, 63, 76, 89]. 
#Find and print the largest number in input_list using the reduce() function.

input_list = [31, 63, 76, 89]

answer = reduce(lambda x,y: x if x>y else y,input_list)

print(answer)
```

    89


### Additional Reading

- [Lambda, Reduce, Filter, and Map](https://www.python-course.eu/lambda.php)   
- [Python tips](http://book.pythontips.com/en/latest/map_filter.html)

## Practice Questions I


```python
## Python Operators

# Qs:What will the output be of ((500//7) % 5) ** 3?

((500//7) % 5) ** 3

# Ans: (500//7) means integer division. Hence, you will get 71.
#71 % 5 will return the remainder when 71 is divided by 5. Hence, you will get 1.
#1 ** 3 will return 1 raised to the third power. Hence, you will get 1
```




    1




```python
## Indexing

# Qs; How will you extract ‘love’ from the string S = “I love Python”?

S = 'I love Python'

S[2:6]
# Ans: The substring ‘love’ in S starts from index 2 and goes up to index 5. 
#Hence, you need to write ‘S[2:6]’ to extract it, since the last index mentioned, i.e. 6, will be excluded by default.
```




    'love'




```python
S[-11:-7]
# Ans: Alternatively, you can also use negative indexing in Python, with the last index being ‘-1’. 
#Hence, by using a negative index, you can extract ‘love’ by writing ‘S[-11:-8]’.
```




    'love'




```python
## List Multiplication

# Qs:If you have a list L = [1, 2, 3], what will the output of L * 2 be?

L = [1, 2, 3]
L * 2
# Ans:L * 2 will replicate all the elements present in the list twice. Hence, you will get [1, 2, 3, 1, 2, 3] as the output.
```




    [1, 2, 3, 1, 2, 3]




```python
## List Slicing

# Qs: If you have a list L = [[1, 2, 3], [4, 5, 6], [7, 8, 9, 10]], what will the output of L[2: ] be?

L = [[1, 2, 3], [4, 5, 6], [7, 8, 9, 10]]
L[2: ]

# Ans:Since this is a nested list, L[2: ] will return all the lists, starting from index 2, and
#since the list present at index 2 is [7, 8, 9, 10] and there are no lists after it, it will return [[7, 8, 9, 10]].
```




    [[7, 8, 9, 10]]




```python
# If you have a tuple T = (3, 5, 7, 11), what will the output of T.append(9) be?
T = (3, 5, 7, 11)
T.append(9)

# Ans:Tuples are immutable, i.e. once a tuple is created, you cannot alter it. 
#This is why if you attempt to append a value to the tuple in the question, Python will throw an error.
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    <ipython-input-80-9316ad82bac8> in <module>()
          1 # If you have a tuple T = (3, 5, 7, 11), what will the output of T.append(9) be?
          2 T = (3, 5, 7, 11)
    ----> 3 T.append(9)
          4 
          5 # Ans:Tuples are immutable, i.e. once a tuple is created, you cannot alter it.


    AttributeError: 'tuple' object has no attribute 'append'



```python
## Dictionary Iteration

# Qs; What will the output be of the following code?

D = {1:['Raj', 22], 2:['Simran', 21], 3:['Rahul', 40]}
for val in D:
     print(val)
        
# Ans: By default, iteration in a dictionary is done over the keys of the dictionary. 
#Hence, the code will return ‘1, 2, 3’. The name of the variable used for the iteration (‘val’, in this case) is insignificant.

```

    1
    2
    3


### Python Comprehensions

#Qs:What will the ‘comprehension equivalent’ be for the following snippet of code?

`for sentence in paragraph:
    for word in sentence.split():
        single_word_list.append(word)`



```python
single_word_list=[]
paragraph=['I love Python language']

for sentence in paragraph:
    for word in sentence.split():
        single_word_list.append(word)
        
print(single_word_list)
```

    ['I', 'love', 'Python', 'language']



```python
# Using list comprehension
[word for sentence in paragraph for word in sentence.split()]

# Ans:[word for sentence in paragraph for word in sentence.split()] is the right comprehension equivalent of the code 
#provided. You need to put it in square brackets [] since the output will be a list.
```




    ['I', 'love', 'Python', 'language']




```python
# Function Arguments

# Qs:What will the output of the following code be?

def my_func(*args):
    return(sum(args))

print(my_func(1,2,3,4,5))
print(my_func(6,7,8))

# Ans:Using ‘*args’ as an argument for a function in Python enables you to pass as many arguments as you desire. 
#Hence, Python will compute the function, no matter if the argument has five elements or three or any other number of 
#elements.

```

    15
    21



```python
# Operations on a List

# Qs:Which of the following commands will output the squares of all the numbers in a list L = [1, 2, 3, 4]?

L = [1, 2, 3, 4]
squared=list(map(lambda x : x ** 2, L))
print(squared)

## Ans: list(map(lambda x : x ** 2, L)) will output the squares of all the numbers. However, just map(lambda x : x ** 2, L) 
#will only perform the required task and won’t output the list. It will just return the ID number where the result 
#is stored. Hence, you need to use the ‘list()’ command along with it, to get the required result.
```

    [1, 4, 9, 16]


### Practice Questions II

### Factorial

Qs: Given a number ‘n’, output its factorial using reduce().
Note: Make sure you handle the edge case of zero. As you know, 0! = 1



```python
n = int(input())

# Import the reduce() function
from functools import reduce

f=lambda x,y:x*y

def factorial(number):
    if(number==0): 
        return 1 
    else: 
        return reduce(f,range(1,number+1))

print(factorial(n))

```

    6
    720


### Set Operations

Qs: In a school, there are total 20 students numbered from 1 to 20. You’re given three lists named ‘C’, ‘F’, and ‘H’, representing students who play cricket, football, and hockey, respectively. Based on this information, find out and print the following:   

    `Students who play all the three sports  
    Students who play both cricket and football but don’t play hockey  
    Students who play exactly two of the sports  
    Students who don’t play any of the three sports  `

Format:  
Input:  
Line 1 : The number of students 'n'.  
Remaining Lines: 3 lists containing numbers (ranging from 1 to n) representing students who play cricket, football and hockey respectively.  
Output:   
4 different lists containing the students according to the constraints provided in the questions.  

Note: Make sure you sort the final lists (in an ascending order) that you get before printing them; otherwise your answer might not match the test-cases.

Examples:
Input 1:
`[2, 5, 9, 12, 13, 15, 16, 17, 18, 19]  
[2, 4, 5, 6, 7, 9, 13, 16]  
[1, 2, 5, 9, 10, 11, 12, 13, 15]   
Output 1:  
[2, 5, 9, 13]  
[16]    
[12, 15, 16]   
[3, 8, 14, 20]`  

Explanation:  

1.Given the three sets, you can see that the students numbered '2', '5', '9', and '13' play all the three sports.   
2. The student numbered '16' plays cricket and football but doesn't play hockey.   
3. The student numbered '12' and '15' plays cricket and hockey and the student numbered '16' plays cricket and football.   There are no students who play only football and hockey. Hence, the students who play exactly two sports are 12, 15, and 16.  
4. As you can see, the students who play none of the sports are 3, 8, 14, and 20.  


```python
input_list=[[2, 5, 9, 12, 13, 15, 16, 17, 18, 19], [2, 4, 5, 6, 7, 9, 13, 16], [1, 2, 5, 9, 10, 11, 12, 13, 15]]

C = set(input_list[0])
F = set(input_list[1])
H = set(input_list[2])
A= set(range(1, 21))

print(sorted(list(C & F & H)))
print(sorted(list((C & F) - H)))
print(sorted(list((C|F|H) - (C^F^H))))
print(sorted(list(A-(C|F|H))))
```

    [2, 5, 9, 13]
    [16]
    [12, 15, 16]
    [3, 8, 14, 20]



```python
# Aliter
input_list=[[2, 5, 9, 12, 13, 15, 16, 17, 18, 19], [2, 4, 5, 6, 7, 9, 13, 16], [1, 2, 5, 9, 10, 11, 12, 13, 15]]

C = set(input_list[0])
F = set(input_list[1])
H = set(input_list[2])
A= set(range(1, 21))

print(sorted(list((C.intersection(F)).intersection(H))))
print(sorted(list((C.intersection(F)).difference(H))))
print(sorted(list((C.union(F).union(H)).difference(C.symmetric_difference(F).symmetric_difference(H)))))
print(sorted(list(A.difference(C.union(F).union(H)))))

```

    [2, 5, 9, 13]
    [16]
    [12, 15, 16]
    [3, 8, 14, 20]

