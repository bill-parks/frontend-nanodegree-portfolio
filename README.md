## Website Performance Optimization portfolio project

### How to run this project:
Open index.html in a web browser, preferably Google Chrome.
Page has been optimized to score better than 90 with Google PageSpeed.
Additional optimizations were made based on the Google Chrome PageSpeed add-in.
Open views/pizza.html in a web browser, preferably Google Chrome.
Page has been optimized to score better than 90 with Google PageSpeed.
Additional optimizations were made based on the Google Chrome PageSpeed add-in.
Page has been optimized to 60 FPS

### Evaluation
The project rubric below reflects all criteria for "meet specifications". Make sure you submit both your source and production code in the same repository in separate folders.

### Critical Rendering Path for Index.html
 * Meet Specifications: Identify and perform optimizations to achieve a PageSpeed score of 90 (both Mobile and Desktop scores should be at least 90)
 * Exceed Specifications: Identify and perform optimizations to achieve a PageSpeed score above 90

### Framerate for pizza.html
 * Identify and perform optimizations ensuring a consistent framerate at 60fps when scrolling
 * The file you need to study and change is views/js/main.js

### Computation Efficiency for pizza.html
* Time to resize pizzas is less that 5 ms in pizza.html shown in the browser console

### Build Tools
* Research, identify and use build tools to automatically perform optimaztion such as minification of CSS and JS and image optimizations

### Comments in views/js/main.js
* Comments in views/js/main.js for pizza.html are present and indicate the optimizations done for the Pizzas page.

### Documentation in README.md file
* A README.md file is included detailing all staeps required to successfully run the application and outlines the optimizations that were made in views/js/main.js for pizza.html
*Please do not forget to update the README file and make sure you outline all of your optimizations done in main.js for the pizzas page.

### Submission
*  Include Websites, Books, Forums, Blogs, Posts, GitHub repositories, etc. that were referenced or used in this submission
* Submit both the source and production code in the same repository in separate folders
* Submit code through Link to Project

### Optimizations 
*	set the javascript to async, to prevent blocking
*	optimized the images using Kraken.io (https://kraken.io/web-interface), the page speed got to a score of 86
*	changed the font loading, moved the css to inline, to prevent render blocking, got to a score of 88
*	used grunt with cssmin, uglifier and htmlmin to minify the JS, CSS and HTML, got to a score of 93
*	main

### Resources Used:
*	https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer#minification-preprocessing--context-specific-optimizations
*	https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer#text-compression-with-gzip
*	https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching
*	https://developer.mozilla.org/en-US/docs/Web/API/Document/write
*	https://github.com/feliu-io/fewd-p4
*	https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer?hl=en

### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html">The fewer the downloads, the better</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html">Reduce the size of text</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html">Optimize images</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html">HTTP caching</a>

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>

### How will I complete this project?
1. Review our course on Website Performance Optimization using Google PageSpeed.
2. Download the required project assets.
3. Use Chrome Developer Tools to review the current state of various pages within the application and identify areas for improvement.
4. Review the code powering the website and identify areas where you believe modifications are warranted.
5. Iteratively make changes and test those changes using the tools available to you to determine if they are a performance gain or loss.

### Evaluation
Your project will be evaluated by a Udacity reviewer according to the rubric below. Be sure to review it thoroughly before you submit. All criteria must "meet specifications" in order to pass. Make sure you submit both your source and production code in the same repository in separate folders.