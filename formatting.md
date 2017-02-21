# Formatting

Formatting code is a good way of making it more readable as well as some other benefits.

# What is formatting?

Formatting is the use of spacing and new lines to layout code for aesthetic and functional benefit. If code were to be written all on one line with no spaces it would be much more difficult to read.

**Example**

`<div><ul><li><a href='#>Hello</a></li></ul></div>`

vs.

`<div>      
     <ul>      
         <li>      
             <a href='#'>Hello</a>      
         </li>      
     </ul>      
 </div>`

# Code Collapsing

If code is formatted as in the above example, many code editors allow for code collapsing. Code collapsing is when all the contents of an indented section of code are hidden. This can help to remove code from view that is currently not being worked on.

**Example**

`line 1:  function add(){    
 line 6:  }    
 line 7:    
 line 8:  function save(record){    
 line 9:     validate_fields(record);    
 line 10:    database_save(record);    
 line 11:    return record;    
 line 12: }`

In this example there is code within the add function but, because it has been indented, the code editor is able to hide lines 2-5. The person writing the code can more easily concentrate on the 'save' function.

# Formatted languages

Some languages require formatting for them to be parsed correctly. This allows for code to be written much faster and look very clean.

**Example**

HTML

`<div class='container'>      
     <ul id='main_list>      
         <li>      
             <a href='#'>Hello</a>      
         </li>      
     </ul>      
 </div>`

HAML

`.container    
    ul#mainlist    
        li    
            a{:href='#'} Hello`

In this example the HTML has been rewritten in HAML. HAML is an abstracted version of HTML. It takes less code and looks much cleaner than the HTML version. HAML uses indentation and line breaks as ways of knowing when an element is finished so explicit closure is not required.

A formatting policy can help a person know how to format code in a particular situation. Should they put a space before a bracket or before a function call. This may not solve any major issues but can save time when deciding what should be done.

