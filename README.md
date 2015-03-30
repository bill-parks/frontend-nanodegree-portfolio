## Website Performance Optimization portfolio project

### How to run this project:
1. Open index.html in a web browser, preferably Google Chrome.
2. Observe page has been optimized to score better than 90 with Google PageSpeed.
3. Open views/pizza.html in a web browser, preferably Google Chrome.
4. Observe page has been optimized to score better than 90 with Google PageSpeed.
5. Observe page has been optimized to render a consistent framerate of 60fps or less when scrolling
6. Observer that the time to resize pizzas is less that 5 ms as shown in the browser console


### How I completed this project
1. Reviewed the course on Website Performance Optimization using Google PageSpeed.
2. Downloaded the required project assets.
3. Used Chrome Developer Tools to review the current state of various pages within the application and identified areas for improvement.
4. Reviewed the code powering the website and identified areas where I believe modifications were warranted.
5. Iteratively made changes and tested those changes using the tools available to me to determine if they were a performance gain or loss.

### Optimizations 
* Prevent render blocking with async parameter in script tags
* Prevent render blocking by movinge css to inline
* Optimize images using GIMP: Resize profilepic.jpg, create sized copies of pizza.jpg (pizzeria100-75.jpg and pizzeria360-270.jpg)
* Improve load time with reserved size(s) added to img tags
* Minify CSS and JS
* main.js

### Resources Used
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). 
* [The fewer the downloads, the better](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html)
* [Reduce the size of text](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html)
* [Optimize images](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html)
* [HTTP caching](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html)

### Evaluation Criteria
The project rubric below reflects all criteria for "meets specifications". 
*Both source and production code are in the same repository in separate folders.

#### Critical Rendering Path for Index.html
 * Meet Specifications: Identify and perform optimizations to achieve a PageSpeed score of 90 (both Mobile and Desktop scores should be at least 90)
 * Exceed Specifications: Identify and perform optimizations to achieve a PageSpeed score above 90

#### Framerate for pizza.html
 * Identify and perform optimizations ensuring a consistent framerate at 60fps when scrolling
 * The file you need to study and change is views/js/main.js

#### Computation Efficiency for pizza.html
* Time to resize pizzas is less that 5 ms in pizza.html shown in the browser console

#### Build Tools
* Research, identify and use build tools to automatically perform optimaztion such as minification of CSS and JS and image optimizations

#### Comments in views/js/main.js
* Comments in views/js/main.js for pizza.html are present and indicate the optimizations done for the Pizzas page.

#### Documentation in README.md file
* A README.md file is included detailing all staeps required to successfully run the application and outlines the optimizations that were made in views/js/main.js for pizza.html

#### Submission
* Include Websites, Books, Forums, Blogs, Posts, GitHub repositories, etc. that were referenced or used in this submission
* Submit both the source and production code in the same repository in separate folders
* Submit code through Link to Project

