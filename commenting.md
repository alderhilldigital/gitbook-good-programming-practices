# Commenting

Commenting is one of the most important practices when engaging in a development project, especially when the project involves other people. It is also one of the practices that is commonly overlooked by many developers.

### What are comments?

Code can sometimes be difficult to follow and real language can help with people's understanding. Comments are descriptions that are appended or prepended to code that explain what the code does. Comments have no affect on how the code executes and are ignored by many compilers and interpreters.

### How to comment

Comments have to common forms, inline and block. Inline comments usually have a character or character sequence that is used to initiate the comment. Inline comments can be used on a line on their own or at the end of a line of code.

**Example**

`// This function does something      
function does_stuff()`

or

`print "hello" // this prints hello`

In these examples the comment is initiated with a double forward slash '//'.

The other type of comments are block comments. Block comments also have a initiating character sequence but instead of the comment ending when a new line occurs, they require a terminating character sequence.

**Example**

`/*      
We can write a comment.      
It can have multiple lines.      
Then it is closed at the end      
*/`

In this example the comment is initiated with a forward slash followed by an asterisk '/\*'. The comment is then terminated with a asterisk followed by a forward slash '\*/'.

### Benefits of Commenting

The main benefit of commenting is to help people understand what the code is doing. Some programmers believe that comments should not explain how the code works but should explain what the code does and why it does it. Comments that explain how the code works could be superfluous or could be compensating for code that is overly complex or badly implemented. Therefore comments should be as brief and concise as possible to quickly facilitate understanding.

Another benefit of commenting is the automatic generation of documentation. There are many tools now available that parse files in an application and extract the comments. The comments are then collated and formatted into documentation for the application. Since many projects require documentation to be provided, commenting and generating the documentation automatically can be an effective and efficient way of doing this.

One use of comments is when debugging code. If a particular piece of code has been implemented and has caused a nondescript error then comments are sometimes used to remove individual sections or lines of code to help isolate the error.

**Example**

`var itemone = 'hello'  
var itemtwo = 'world'  
if(itemone == 'hello') { print 'success' }  
// if(itemthree == 'world') { print 'more success' }`

In this example the fourth line is commented as it was causing an error because the 'itemthree' variable doesn't exist.



