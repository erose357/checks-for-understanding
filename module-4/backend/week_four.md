## Week Four - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's your favorite project management tool?  
   waffle.io  
2. Why do we create staging environments?  
   to run our code in an environment that is the same as production, to find bugs that are not immediately apparent in the development environment, prevent breaking production  
3. What are the characteristics of a good README (in your opinion)?  
   1. explains what the project is/does  
   2. how to set it up locally, any necessary dependencies  
      a. how to run the test suite  
      b. db setup  
   3. who to contact, if necessary  
4. What's one main improvement you're going to make to your code regarding accessibility issues?  
   Make the page can be tabbed through  
5. What are some basic security concerns to be aware of when building applications?  
   a. using programs that are no longer supported/not up to date  
   b. remove dependencies you no longer need  
   c. never trust user input, SQL injection/cross site scripting  
   d. be aware of vulnerabilities in the programs you use fix them/have a plan in place in case a vulnerability is found  
6. Why is continuous integration helpful/important?  
   to make sure you're not merging broken code into your master branch, helps prevent/detect issues before they get to production  
7. What are some pros/cons of using ReactJS as a frontend tool?  
   Pros: speed/efficiency when manipulating/updating the DOM, HTML is generated from the React components so less work with plain html  
   Cons: new library/syntax to learn

#### Review  

8. What are some characteristics of "good" git workflow?  
   frequent commits with useful messages, smaller PRs, using branches to implement features, merging master into a branch before creating a PR to prevent/minimize conflicts  
9. Describe each of the four fundamental concepts of object oriented programming.  
   abstraction - hide details that are not relevant  
   polymorphism - use the same function/method name to manipulate different data types  
   inheritance - reuse code  
   encapsulation - keep like things together
10. What's a module in Ruby? What's the difference between a class and a module? What are some good use cases for modules?  
   A class is able to hold state in the form of instances, a module is a collection of methods.  A module can be used to provide methods that can be used by different classes through inclusion or inheritance.  
