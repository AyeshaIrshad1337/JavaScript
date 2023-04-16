# JavaScript
<h2>Declare JavaScript Variables</h2>
<p>In computer science, data is anything that is meaningful to the computer. JavaScript provides eight different data types which are undefined, null, boolean, string, symbol, bigint, number, and object.</p>
<p>For example, computers distinguish between numbers, such as the number 12, and strings, such as "12", "dog", or "123 cats", which are collections of characters. Computers can perform mathematical operations on a number, but not on a string.</p>
<p>Variables allow computers to store and manipulate data in a dynamic fashion. They do this by using a "label" to point to the data rather than using the data itself. Any of the eight data types may be stored in a variable.</p>
<p>We tell JavaScript to create or declare a variable by putting the keyword var in front of it, like so:</p>
<code>var ourName;</code>
  
<h2>Storing Values with the Assignment Operator</h2>
<p>n JavaScript, you can store a value in a variable with the assignment operator (=).</p>
<code>myVariable = 5;</code>
<p>This assigns the Number value 5 to myVariable.</p>

<p>If there are any calculations to the right of the = operator, those are performed before the value is assigned to the variable on the left of the operator.
</p>
<code>
var myVar;
myVar = 5;
</code>
<p>
First, this code creates a variable named myVar. Then, the code assigns 5 to myVar. Now, if myVar appears again in the code, the program will treat it as if it is 5.</p>
<br>
<h2>Assigning the Value of One Variable to Another</h2>
<p>After a value is assigned to a variable using the assignment operator, you can assign the value of that variable to another variable using the assignment operator.</p>
<code>var myVar;
myVar = 5;
var myNum;
myNum = myVar;</code>
<p>The above declares a myVar variable with no value, then assigns it the value 5. Next, a variable named myNum is declared with no value. Then, the contents of myVar (which is 5) is assigned to the variable myNum. Now, myNum also has the value of 5.</p>
<br>
<h2>Initializing Variables with the Assignment Operator</h2>
<p>It is common to initialize a variable to an initial value in the same line as it is declared.</p>
<code> var myVar = 0;</code>
<p>
Creates a new variable called myVar and assigns it an initial value of 0.</p>
<br>
<h2>Declare String Variables</h2>
<p> you can also declare a string variable like this:</p>
<code>var myName = "your name";</code>
<p>"your name" is called a string literal. A string literal, or string, is a series of zero or more characters enclosed in single or double quotes.</p>
<br>
<h2>Understanding Uninitialized Variables</h2>
<p>When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number". If you concatenate a string with an undefined variable, you will get a string of undefined.</p>
