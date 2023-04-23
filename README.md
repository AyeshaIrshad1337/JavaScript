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
<br>
<h2>Understanding Case Sensitivity in Variables</h2>
<p>In JavaScript all variables and function names are case sensitive. This means that capitalization matters. MYVAR is not the same as MyVar nor myvar. It is possible to have multiple distinct variables with the same name but different casing. It is strongly recommended that for the sake of clarity, you do not use this language feature.</p>
<h3>Best Practice</h3>
<p>Write variable names in JavaScript in camelCase. In camelCase, multi-word variable names have the first word in lowercase and the first letter of each subsequent word is capitalized.</p>

<br>
<code>var someVariable;
var anotherVariableName;
var thisVariableNameIsSoLong;</code>
<br>
<h2>Explore Differences Between the var and let Keywords</h2>
<p>One of the biggest problems with declaring variables with the var keyword is that you can easily overwrite variable declarations:</p>
<code>var camper = "James";
var camper = "David";
console.log(camper);</code>
<br>
<p>In the code above, the camper variable is originally declared as James, and is then overridden to be David. The console then displays the string David.</p>
<p>In a small application, you might not run into this type of problem. But as your codebase becomes larger, you might accidentally overwrite a variable that you did not intend to. Because this behavior does not throw an error, searching for and fixing bugs becomes more difficult.</p>
<p>A keyword called let was introduced in ES6, a major update to JavaScript, to solve this potential issue with the var keyword..if you replace var with let in the code above, it results in an error:</p>
<code>let camper = "James";
let camper = "David";
</code>
<br>
<p>The error can be seen in your browser console.

So unlike var, when you use let, a variable with the same name can only be declared once.</p>
<br>
<h2>Declare a Read-Only Variable with the const Keyword</h2>
<p>The keyword let is not the only new way to declare variables. In ES6, you can also declare variables using the const keyword.
<br>
const has all the awesome features that let has, with the added bonus that variables declared using const are read-only. They are a constant value, which means that once a variable is assigned with const, it cannot be reassigned</p>
<br>
<code>const FAV_PET = "Cats";
FAV_PET = "Dogs";</code>
<br>
<p>The console will display an error due to reassigning the value of FAV_PET.
<br>
You should always name variables you don't want to reassign using the const keyword. This helps when you accidentally attempt to reassign a variable that is meant to stay constant.
<br>
<b>Note:</b> It is common for developers to use uppercase variable identifiers for immutable values and lowercase or camelCase for mutable values (objects and arrays). You will learn more about objects, arrays, and immutable and mutable values in later challenges. Also in later challenges, you will see examples of uppercase, lowercase, or camelCase variable identifiers.</p>
<br>
<h2>Add Two Numbers with JavaScript</h2>
<p>Number is a data type in JavaScript which represents numeric data.
<br>
Now let's try to add two numbers using JavaScript.
<br>
JavaScript uses the + symbol as an addition operator when placed between two numbers.</p>
<code>const myVar = 5 + 10;</code>
<br>
<h2>Subtract One Number from Another with JavaScript</h2>
<br>
<p>We can also subtract one number from another.
<br>
JavaScript uses the - symbol for subtraction.</p>
<code>const myVar = 12 - 6;</code>
<br>
<h2>Multiply Two Numbers with JavaScript
</h2>
<br>
<p>We can also multiply one number by another.
<br>
JavaScript uses the * symbol for multiplication of two numbers.</p>
<code>const myVar = 13 * 13;</code>
<br>
<h2>Divide One Number by Another with JavaScript</h2>
<br>
<p>We can also divide one number by another.
<br>
JavaScript uses the / symbol for division.</p>
<code>const myVar = 16 / 2;</code>
<br>
<h2>Increment a Number with JavaScript</h2>
<br>

<p>You can easily increment or add one to a variable with the ++ operator.</p>
<br>
<code>i++;</code>
<p>is equivalent to </p>
<br>
<code>i = i + 1;</code>
<br>

<h2>Decrement a Number with JavaScript</h2>
<br>

<p>You can easily decrement or decrease a variable by one with the -- operator.</p>
<br>
<code>i--;</code>
<p>is equivalent to </p>
<br>
<code>i = i - 1;</code>
<br>
<h2>Create Decimal Numbers with JavaScript</h2>
<br>
<p>We can store decimal numbers in variables too. Decimal numbers are sometimes referred to as floating point numbers or floa</p>
<br>
<h2>Multiply Two Decimals with JavaScript</h2>
<br>
<p>In JavaScript, you can also perform calculations with decimal numbers, just like whole numbers.</p>
<br>
<h2>Finding a Remainder in JavaScript</h2>
<br>
<p>The remainder operator % gives the remainder of the division of two numbers.

Example:  

5 % 2 = 1  
5 / 2 = 2 remainder 1  
2 * 2 = 4  
5 - 4 = 1  

 Usage  
  
 In mathematics, a number can be checked to be even or odd by checking the remainder of the division of the number by 2. Even numbers have a remainder of 0, while odd numbers a remainder of 1.  
  
