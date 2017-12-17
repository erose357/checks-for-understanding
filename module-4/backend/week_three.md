## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?  

   Node is a server side JavaScript runtime  
   
2. What is Express? What is Express similar to in the Ruby world?  

   Express is a JavaScript web application framework, like Sinatra in Ruby  
   
3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.  

   ```javascript
   const app = express()
   
   app.get('/api/v1/example', someFunction) 
   ```
   
4. What do we use Knex for?  

   Knex is a library that allows Express to interact with a SQL database  
   
5. How **could** you organize your code to follow the MVC design pattern in your Quantified Self project?  

   server.js -> routes calling functions within the controllers directory  
   controllers directory -> containing functions related to controller-like traffic directing  
   models directory -> containing functions related to interacting with the database    
   
6. How do you execute raw SQL in node?  

   Using knex: ```knex.raw('SQL query')```  
   
7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?  

   Advantages: the code base for each is more concise, you can more easily consume or provide data to/from additional servers  
   Disadvantages: communication between the two can be challenging, you need two separate servers  

#### Review  

8. Describe DNS.  

   Ties more easily readable enlgish domain names with the server IP addresses  
   
9. What does writing clean code mean to you?  

   Writing reasonably DRY code that is readable for other developers and using a file structure that is somewhat intuitive   
   
10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality? Hint: think about what tables you would need in the database, how those records would relate to each other, and good OOP.  
   *classes*:  
   guests -> guest info  
   rooms -> rooms at the hotel  
   bookings -> joins guests and rooms including timeline for stay  
   transactions -> financial transactions related to guests  
  
