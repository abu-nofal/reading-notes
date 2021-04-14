# HOW HTML, CSS,& JAVASCRIPT FIT TOGETHER :

Before diving into the JavaScript language, you
need to know how it will fit together with the
HTML and CSS in your web pages. 

- BEHAVIOR LAYER .js files
  - This is where we can change
how the page behaves, adding
interactivity. We will aim to keep
as much of our JavaScript as
possible in separate files. 

> PROGRESSIVE ENHANCEMENT

HTML+CSS+JAVASCRIPT
The JavaScript is added last and enhances the usability of
the page or the experience of interacting with the site.
Keeping it separate means that the page still works if the
user cannot load or run the JavaScript.
You can also reuse the code on several pages
(making the site faster to load and easier to maintain).

> CREATING A BASIC JAVASCRIPT 

JavaScript is written in plain text, just like HTML and CSS,so you do not need any new tools to write a script. This example adds a greeting into an HTML page. 
The greeting changes depending on the time of day. 

- The HTML <script> element is used to load the JavaScript file into the page. It has an attribute called src, whose value is the path to the script you created.
This tells the browser to find and load the script file (just like the src attribute on an <i mg> tag). 

- try opening the
HTML file, removing the src attribute from the opening <script> tag, and adding the new code between the opening <script> tag and the closing </script>tag. 
The s re attribute is no longer needed because the
JavaScript is in the HTML page.

> BASIC JavaScript instruction :

- COMMENTS 
  - You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code.
// or /* */

- VARIABLE
  - A script will have to temporarily store the bits of information it needs to do its job. It can store this
data in variables.
- DATA TYPES 
  - JavaScript distinguishes between numbers,strings, and true or false values known as Booleans.   
     - *NUMERIC DATA TYPE*
The numeric data type handles
numbers. 
     - *STRING DATA TYPE*
The strings data type consists of
letters and other characters.
    - * BOOLEAN DATA TYPE *
Boolean data types can have one
of two values: true or false.

> RULES FOR NAMING VARIABLES

1. The name must begin with a letter, dollar sign ($),or an
underscore (_). It must not start with a number.

2. The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name.

3. You cannot use keywords or reserved words. Keywords
are special words that tell the interpreter to do something. For example, var is a keyword used
to declare a variable. Reserved words are ones that may be used in a future version of JavaScript.
ONLINE EXTRA View a full list of keywords and
reserved words in JavaScript.

4. All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases. 

5. Use a name that describes the kind of information that the variable stores. For example, fi rstName might be used to store a person's first name, l astNarne for their last name, and age for their age. 

6. If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. For example, f i rstName rather
than fi rstnarne (this is referred to as camel case). You can also use an underscore between each
word (you cannot use a dash). 





