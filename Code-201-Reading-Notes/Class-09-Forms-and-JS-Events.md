# Forms and JS Events

## HTML Forms

Forms are one of main ways of interaction between the user and the developer. It's important because it allows user to input data in the website the so it can do user specific functions. It's used to create passwords and usernames, one of the most common forms of identification on the internet.

When making a form it's important to think about the user experience. Make the form big enough and space the promps evenly to help readability. Make it as simple as posible.

The < form > element is responisble for making the form. The label is the prompt/ label for the input section. Input section is where the users puts in some sort of input, such as text. The button element that that usually holds a submit input when clicked, what the button does is usually coded in the JavaScript. And finally when the devoloper wants to give a certin message to the developer, they use < text area. >

## Events

Events are things that happens when the user dose certin things on a webpage. It could be clicking, pressing a button, resizing the window, closing the window etc. When using the proper code you could create a reaction to a certin event in JavaScript.

When using the addEventListener() method requires you to put in the type of event you want it to listen for and function you want to call when the event happens.

The event object is a perameter inside the event handler. The target is used to specify which element in the HTML the event listener listens to.

Event bubbling is what hapens when an event occours in a nested elenent then bubbles outward to it's container element. Event capturing is when a event effects the contianer then goes inward.
