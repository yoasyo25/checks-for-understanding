## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
JavaScript syntax and how to test JavaScript code. 

2. What are some tools to help debug JavaScript code?
The console on our browser, debugger, and the pry.js package. 

3. What are some tools you need in order to unit test your JavaScript?
We need to create a test environment and install a test module that allows us make assertions for hour our code should behave. 
The Mocha and Chai packages allow us to conduct unit test in JavaScript. 

4. What is the syntax for invoking a function? Give an example.
(). We write the function name and invoke it by using () next to the function name. 

5. What's `this` in JavaScript?
`this` refers to different JavaScript objects depending on the context that it is called in. 
It refers to the global object when called outside a function. When called inside a function, 
`this` points to the parent object, or the object that invoked the function. 

6. What is Webpack and why is it useful?
Webpack is a modul bundler that packages the dependencies in our application so that it is understood by the browser. 
It bundles our HTML, CSS, JavaScript files so that it can be served to the browser in a single file. 

7. When/why do you want to use event delegation?
event delegation is useful when we have events that are occuring on elements that are constantly added/deleted. 
Instead of adding an event listener on each element, event delegation allows us to add a listener to the parent element. 
Then when the event bubbles up, we are able to determine the event object's target and know which element the action was performed on. 

8. What's `npm` and what do we use it for?
`npm` is Node Package Manager. It allows us to install Node packages and manage our project dependencies. 

#### Review  
9. What's the MVC design pattern? Describe each part of MVC.
MVC is a way of organizing our code so that it is readable and adhers to the single responsibility principle. 
The model is where the application's data resides. It stores the attributes for our model, complex logic such as database queries and communicates with the controller and shouldn’t interact with the view. The view simply render the template and displays data passed on from the controller and should not communicate with the model. The controller manages data flow. It takes requests from the router based on user input and communicates with the model and view based on the request. The controller should not contain complex logic. 

10. What are a few ways to optimize a Rails application?
Adding background workers and caching.  

11. What's a background worker? When would we want to use a background worker?
A background worker processes a request that tends to take a long time outside of the request/response cycle.
The background task is implemented while the user continues to interact with the application. 
We would use a background worker to process tasks that take a long time such as uploading large CSV data or sending large amounts of email. 
