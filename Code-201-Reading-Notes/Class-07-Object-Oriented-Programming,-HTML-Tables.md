# Object-Oriented Programming, HTML Tables

- Domain Modeling is a helpful because it can help you to plan out your program and can help break down long complicated code into more condensed readable code that you can write.

## Tables 

- Tables should not be used to write out entire websites because we have now have better tags we can use to sttructure websites that is easier to read and more condensed. Tables are strucred in rows and cells so they can be very resrictive when planning out non tabular data

- < tr > is the table row, this element makes a new row in the table. < th > (table header) makes the first cell in a row, acts as a h1 element. < td > makes a generic table cell in the row.

## Constructors

- Constructor functions are functions that also act as objects. They are more useful than object literals because they can be replicated easier assining a variable as a new function() and adding the custon properties in the brackets.

- Since the objects are stored in functions we need to assign the properties in different ways. We use the = operator "this.". this.name = name.

## Prototypes

- Imagine you have a set of triplets and you need to name them. You need to sign each birth certificate with a name so you make a constructor function to name them. function Triplet(name, gender){}. After assigning three new variables to three new Triplet() constructors (you name the three babies), you decide to make a prototype to help the sign the birth certificates. function sign(){ `This childs name is ${this.name}`}. The you would call the prototype with the constroctor.
