---
marp: true
title: "Code Readability"
paginate: false
theme: custom
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')

---

# Code readability
#### Who is the audience that will read your code?

>Code is for computer, comments are for humans.

Do you agree with this statement?

---

# Code readability

- ~~Code is for computer, comments are for humans.~~

- Use whitespace and newlines strategically.

---

#### Compare:

```python
if foo == 'blah': do_blah_thing()
do_one(); do_two(); do_three()
```
**with**
```python
if foo == 'blah':
    do_blah_thing()

do_one()
do_two()
do_three()
```

Compound statements are generally discouraged, make generous use of newlines

---

# Code readability

- ~~Code is for computer, comments are for humans.~~

- Use whitespace and newlines strategically.

- use descriptive names for functions and variables
  - start functions with a verb
  - make variable names _just_ long enough to be meaningful

---

# Code readability
**Compare**

```r
for i in my_shopping_basket:
  if(test(i)) > 10:
    purch(i)
  else:
    disc(i)
```
**with**
```r
for item in basket:
  if(testNecessity(item)) > 10:
    purchase(item)
  else:
    discard(item)
```

---

# Code readability

- ~~Code is for computer, comments are for humans.~~

- Use whitespace and newlines strategically.

- use descriptive names for functions and variables
  - start functions with a verb
  - make variable names _just_ long enough to be meaningful

- use a consistent style 
  - consistency will make your code easier to understand and maintain
  - consult a styleguide for your language (keep conventions, and don't reinvent the wheel)
  
---

# Variable naming
Compare:

```python
myVar = original_variable + MOD(new.var)
```
with

```python
my_var = original_var + Modified(new_var)
```
_consistency is key!_

---

# Comments
- Comments that contradict the code are worse than no comments. Always make a priority of keeping the comments up-to-date when the code changes! 
- Ensure that your comments are clear and easily understandable to other speakers of the language you are writing in (ENGLISH!)
- Delete commented code 
- Inline comments are unnecessary and in fact distracting if they state the obvious. 

---

Don’t do this
```python
x = x + 1                 # Increment x
```
This is more useful
```python
x = x + 1                 # Compensate for border
```
