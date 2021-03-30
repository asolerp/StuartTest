## Solutions Engineer's first test

Welcome! Please spend some time answering the questions you can find below

We do not expect reading code here.

## Questions

**1- Imagine that you have two classes named "Animal" and "Dog" and you want the class "Dog" to have all the properties and methods from the class "Animal", how would you do it? How is this called? What's the benefit?**

I would use inheritance to give “Dog” the possibility to heritage “Animal” methods and properties.
The benefits are:

- Reusability
- Readability.

At the end is like to imitate what we have in the real world with code.
Dogs 🐶 and Cats 😸 share a lot of properties and behaviors of mammals.

**2- A call to the setTimeout() global method can block the event loop in NodeJS. Is this true or false? Why?**

It is false due to the nature of how Node has been build. Just is going to wait the time you have specified in the method. With a bad "while" implementation for example, you can block the event loop.

**3- How can you share information between components on a React application?**

You can share information throw props in your components or you can use a global state like redux for example and share the information globally.

**4- How would you protect a REST API against potential SQL Injections?**

For example in NodeJs, you need to tweak your code so any user input is automatically escaped before being executed.

**5- What does the level of coupling measure in software development?**

It measure the interdependence between different modules. This interdependence can be tight or loose.

**6- What is CI? Have you used one before?**

CI means continuous integration. It is an automatization process for developers. It helps with the integration of code changes from different contributors. You can make different processes like tests before the integration.
I have used Circle CI

**7- How would you deploy a Node application?**

I would put the aplication inside a container with Docker and I would use third party to host the application

**8- Why do we do code reviews?**

I would say for these reassons:

- Improve the quality of the team's code
- Imporve the communication between the members of the team.
- Imporve the code quality
- Find code problems

**9- In which files would you store API tokens, passwords, or similars?**

I would store this data in an enviroment file.

**10- What are the benefits of using Typescript?**

To have a tpyed and more robust code. It protects you to make type errors and it give you more information about your code.

**11- Describe with your own words a web socket?**

I would say it is a bidirecctional opened chanel between the sever and the client.

**12- Describe with your own words a GraphQL API.**

GraphQL API is a query language that solves a problem that you might have with a REST API. Instead of have N numbers of endpoints, you just have one and gives the frontend the possibility to get the data they need. No more no less.

**13- How do you keep yourself up-to-date in regards the technologies you do use?**

I join meetups, I follow important developers from the industry of big companies like Facebook or Google and I read technical papers.
