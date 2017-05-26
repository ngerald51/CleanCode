#  Quality Code is code
Coding Organization can make or break a development organization. Countless hours and significant resources are lost because of poorly written code. Hence, in my opinion, code organization can actually make or break a development team organization. 
My opinion of clean code is mainly code that is portable and easily extensible to fellow developers or team members in a project. It adheres to time-tested principles and patterns, which would lead to huge payoff in application maintainability and more allows ease of evolution of a program.
The principles and practice that clean code should adhere to are as follows
1. It should not be redundant
Modification of any single element of a system doesn’t require a change in any other logically unrelated elements. An example might be the Model-View-Controller pattern that is being use in Rails. 
2. Using Descriptive naming conventions for variables and methods.
Conform to easy naming conventions can be a good start. Some of the guidelines may include that Classes and type names should be nouns. Methods names should contain a verb. In particular, if a method returns a value indicating whether something holds true for an object, the method name should start with is. Other methods that return an object's property should start with get, and those that set a property should start with set.
5. Can be easily extended to any other developer
Keep coding format and structure as simple as possible. Hence simplicity should be key consideration in the design of your code. The practice to focus on the simplest things that make your software work.
Projects are mainly done by a group of people hence the production of a hardly maintainable and extendable code would cripple the project team.
6. It should have minimal dependencies
The more dependencies it has, the harder it is to maintain and change it in the future. You can always help yourself in achieving the goal of having minimal dependencies by using e.g. NDEPEND for checking potential incorrectness in the dependencies of your code.
7. Smaller is better
Code should be minimal. Both classes and methods should be short, preferably just a few lines of code. It should be well divided (also within one class). The better you divide your code the easier it becomes to read it. This principle might positively influence point 4 – it will make it easier for other developers to understand your code.
8. It should have unit and acceptance tests
How can we know that our code complies with the requirements if we don’t write tests? How can we maintain and extend it without the fear that it will stop working? Code without tests is simply not clean. If you would like to get to know more about the pillars of unit testing I advise you to read a very nice article Three Pillars of Unit Tests written by one of my colleagues.
9. Comment and Documentation 
Commenting and outlining what a method or class does is, its parameters, and what it returns, as well as possible errors and exceptions. Write the comments as you develop the code and make it a common practice.
In addition, ensure that your code as a whole comes with at least a guide explaining what it does; indicating its dependencies; and providing instructions on building, testing, installation, and use. This document should be short and sweet; a single README file is often enough.


## Footer ##

* Clean Code: A Handbook of Agile Software Craftsmanship
* http://www.informit.com/articles/article.aspx?p=2223710
* https://www.quora.com/How-do-you-define-code-quality