17 % 2 = 1  
48 % 2 = 0  
  <b>Note:</b>   
 The remainder operator is sometimes incorrectly referred to as the modulus operator. It is very similar to modulus, but does not work properly with negative numbers.</p>
<br>

<h2>Compound Assignment With Augmented Addition</h2>
<br>
<p>In programming, it is common to use assignments to modify the contents of a variable. Remember that everything to the right of the equals sign is evaluated first, so we can say:</p>
<br>
<code>myVar = myVar + 5;</code>
<p>to add 5 to myVar. Since this is such a common pattern, there are operators which do both a mathematical operation and assignment in one step.  
  
One such operator is the += operator.

</p>
<br>
<code>let myVar = 1;
myVar += 5;
console.log(myVar);</code>
<p>6 would be displayed in the console.</p>
<br>


<h2>Compound Assignment With Augmented Subtraction</h2>
<br>
<p>Like the += operator, -= subtracts a number from a variable.</p>
<br>
<code>myVar = myVar - 5;</code>
<p>will subtract 5 from myVar. This can be rewritten as:</p>
<br>
<code>myVar -= 5;</code>
<p>Convert the assignments for a, b, and c to use the -= operator.</p>
<br>

<h2>Compound Assignment With Augmented Multiplication</h2>
<br>
<p>The *= operator multiplies a variable by a number.</p>
<br>
<code>myVar = myVar * 5;</code>
<p>will multiply myVar by 5. This can be rewritten a</p>
<br>
<code>myVar *= 5;</code>
<br>


<h2>Compound Assignment With Augmented Division</h2>
<br>
<p>The /= operator divides a variable by another number.</p>
<br>
<code>myVar = myVar / 5;</code>
<p>Will divide myVar by 5. This can be rewritten as:</p>
<br>
<code>myVar /= 5;</code>

<br>

<h2>Escaping Literal Quotes in Strings</h2>
<p>When you are defining a string you must start and end with a single or double quote. What happens when you need a literal quote: " or ' inside of your string?  
  
In JavaScript, you can escape a quote from considering it as an end of string quote by placing a backslash (\) in front of the quote.</p>
<code>const sampleStr = "Alan said, \"Peter is learning JavaScript\".";</code>
<br>
<p>This signals to JavaScript that the following quote is not the end of the string, but should instead appear inside the string. So if you were to print this to the console, you would get:</p>
<br>
<code>Alan said, "Peter is learning JavaScript".</code>
<br>
<h2>Quoting Strings with Single Quotes</h2>
<p>String values in JavaScript may be written with single or double quotes, as long as you start and end with the same type of quote. Unlike some other programming languages, single and double quotes work the same in JavaScript.</p>
<code>const doubleQuoteStr = "This is a string"; 
const singleQuoteStr = 'This is also a string';</code>
<p>The reason why you might want to use one type of quote over the other is if you want to use both in a string. This might happen if you want to save a conversation in a string and have the conversation in quotes. Another use for it would be saving an <a> tag with various attributes in quotes, all within a string.</p>
 <code>const conversation = 'Finn exclaims to Jake, "Algebraic!"';</code>
  <p>However, this becomes a problem if you need to use the outermost quotes within it. Remember, a string has the same kind of quote at the beginning and end. But if you have that same quote somewhere in the middle, the string will stop early and throw an error.</p>
  <code>const goodStr = 'Jake asks Finn, "Hey, let\'s go on an adventure?"'; 
const badStr = 'Finn responds, "Let's go!"';</code>
  <p>Here badStr will throw an error.  
  
In the goodStr above, you can use both quotes safely by using the backslash \ as an escape character.  
  
<b>Note: The backslash \ should not be confused with the forward slash /. They do not do the same thing.</b></p>
  <h2>Escape Sequences in Strings</h2>
  <p>Quotes are not the only characters that can be escaped inside a string. Escape sequences allow you to use characters you may not otherwise be able to use in a string.</p>
 <table>
<tr>
  <th>Code</th>
  <th>Output</th>
 </tr>
  
<tr>
  <td><code>\'</code></td>
  <td>Single Quoe</td>
 </tr>
  
<tr>
  <td><code>\"</code></td>
  <td>Double Quote</td>
 </tr>
<tr>
  <td><code>\\</code></td>
  <td>backslash</td>
 </tr>
<tr>
  <td><code>\n</code></td>
  <td>newline</td>
 </tr>
<tr>
  <td><code>\t</code></td>
  <td>tab</td>
 </tr>
<tr>
  <td><code>\r</code></td>
  <td>carriage return</td>
 </tr>
<tr>
  <td><code>\b</code></td>
  <td>backspace</td>
 </tr>
  
<tr>
  <td><code>\f</code></td>
  <td>form feed</td>
 </tr>
</table>
