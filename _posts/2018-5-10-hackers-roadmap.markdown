---
layout: post
title: "Hacker's Roadmap"
---

## Table of Contents
* Full-Stack Web Development
	* Frontend Topics
		* [Basic Frontend Web Development](#basic-frontend-web-development)
		* [Intermediate Frontend Web Development](#intermediate-frontend-web-development)
		* [Advanced Frontend Web Development](#advanced-frontend-web-development)
	* [Backend Topics](#backend-web-development)
* [iOS Mobile App Development](#ios-app-development)
* [Data Science & Machine Learning](#data-science--machine-learning)
* [DevOps](#devops)

---

## Full-Stack Web Development
### Basic Frontend Web Development
#### Topics: HTML, CSS, Responsive Design, Javascript
1. HTML & CSS
	* [Learn to Code HTML & CSS](https://learn.shayhowe.com/html-css/)
2. Project: Build your personal website using just HTML/CSS!
	* Don't worry if you don't know how to start! Revisit the tutorials and Google your questions! Starting is always the hardest part.
	* **Optional for debugging**: If you use Chrome, use [Chrome Developer Tools](https://www.youtube.com/watch?v=wcFnnxfA70g) by right-clicking and selecting "Inspect" to debug and edit any website in-browser
3. Responsive Web Design
	* [What does responsive mean?](https://www.w3schools.com/css/css_rwd_intro.asp)
	* [Examples of responsive web design](http://blog.froont.com/9-basic-principles-of-responsive-web-design/)
	* [What is Bootstrap?](https://stackoverflow.com/a/24783264)
	* Check out [Bootstrap Components](https://getbootstrap.com/docs/4.1/components/buttons)
		* Note: Bootstrap's documentation has example code snippets which show you how to use different components/widgets which you can just copy and paste into your code.
	* [Bootstrap Grids](https://youtu.be/VaW4na2qkwQ) Tutorial
	* [Bootstrap Nav Bar](https://youtu.be/L0uNai3XyKQ) Tutorial
4. Project: Upgrade your personal website to be responsive and use a nav-bar component!
	* Note: you can use different frontend frameworks such as [Foundation](https://foundation.zurb.com/), [Materialize](https://materializecss.com/), [SemanticUI](https://semantic-ui.com/), etc if you prefer.
5. Javascript
	* [Why JS?](https://www.thoughtco.com/what-is-javascript-used-for-2037679)
	* [Codecademy: Learn JS](https://www.codecademy.com/learn/introduction-to-javascript)
	* [Intro to the DOM](https://www.digitalocean.com/community/tutorials/introduction-to-the-dom)
	* [Altering the DOM](http://eloquentjavascript.net/14_dom.html)
6. Project: Add animation, interaction, or a form to your website using Javascript!
7. You know enough to build static frontend websites! Keep practicing by making websites till you feel more comfortable.

### Intermediate Frontend Web Development
This section is not required, but encouraged if time permits. If you do read anything here, read up on #2: Templating Engines and #4: Using CDNs.
1. [jQuery](https://www.codecademy.com/learn/learn-jquery)
	* Note: jQuery is typically not used for large projects, and is seen more in small purely frontend projects. So having some idea of what it looks like is useful.
2. Templating Engines
	* [Introduction](https://www.sitepoint.com/overview-javascript-templating-engines/)
	* [Handlebars.js Example](https://tutorialzine.com/2015/01/learn-handlebars-in-10-minutes)
3. CSS Preprocessor: Sass
	* [Sass](https://sass-lang.com/guide)
	* [Code Example](https://www.youtube.com/watch?v=b0d--jixRwg)
4. Using 3rd Party Javascript Libraries
	* Tutorial: [Isotope Tile Library](http://www.designlunatic.com/2011/08/isotope-tutorial/)
	* [Referencing External JS Libraries: CDNs](https://www.sitepoint.com/7-reasons-to-use-a-cdn/)

### Advanced Frontend Web Development
#### Topics: NPM, React.js, and Redux

0. Installation
	1. Install [`npm` and `node.js`](https://www.npmjs.com/get-npm)
1. Package/Dependency Managers
	* [What is `npm`?](https://nodejs.org/en/knowledge/getting-started/npm/what-is-npm/)
	* [Basic `npm` commands](http://dreamerslab.com/blog/en/npm-basic-commands/)
2. React.js
	* [Introduction](https://programmingwithmosh.com/react/react-tutorial/)
	* [Hello, world Example](https://reactjs.org/docs/hello-world.html)
	* [Build a tic-tac-toe game](https://reactjs.org/tutorial/tutorial.html)
3. [`react-router`](https://blog.pshrmn.com/simple-react-router-v4-tutorial/)
4. Project: Build a restaurant menu using React.js while trying to separate the view from the underlying data.
5. Redux
	* Introduction
		* [Part 1](https://www.smashingmagazine.com/2016/06/an-introduction-to-redux/)
		* [Part 2](https://code-cartoons.com/a-cartoon-intro-to-redux-3afb775501a6)
	* [Build a Todo List](https://redux.js.org/basics/basic-tutorial)
	* [Build a Reddit Feed](https://redux.js.org/advanced/advanced-tutorial)
6. Project: Build a new react app using redux.


### Backend Web Development
1. [What is frontend & backend development](https://blog.codeanalogies.com/2018/04/07/front-end-v-back-end-explained-by-waiting-tables-at-a-restaurant/)
2. [Client-server Architecture Introduction & Analogy](https://blog.codeanalogies.com/2018/04/26/web-servers-explained-by-running-a-microbrewery/)
3. [What is an API?](https://blog.codeanalogies.com/2018/02/27/web-apis-explained-by-selling-goods-from-your-farm/)
	* [Another Analogy](https://medium.com/@tyteen4a03/how-apis-work-an-analogy-for-dummies-ac6ee1d1671b)
4. [What is HTTP?](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)
	* [`POST` vs. `PUT`](https://stackoverflow.com/questions/630453/put-vs-post-in-rest?noredirect=1&lq=1)
5. [What is REST?](https://stackoverflow.com/questions/671118/what-exactly-is-restful-programming?rq=1)
	* [What is the difference between HTTP & REST?](https://stackoverflow.com/questions/2190836/what-is-the-difference-between-http-and-rest)
	* [Designing a RESTful API: Best Practices](https://hackernoon.com/restful-api-designing-guidelines-the-best-practices-60e1d954e7c9)
	* [Designing a RESTful API: Another Example](https://making.lyst.com/2015/02/20/1-to-1-relationships-and-subresources-in-rest-apis/)
6. [Server-side Web Frameworks](https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps/Web_frameworks)
7. [Databases: what & why](https://medium.com/omarelgabrys-blog/database-introduction-part-1-4844fada1fb0)
	* [Relational vs. non-relational databases](https://www.pluralsight.com/blog/software-development/relational-non-relational-databases)
8. Framework Specific Tutorials
	* Try choosing 1 particular framework (ie Node.js, Django, Ruby on Rails (RoR), etc.) and stick with it till you are comfortable with implementing the concepts you read about above. Then feel free to experiment with other frameworks to gain exposure in how they also implement the same thing.
	* Note: UCLA students tend to have more experience with Node.js due to UCLA ACM mentors/workshops/events, so it's recommended you learn Node.js first if you are a UCLA student for the larger support community.
	<!-- Resources on various web frameworks -->
	
	| Node.js | Django | RoR |
	|---------|--------|-----|
	| [Installation](https://nodejs.org/en/)         |[Installation](https://docs.djangoproject.com/en/3.0/topics/install/)        |[Installation](http://installrails.com/)
	| [Video Tutorials](https://www.youtube.com/playlist?list=PL55RiY5tL51oGJorjEgl6NVeDbx_fO5jR)         |[Official Tutorials: Part 1 - 7](https://docs.djangoproject.com/en/3.0/intro/tutorial01/)        |[Michael Hartl's RoR Book](https://www.railstutorial.org/book)     |
	| [Build a Web API](https://scotch.io/tutorials/build-a-restful-api-using-node-and-express-4)         |[Build a Web API](https://codeburst.io/building-an-api-with-django-rest-framework-and-class-based-views-75b369b30396)        |[Build a Web API](https://scotch.io/tutorials/build-a-restful-json-api-with-rails-5-part-one)     
	| [Build an online shopping cart](https://www.youtube.com/playlist?list=PL55RiY5tL51rajp7Xr_zk-fCFtzdlGKUp)         |[Build a blog Tutorial](https://tutorial.djangogirls.org/en/)        |     |
	{: .web-table }
10. Project: Build your own full-stack web app using any frontend/backend technology you want!
	* Suggestions:
		* social media app
		* finance tracker app
		* event, food, etc. recommendation app
		* workout buddy finder app
		* Meetup, Twitter, Reddit, etc. clone
11. This completes your full-stack web development roadmap! Continue working on your own projects till you feel comfortable building your own API and web app.

## iOS App Development
1. [Learn Swift](https://codewithchris.com/learn-swift/)
2. [iOS Core Concepts](https://academy.codewithchris.com/p/beginners-course-free)
3. Important Concepts
	* [What is a view controller?](https://developer.apple.com/documentation/uikit/uiviewcontroller?changes=_3)
	* [View Controller Life Cycle](https://medium.com/@amyjoscelyn/the-life-cycle-of-a-view-c98f296fd84e)
	* [ARC - Memory Management](https://www.raywenderlich.com/966538-arc-and-memory-management-in-swift)
3. Guided Tutorials
	* Build a Card Matching Game: [Video Series](https://www.youtube.com/playlist?list=PLMRqhzcHGw1YdahNsCLZdSVfNv0stwvdx)
	* [UITableViewController](https://youtu.be/5lH5fSuDVxg)	
	* Build a SoundBoard App: [Video Series](https://www.youtube.com/playlist?list=PLMRqhzcHGw1a_lcW4L21LPwmua3lZeuVc)
	* [Animation Tutorial](https://www.youtube.com/watch?v=5b91dFhZz0g)
4. [Introducing Other Types of View Controllers](https://developer.apple.com/library/content/documentation/WindowsViews/Conceptual/ViewControllerCatalog/Introduction.html)
	* in iOS apps you often put different view controllers together to create the full app storyboard (i.e. `UITableViewController`, `UITabBarController`, `UICollectionViewController`)
5. [CocoaPods](https://stackoverflow.com/questions/22261124/what-is-cocoapods/22261215)
	* [Installation](https://youtu.be/oNKVVBN2JN0)
	* [AlamoFire Tutorial](https://youtu.be/Brei27hdnF8)
	* [Firebase Tutorials](https://www.youtube.com/playlist?list=PLMRqhzcHGw1ZRUB86rmNqG15Sr5jV-2NU)
6. Build your own app!
7. Other Advanced Topics
	* Delegates & Protocols
		* [What is it?](https://blog.bobthedeveloper.io/the-meaning-of-delegate-in-swift-347eaa9674d)
		* [Example](https://medium.com/@jamesrochabrun/implementing-delegates-in-swift-step-by-step-d3211cbac3ef)


## Data Science & Machine Learning
**Topics: Python, pandas, numpy, matplotlib, machine learning concepts and project tutorials**
1. [Learn Python](https://www.codecademy.com/learn/learn-python-3)
2. Setup [`virtualenv`](https://virtualenv.pypa.io/en/stable) to create and work in a Python virtual environment
	* [Why use it?](https://www.dabapps.com/blog/introduction-to-pip-and-virtualenv-python/)
	* [How to use `virtualenv`](http://www.simononsoftware.com/virtualenv-tutorial/)
	* What is `requirements.txt`?
		* [A Better `pip` Workflow](https://www.kennethreitz.org/essays/a-better-pip-workflow)
		* [`pip freeze`](https://medium.com/python-pandemonium/better-python-dependency-and-package-management-b5d8ea29dff1)
3. [Introduction to `pandas`](https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python)
	* Note: you can follow along with as much of the tutorial as you want till feeling comfortable with Pandas
4. Introduction to `numpy`
	* [Part 1](https://hackernoon.com/introduction-to-numpy-1-an-absolute-beginners-guide-to-machine-learning-and-data-science-5d87f13f0d51)
	* [Part 2](https://hackernoon.com/introduction-to-numpy-2-an-absolute-beginners-guide-to-machine-learning-and-data-science-967b21e3542a)
4. [Matplotlib Tutorial: Political Tweets](https://www.dataquest.io/blog/matplotlib-tutorial/)
5. Machine Learning Concepts
	* [A visual introduction](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
	* [Another introduction](https://www.digitalocean.com/community/tutorials/an-introduction-to-machine-learning)
	* [Guide from ACM AI @ UCLA](https://github.com/adeshpande3/Machine-Learning-Links-And-Lessons-Learned)
7. Feature Engineering Tutorials
    * [Video Game Reviews](https://www.dataquest.io/blog/pandas-python-tutorial/)
    * [Thanksgiving Foods](https://www.dataquest.io/blog/pandas-tutorial-python-2/)
8. Data Storytelling Tutorials
    * [NYC Education](https://www.dataquest.io/blog/data-science-portfolio-project/)
    * [Fannie Mae Loan Foreclosure](https://www.dataquest.io/blog/data-science-portfolio-machine-learning/)
	* Video Series: [Predicting the stock market](https://pythonprogramming.net/data-acquisition-machine-learning/)
9. Do your own project!
	* Choose a dataset from [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets), clean the data, try to extract meaning/trends, and make predictions and classifications similar to the guided projects above.
10. Congrats, you've learned and done enough to gain enough knowledge to onboard to more complex data science and machine learning projects in the future!

## DevOps
* [Learn Git](https://thenewstack.io/tutorial-git-for-absolutely-everyone/)
* Docker
	* [Intro to Docker](https://docker-curriculum.com/)
	* [Deploy a web-app with Docker](https://docker-curriculum.com/#webapps-with-docker)