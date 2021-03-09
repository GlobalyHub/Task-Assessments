# Task for Software Engineer (Full Stack) - PHP / Javascript

This is a simple coding task not a coding challenge. This has only **Create and Read** of the small CRUD part for the 
client section of the application.

### Task

1. Create a form to get 
   1. Name
   2. Gender
   3. Phone 
   4. Email 
   1. Address
   1. Nationality
   1. Date of birth
   1. Education background 
   1. Preferred mode of contact (select one from email, phone, none)
2. You can be creative with the fields.
3. Add relevant validation to the form both frontend (js) and backend (php)
4. After form submission, if fields are valid save to a csv file
5. Show all clients pulled in from the CSV as another page

### Things to consider

1. As the task is easy, we will look into the software design part of things, just making it work is not enough.
1. Naming classes, methods and variables properly will be checked.
1. Simple code is better, still think how easy will it be easy to add things like update and delete client later.
1. The way you construst URLs will also be evaluated.
1. Your git commit history will tell a story of how you thought of the solution please be mindful of it. If you use Pull reqeust to come to your solution its even better.
1. Code it so that the next person who continues that work will like it and not hate the code. Think maintainability of code.
1. Tip: First break your task into logical parts then code it. (First solve the problem. Then write code. - John Johnson)
1. Tip: Commented code is bad, relavant comments about code will be necessary. PHP docs are right places will be appriciated.

### Rules/Requirements

1. This task needs to be completed and submitted back within 72 hours of receiving it, if not stated otherwise.
1. You must use **Laravel** framework of version **5.x** or above.
1. You will need to use PSR-O or PSR-4 autoloading. **PSR-4 preferred**.
1. Code must be comply with **PSR-2 coding standards**. You can use [styleci](https://styleci.io/) for this.
1. You must have a readme.md file in the root, **well formatted in markdown** (like the one you are reading now) that explains your solution.
1. Use of any extra open-source library or package is allowed only via **composer/packgist**. You will need to explain why you used it in the read me file.
1. You can use any front-end library or framework, **bootstrap preferred**. You can even use jquery or other javascript library for validation.
1. You must use git and submit this task as a **private or public git repository on github/bitbucket** another option is a zip/tar file.

### Bonus points

1. If you can add detail view page to the listing page, it will be good.
1. Adding pagination will earn you some more point.
1. Adding any form of automated tests like unit or functional will be a plus point. **PHPUnit preferred**.
1. Wiring up your tests with a continuous integration (CI) service and reporting coverage is a huge plus. **Wercker.com is a good free CI even for private repos**. If you open source your code and use Travis CI that is also fine.
1. Application level logging following PSR-2 starndards with saving logs in a cloud logging service (like logentries.com) **is preferred**. For example log that the client is created successfully.
1. Hosting your small application in free service provider will earn you additional points. Think of first level security too. You can host in on [Zeit](https://zeit.co/) with now-cli, Heroku, **elastx.se/en** or any free host. If you use a free host do mention how you deployed the application. 
1. If you can run your repo through a code quality checking service like [codeclimate](https://codeclimate.com/) it would be great. 
1. Any relevant details in the readme.me file **is a plus**.

### Final Note 

Just completing the task might be at 2-4 hour job. If you just complete the requirements of the task its like getting 40 out of 100. You have been given 7 days so roughly 24 hours (work time) considering that you will invest time in learning things you might not know like automated testing, CI and logging with libraries like monolog and even deploy the app. If you surprise us with a dockerfile in your solution we will be happy.

This task can be done by a student, a software engineer with 1 year experience or a software engineer with 5+ years of experience. The main **question is do you aim for 100/100 or just 40/100** that will just pass you in the task, take a wise decision. Don't do things to just make it work, think about making it maintainable too.
