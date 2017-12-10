## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's one difference between ES5 and ES6?  

   string interpolation: `'' + ''` vs. `` `${}` ``  
   
2. What's the difference between asynchronous and synchronous JavaScript?  

   JS runs synchronously through a call stack, but certain methods utilize APIs built into the browser to allow operations that may block the stack to be removed and completed outside the call stack then reinserted once the call stack is clear of other operations.  
   
3. What are the four pillars of Object Oriented programming?  

   Abstraction, Inheritance, Encapsulation, Polymorphism.    
   
4. What are some tools available in JavaScript to help you write object oriented code?  

   Constructor functions allow you to utilize a class structure  
   
5. What are some key concepts to be aware of when refactoring your JavaScript?  

   DRY it up.  Don't use anonymous functions in deferred objects.  Break down complex functions into single responsibility functions.  
   
6. What's a callback function and what are some reasons when we use/need callback functions?  

   It's a function that is passed as an argument to another function.  We used them with event listeners to trigger a function after an event.    
   
7. What are the different scopes of variables in Javascript? When would you want to define global variables?  

   Variables declared outside of a function are in the global scope and accessible anywhere in the code.  Variables declared inside a function are in the local scope and only accessible within the that function.  I've used global variables to save an address for an API that I'll use multiple endpoints from, and to import files.  
   
8. What's the difference between `==` and `===` in JavaScript?  

   `===` is more strict, `==` will try to coerce the values to make them match.  
   
9. Why do front end frameworks exist?  

   To make the developers job easier, by making it easier to write complex or verbose functionality.  
   

#### Review  

10. Why do people say "HTTP is stateless"?  

    Because the server doesn't save a record of the requests that are made.  
   
11. Describe a RESTful API.  

    An API that follows the constraints of RESTful architecture.  I don't know how else to elaborate on this because I don't fully understand REST, I know that it's not necessarily tied to HTTP, although it can be used.  There seems to be a need for consistency in documentation and usage of the site.  

12. What are some main characteristics of a team following an agile workflow?  

    Team plans out work to be done in advance and works in time period cycles called iterations.  There are regular checkin-ins, as a group, so everyone stays coordinated and can get the help they need.  The goal is to build a functional product quickly with regular feedback from stakeholders and the customer so changes can be implemented more smoothly.  
  
  
13. What are some advantages **and** disadvantages to using OAuth to authenticate a user?  

    Advantage: you don't have to write your own user authentication or store user passwords.  Disadvantage: you can't control the site you're using OAuth through, if they go down your users cannot authenticate.  Also, a user to your site would also need to be a user on that site.
