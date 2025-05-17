# flin-test-2

## Project setup

This is a project to improve the performance of a website.
Initially, I created a simple HTML file with inline styles, wrinting some styles in CSS file and some javascript code in a separate file.

I was sucessfully improved the performance score from 81 to 98 by using the following techniques:

- Minifying the HTML, CSS and Javascript files (I used third-party tools like CSSMinifier and JSMinifier)
- Using the defer attribute to defer the execution of the Javascript code
- Using the sizes attribute to specify the image sizes
- Using the srcset attribute to specify the image source set
- Using the lazy loading attribute to specify the image loading strategy
- Using the preconnect and preconnect attribute to improve the performance of the website

## How to run the project

To run the project, you can open the html file with your web browser.

## Disclaimer

The test result is captured before I wrote some comments in the HTML file (so it may impact the performance score if you run the file with the comments written). Your score can vary depending on the browser you are using and the extensions you have installed. I already provided the Google Lighthouse report and the screenshot for both test runs. I used a Google Chrome browser with no extensions installed when doing the test.
