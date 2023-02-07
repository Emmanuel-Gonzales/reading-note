# Basics of HTML, CSS & JS

## Intro to HTML

* **Semantic** elements are used to divide up the page, they are useful to the browser and the developer. Semantic tags are used to divide the page into sections based on the content inside. < header >
tags usually contain the title and navigation of the page, the < body > contains the all of the viewable page, the < footer > is the bottom etc.

* There are 6 levels of **headings** in HTML.

* The < sub > and < sup > tags are used when you want to shrink a piece of text next to a word. < sub > places the text at the bottom of the sentence and < sup > places the text at the top. They are used for marking up item next to dates chemical numbers and more. EX: 25**th** or CO**3**.

* < abbr > is used with abbreviations and acronyms if the developer adds the **title** value to < abbr >, plus the full version of the word, it will allow the user to see the full word of the abbreviation by hovering the mouse over the word.  

EX:  This is the < abbr title="Abbreviation" >abb< /abbr > of a word.

## Learn CSS

* How to apply CSS to HTML
  
  * **Internal** - Putting a < style > tag in the < head > section then writing CSS code in inbetween thoes tags.

  * **External** - Placing a < link > tag in the < head > section and pasting a link to a seperate CSS file
 
  * **Inline** - Using a style atribute inside a HTML tag

* You want to stay away from using inline styles as much as posible because it involves mixing CSS and HTML code together making harder to read

* Look at this CSS code 

   h2 {
    
     color: black;
    
     padding: 5px;
   
   }
   
   * The "h1" is the selector

   * "color: black" and "padding: 5px" are the declorations

   * "color" and "padding" are properties

## JavaScript

* A **string** is a sequence of text surounded by quotes

* Operators

  * (+) Plus operators - Adds numbers and combines strings

  * (=) Assignment - Assigns a value to a veriable

  * (&&) Logical And - Allows you to chain two or more expressions together so that both of them have to be true

  * You can make your code shorter using functions.

* An if statement checks a **condition** and if it evaluates to **true** then the code block will execute.

* Am else is statement is used at the end of an if chain, if none of the conditions are met then this is the last resort.

* The three different types of comparison operators are logical AND, logical OR, and logical Not

* When a logical AND (&&) is used BOTH conditions must be true, and with a logical OR (||) at least one condition must be true.