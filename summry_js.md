
# WRITING A
# SCRIPT
To write a script, you need to first
state your goal and then list the
tasks that need to be completed in
order to achieve it.
Humans can achieve complex goals without thinking
about them too much, for example you might be
able to drive a car, cook breakfast, or send an email
without a set of detailed instructions. But the first
time we do these things they can seem daunting.
Therefore, when learning a new skill, we often break
it down into smaller tasks, and learn one of these at
a time. With experience these individual tasks grow
familiar and seem simpler.
Some of the scripts you will be reading or writing
when you have fin ished this book will be quite
complicated and might look intimidating at
first. However, a script is just a series of short
instructions, each of which is performed in order
to solve the problem in hand. This is why creating a
script is like writing a recipe or manual that allows a
computer to solve a puzzle one step at a time.
It is worth noting, however, that a computer doesn't
learn how to perform tasks like you or I might; it
needs to follow instructions every time it performs
the task. So a program must give the computer
enough detail to perform the task as if every time
were its first time.


Start with the big picture of what
you want to achieve, and break
that down into smaller steps.
## 1: DEFINE THE GOAL
First, you need to define the task you want to
achieve. You can think of this as a puzzle for the
computer to solve.
## 2: DESIGN THE SCRIPT
To design a script you split the goal out into a series
of tasks that are going to be involved in solving this
puzzle. This can be represented using a flowchart.
You can then write down individual steps that the
computer needs to perform in order to complete
each individual task (and any information it needs to
perform the task), rather like writing a recipe that it
can follow.
## 3: CODE EACH STEP
Each of the steps needs to be written in a
programming language that the compu ter
understands. In our case, this is JavaScript.
As tempting as it can be to start coding straight
away, it pays to spend time designing your script
before you start writing it.



# ARRAYS
An array is a special type of variable. It doesn't
just store one value; it stores a list of values.
You should consider using an
array whenever you are working
with a list or a set of values that
are related to each other.
Arrays are especially helpful
when you do not know how
many items a list will contain
because, when you create the
array, you do not need to specify
how many values it will hold.
If you don't know how many
items a list will contain, rather
than creating enough variables
for a long list (when you might
only use a small percentage
of them), using an array is
considered a better solution.
For example, an array can be
suited to storing the individual
items on a shopping list because
it is a list of related items.
Additionally, each time you write
a new shopping list, the number
of items on it may differ.
As you will see on the next page,
va lues in an array are separated
by commas.
In Chapter 12, you will see that
arrays can be very helpful when
representing complex data.

# VALUES IN ARRAYS
Values in an array are accessed as if they are in
a numbered list. It is important to know that the
numbering of this list starts at zero (not one).
NUMBERING ITEMS IN
AN ARRAY
Each item in an array is
automatically given a number
called an index. This can be used
to access specific items in the
array. Consider the following
array which holds three colors:
var col ors;
colors= ['whi te ' ,
'black ' ,
' custom'];
Confusingly, index values start at
0 (not 1), so the following table
shows items from the array and
their corresponding index values:
INDEX VALUE
o 'white '
'bl ack'
2 ' custom'
ACCESSING ITEMS IN
AN ARRAY
To retrieve the third item on the
list, the array name is specified
along with the index number in
square brackets.
Here you can see a variable
called i temThree is declared.
Its value is set to be the third
color from the co 1 ors array.
var itemThr ee;
itemThree = col ors [ 2] ;
0 BASIC JAVASCRIPT INSTRUCTIONS
NUMBER OF ITEMS IN
AN ARRAY
Each array has a property called
length, which holds the number
of items in the array.
Below you can see that a variable
called numCo 1 ors is declared. Its
value is set to be the number of
the items in the array.
The name of the array is
followed by a period symbol (or
full stop) which is then followed
by the 1 ength keyword.
var numColors ;
numColors =col ors. length;


