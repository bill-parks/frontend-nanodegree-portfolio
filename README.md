## Website Performance Optimization portfolio project

### How to run this project:
Open index.html in a web browser, preferably Google Chrome.
Page has been optimized to score better than 90 with Google PageSpeed.
Additional optimizations were made based on the Google Chrome PageSpeed add-in.
Open views/pizza.html in a web browser, preferably Google Chrome.
Page has been optimized to score better than 90 with Google PageSpeed.
Additional optimizations were made based on the Google Chrome PageSpeed add-in.
Page has been optimized to 60 FPS

### How I completed this project
1. Reviewed the course on Website Performance Optimization using Google PageSpeed.
2. Downloaded the required project assets.
3. Used Chrome Developer Tools to review the current state of various pages within the application and identified areas for improvement.
4. Reviewed the code powering the website and identified areas where I believe modifications are warranted.
5. Iteratively made changes and tested those changes using the tools available to me to determine if they were a performance gain or loss.### Optimizations 
*	set the javascript to async, to prevent blocking
*	optimized the images using Kraken.io (https://kraken.io/web-interface), the page speed got to a score of 86
*	changed the font loading, moved the css to inline, to prevent render blocking, got to a score of 88
*	used grunt with cssmin, uglifier and htmlmin to minify the JS, CSS and HTML, got to a score of 93
*	main

### Resources Used
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
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
*Please do not forget to update the README file and make sure you outline all of your optimizations done in main.js for the pizzas page.

#### Submission
* Include Websites, Books, Forums, Blogs, Posts, GitHub repositories, etc. that were referenced or used in this submission
* Submit both the source and production code in the same repository in separate folders
* Submit code through Link to Project

