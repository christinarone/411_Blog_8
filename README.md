# 411_Blog_8
Class 8
Discuss in words something you learned in class today or this week.
  I learned about creating a route and then creating a protected route.
  
How does hoisting work in JavaScript?
  It works by allowing functions to be safely used in code before they are declared. Hoisting is the process whereby the interpreter appears to move the declaration of functions, variables or classes to the top of their scope, prior to the execution of the code.

Why is setState() in React Async instead of Sync?
  Async setState calls are batched to provide a better user experience and performance.

How is the Virtual-DOM more efficient than Dirty checking?
  React uses virtual DOM which is a lightweight version of the DOM. The virtual DOM is created after every re-render.  

What is PureComponent? When to use PureComponent over Component?
 PureComponent is exactly the same as Component except that it handles the shouldComponentUpdate method for you. PureComponent is useful when you want to avoid re-rendering cycles of your component when its props and state are not changed.

What is a higher order component?
  A higher-order component (HOC) is a function that takes a component and returns a new component.

Which (if there is) node library method could you use to solve the algorithm problem you solved last night in your pre-homework.
  I'm not sure if there is a node library for this.

Which (if there is) node library method could you use to solve the algorithm problem you solved in class tonight?
  I wasn't sure if there was one for the problem I solved.

How do you think you might use the checkAuth() function to actually verify a user's email and password?
  I think I can use checkAuth() to verify a set of credentials. First, I need to check if the user is Authenticated. Then, I need to check the login route.
