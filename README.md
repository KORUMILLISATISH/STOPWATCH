# STOPWATCH
Let’s see the real demo of this stopwatch timer and try to get some ideas about all the codes that I have used to make this stopwatch using HTML CSS and javascript.
As we have seen on the video tutorial of this stopwatch. At first, we saw all the time in the stopwatch is in zero condition. When I clicked on the start button the millisecond time starts to increase from 0 to a hundred and when it crosses the second number increased by one and the milliseconds number comes in its initial condition.

Step 1 (HTML Code): To get started, we will first need to create a basic HTML file. In this file, we will include the main structure for our stopwatch.  After creating the files just paste the following codes into your file. Make sure to save your HTML document with a .html extension, so that it can be properly viewed in a web browser.

1. <!DOCTYPE html>: This declaration specifies that the document is written in HTML5, the latest version of HTML.

2. <html lang="en">: This is the opening tag of the HTML document. It defines the root element of the document and specifies that the document's primary language is English ("en").

3. <head>: This is the head section of the HTML document. It contains meta-information about the document and links to external resources.

Step 2 (CSS Code): Once the basic HTML structure of the stopwatch is in place, the next step is to add styling to the stopwatch using CSS.

Next, we will create our CSS file. In this file, we will use some basic CSS rules to style our stopwatch. Here's an explanation of each part:

Step 3 (JavaScript Code): Finally, we need to create a function in JavaScript. Let's break down the code step by step:

1. It starts by selecting several elements from the HTML document using their IDs or class names:

time_ele: Represents an element with the class name "time." This is presumably where the stopwatch time will be displayed.
start_btn, lap_btn, stop_btn, reset_btn: These variables store references to HTML buttons with the respective IDs "start," "lap," "stop," and "reset."
l1, l2, l3, l4, l5: These variables store references to elements with IDs "lap1," "lap2," "lap3," "lap4," and "lap5," which are used to display lap times.
