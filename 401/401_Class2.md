# Class 2

Node is a flexible and powerful runtime environment that allows us to utilize a large kit of tools to help with software development

## Node and Express

1. Middleware is any type of software/program that facilitates communication between the Operating System and the applications that are being run on it. 

2. Express is a popular server side framework.

3. Express being "unopinionated" means that it is comparatively flexible in how you use it to create what you need.  You can use many different types of modules and components.

4. Modules are JavaScript files that you can import/use in other code, as long as you use the `require()` function.

    Source: [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

## NPM

1. Version 8.19.1

2. `npm install jshint`

## Test Driven Development (TDD)

1. Tests are important because they show that your code is actually working as intended.  Building on that, it also helps to prevent dealing with major bugs on the live-version of your applications.

2. Benefits of TDD:
    * many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort
    * the same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases
    * although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling

    Source: [Agile Alliance](https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))

3. Common Pittfalls:
    * Individual Pitfalls:
        * trying to create too many tests at one time
        * writing tests that are either too broad or too narrow in scope
    * Team Pitfalls:
        * only some members of the team are utilizing TDD
        * neglecting to perform maintenance on the tests

## Continous Integration (CI)/Continuous Delivery (CD)

1. Three Benefits of CI:
    * Catches more bugs
    * Reduces git merge conflicts
    * more confidence in code
2. Continuous Delivery is the development of software in a way that allows you to release it at any time. Continous Deployment lets you deploy new features immediately with little downtime.

3. To put it simply, Github can act as a gate for your code if you've set up the appropriate tests.  When someone wants to add code, Github can relay the code to the test server and will read the response and display whether or not that code passed the tests.  

    [Github Professional Guides](https://www.youtube.com/watch?v=xSv_m3KhUO8)

[Return to Table of Contents](https://haydencleaver.github.io/reading-notes/)