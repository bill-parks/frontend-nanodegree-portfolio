## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository, inspect the code,

### Getting started

Profile, optimize, measure... and then lather, rinse, and repeat. Good luck!

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

### Submission
When you're ready to submit your project go back to your Nanodegree Portal, click on Project 4, and follow the instructions to submit.
*	Start by creating a text file with a list of websites, books, forums, blog posts, Github repositories etc. that you referred to or used in this submission (Add N/A if you did not use such resources).
*	Please submit your code through "Link to Project" with a link to the appropriate Github repo, using a separate repository for this project.
*	Please ignore the option to submit through "Upload a Zip".
It can take us up to 2 weeks to evaluate the project so keep checking back for updates.
If you are having any problems submitting your project or wish to check on the status of your submission, please email us at frontend-project@udacity.com.

### Next Steps
Feel free to hop onto the forums to help your fellow students, or work on the next project while you wait to receive your evaluation.

### Instructor Notes
The PageSpeed score of 90 is for index.html (both Mobile and Desktop scores should be at least 90).
The frame rate of 60fps should be obtained for the pizza page (views/pizza.html). The file you need to study and change is views/js/main.js.
Comments should be present in main.js to indicate the optimizations done for the Pizzas page.
Please do not forget to update the README file and make sure you outline all of your optimizations done in main.js for the pizzas page.
It's recommended to not measure performance in a virtualized environment. We recommend you measure your FPS performance in your native operating system.
Below is a picture of what the target timeline should look like. Evaluators will focus their attention on the timeline rather than the FPS meter due to varying hardware factors that may affect FPS.
Target Timeline

### Optimizations 
*	set the javascript to async, to prevent blocking
*	optimized the images using Kraken.io (https://kraken.io/web-interface), the page speed got to a score of 86
*	changed the font loading, moved the css to inline, to prevent render blocking, got to a score of 88
*	used grunt with cssmin, uglifier and htmlmin to minify the JS, CSS and HTML, got to a score of 93
*	main

### How to run:
Download the zip file and open the "index.html" file with your favorite browser.
Each page has optimized to achieve a 90+ Google PageSpeed score. Javascript has also been optimized to achieve a 60+ FPS rendering speed. I have included two versions of each HTML page: a production version and a development version.
The production versions include minified CSS and Javascript. They are the .html files (e.g. index.html). The development versions include no minification, so that you can more easily read through the code and understand what's happening. They are the _dev.html files (e.g. index_dev.html).

### Resources Used:
*	https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer#minification-preprocessing--context-specific-optimizations
*	https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer#text-compression-with-gzip
*	https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching
*	https://developer.mozilla.org/en-US/docs/Web/API/Document/write
*	https://github.com/feliu-io/fewd-p4
*	https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer?hl=en
