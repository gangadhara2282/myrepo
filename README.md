
Data Type 
=========
# int float
# Complex 

#Operator Precedence 
====================

# () ** */ + - 

Variables
========
Snake_case
Start wih lowercase or underscore
Letters,numbers,underscores
Case sensitive
Don't Overwrite Keywords

_ signifies private varible
__ dunder

Constants
=========

Captials name

Expressions and statements
==========================
100/5 --called expresssion
a=100/5 -- whole thing statement

Augmented assignment operator
=============================
a=a+1 -- can be "a +=1" (called assignment operator)

String 
======
String concatenation
Type convertion
escape sequencce \
formatted string
 --add 'f' in beginning of sentence "{}" --pyhton 3 is requried
 -- print( 'hi {} {}' . format('johnny','55'))
string Indexes
   --called order string 
   --print(selfish [0:2:3])--[start:stop:stepover]
Immutability
  --cannot reassign part of string
build in function and methods
  --
Boolean
exsice:password checker : print('*' * 10)


Lists []
=====
List are like arrays

list slicing
============
print(basket[::-1]) 
--reverse the list
--slicing of list  
Matrix
======
 - array inside another array
 matrix = [[1,2,3],[1,2,3],[7,8,9]]
 -used in image processing
 -for pixcel
List methods
============
--we can used the list using . operator
--append method changes in place in changes
--insert modify list in place
--extend,pop,remove,clear,copy,reverse,len(create new copy)
--index(in place),sort(in place),sorted(create new copy)
List patterns
=============

print (list(range(1:100)))
--range
--join(create new copy)
  --convert list into string

List unpacking
==============
a,b,c=[1,2,3]
a,b,c, *other = [1,2,3,4,5,6,7,8]
None
====
var = None
Dictionary {}
==========
dict --data structure
Dictionary keys
Dictionary Methods
Dictionary Method2
Tuples ()
======

Set {}
===
--cannot access index
functions--set(used for convertion from list),len,copy
methods--add,clear
=========================================================

condition logic / LOOPs
=======================
Truthy and falsy
ternary operator 
================
   --shortcut used 
  --example 
      --is_friend = true
  can_message= "messaege allowed" if is_friend else "not allowed"

short circuiting
================

is vs ==
========
is -- evaluates the value in memory

iterable
========
--can be list,dictionary,tuple,set,sting
--one by one check each item in the collection

for item in user.items()-tuple/ user.values / user.keys

range() --produces sequence of integers
=======
enumerate()
===========
functions def sum(n1,n2):
=========
arguments vs parameters 
dflt parametrs and dflt arguments -- keyword arguments
return
Methods vs functions
Doc string def test(): ''' info : hello '''

*args **kwargs
#rule: params, *args,default paramets,**kwargs 
walrus operator :=
scope
global keyword
nonlocal keyword
imposter syndrome
Which collection is ordered, changeable, and allows duplicate members?
Which collection does not allow duplicate members?
OOP (__ dunder methods )
==
Class
=====
__init__,self
decorator-->@classmethod -->cls instead of self && @staticmethod
def
encapsulation --binding of data(blue print)
Abstraction -- hiding the information
	Private(_ means private) and public
Inheritance -- new object form existing objects(object base class/parent/subclass/derived class)
polymorphism
  super()--replacement for self 

object Intersection -- type of an object
  --dir.() --print the dunder methods

Dunder methods
==============
__str__() same str()
__del__
__call__---
__getitem__
MRO --Method resloution order ex:print(d.mro()) or print(d.__mro__)
depth first serch

pure functions
==============

map()
filter()
zip()
reduce()
lamda expressions
List comprehensions (list,set, dictionary)
Decorators '@'
higher order function (HOC)
Generators 
module
PDB -Python debugger import pdb.set_trace()
dynamic binding in c++ at runtime
File I/O--pathlib
regular expressions--special sequence 
https://github.com/aneagoie/pokedex
https://pillow.readthedocs.io/en/stable/
https://www.twilio.com/docs
https://ntfy.sh/
https://pypi.org/project/pyjokes/
https://www.tweepy.org/





