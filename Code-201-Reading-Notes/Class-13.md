# Local Storage and How To Use It On Websites

When you're storing information on a website you can either do it server side or client side. A lot of devolopers prefer local storage because with local storage, if the user resets the page the information can persist. If the user closes the page the information dosen't reset.

Using objects is kind of tricky on local storage since local storage converts everything to strings. Another problem with local storage is that it has been known to be explioted using cookies and other methods to get personal information. That is why you shouldn't store personal information on local storage.

As stated before, local storage stores strings. To convert it to numbers you can use JSON.parse() and to objects use JSON.stringify().
