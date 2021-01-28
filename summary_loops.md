At the most basic level, you can
evaluate two variables using a
comparison operator to return a
t rue or f al se value.
In this example, a user is taking a
test, and the script te lls the user
whether they have passed this
round of the test.
The example starts by setting
two variables:
1. pass to hold the pass mark
2. score to hold the users score
To see if the user has passed,
a comparison operator checks
whether score is greater than or
equal to pass. The result will be
true or false, and is stored in
a variable called has Passed. On
the next line, the result is written
to the screen.
The last two lines select the
element whose id attribute
has a value of answer, and then
updates its contents. You will
learn more about this technique
in the next chapter.

Functions allow you to group a set of related
statements together that represent a single task.
Functions can take parameters (informatiorJ required
to do their job) and may return a value.
An object is a series of variables and functions that
represent something from the world around you.
In an object, variables are known as properties of the
object; functions are known as methods of the object.
Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window.
JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.
Arrays and objects can be used to create complex data
sets (and both can contain the other).



A for loop is often used to loop
through the items in an array.
In this example, the scores for
each round of a test are stored in
an array called scores.
The total number of items in
the array is stored in a variable
called arrayl ength. This
number is obtained using the
l ength property of the array.
There are three more variables:
roundNumber holds the round of
the test; msg holds the message
to display; i is the counter
(declared outside the loop).
The loop starts with the for
keyword, then contains the
condition inside the parentheses.
As long as the counter is less
than the total number of items
in the array, the contents of the
curly braces will continue to
run. Each time the loop runs, the
round number is increased by 1.
Inside the curly braces are rules
that write the round number and
the score to the msg variable. The
variables declared outside of the
loop are used within the loop.
The msg variable is then written
into the page. It contains HTML
so the i nnerHTML property is
used to do this. Remember,
p228 will talk about security
issues relating to this property.


Here is an example of awhile
loop. It writes out the 5 times
table. Each time the loop is run,
another calculation is written
into the variable called msg.
This loop will continue to run
for as long as the condition in
the parentheses is true. That
condition is a counter indicating
that, as long as the variable
i remains less than 10, the
statements in the subsequent
code block should run.
Inside the code block there are
two statements:
The first statement uses the+=
operator, which is used to add
new content to the msg variable.
Each time the loop runs, a new
calculation and line break is
added to the end of the message
being stored in it. So+" works as
a shorthand for writing:
msg = msg + 'new msg'
(See bottom of the next page for
a breakdown of this statement.)
The second statement
increments the counter variable
by one. (This is done inside
the loop rather than with the
condition.)
When the loop has finished, the
interpreter goes to the next line
of code, which writes the msg
variable to the page.














