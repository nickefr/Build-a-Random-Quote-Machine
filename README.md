# Random Quote Machine -Requirements 
https://codepen.io/nickefr-the-flexboxer/pen/GRLBNwr

This project is a Random Quote Machine, designed to fulfill the user stories provided by FreeCodeCamp. It allows users to generate random quotes and share them via Twitter.

## User Stories

| User Story | Description |
| --- | --- |
| **User Story #1** | I can see a wrapper element with a corresponding id="quote-box". |
| **User Story #2** | Within #quote-box, I can see an element with a corresponding id="text". |
| **User Story #3** | Within #quote-box, I can see an element with a corresponding id="author". |
| **User Story #4** | Within #quote-box, I can see a clickable element with a corresponding id="new-quote". |
| **User Story #5** | Within #quote-box, I can see a clickable a element with a corresponding id="tweet-quote". |
| **User Story #6** | On first load, my quote machine displays a random quote in the element with id="text". |
| **User Story #7** | On first load, my quote machine displays the random quote's author in the element with id="author". |
| **User Story #8** | When the #new-quote button is clicked, my quote machine should fetch a new quote and display it in the #text element. |
| **User Story #9** | My quote machine should fetch the new quote's author when the #new-quote button is clicked and display it in the #author element. |
| **User Story #10** | I can tweet the current quote by clicking on the #tweet-quote a element. This a element should include the "twitter.com/intent/tweet" path in its href attribute to tweet the current quote. |
| **User Story #11** | The #quote-box wrapper element should be horizontally centered. Please run tests with browser's zoom level at 100% and page maximized. |

## Fulfillment

Fulfill the below user stories and get all of the tests to pass. Use whichever libraries or APIs you need. Give it your own personal style.

You can use any mix of HTML, JavaScript, CSS, Bootstrap, SASS, React, Redux, and jQuery to complete this project. You should use a frontend framework (like React for example) because this section is about learning frontend frameworks. Additional technologies not listed above are not recommended and using them is at your own risk. We are looking at supporting other frontend frameworks like Angular and Vue, but they are not currently supported. We will accept and try to fix all issue reports that use the suggested technology stack for this project. Happy coding!

Note: Twitter does not allow links to be loaded in an iframe. Try using the target="_blank" or target="_top" attribute on the #tweet-quote element if your tweet won't load. target="_top" will replace the current tab so make sure your work is saved.


```html
<!DOCTYPE html>
<html lang="en">
<head>
  <link rel="stylesheet" href="styles.css" />
  <link rel="stylesheet" 
        href="https://maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css" />
  <title>FCC : Random Quote Machine</title>
</head>
<body>
  <!-- User Story #1: Wrapper element with id="quote-box" -->
  <div id="wrapper">
    <!-- User Story #2: Element with id="text" -->
    <div id="quote-box">
      <div class="quote-text">
        <!-- User Story #6: Display a random quote -->
        <i class="fa fa-quote-left"> </i><span id="text"></span>
      </div>
      <!-- User Story #7: Display the author of the random quote -->
      <div class="quote-author">- <span id="author"></span></div>
      <div class="buttons">
        <!-- User Story #10: Tweet the current quote -->
        <a class="button" id="tweet-quote" title="Tweet this quote!" target="_top">
          <i class="fa fa-twitter"></i>
        </a>
        <a class="button" id="tumblr-quote" title="Post this quote on tumblr!" target="_blank">
          <i class="fa fa-tumblr"></i>
        </a>
        <!-- User Story #8: Fetch a new quote -->
        <button class="button" id="new-quote">New quote</button>
      </div>
    </div>
    <!-- Footer with credit -->
    <div class="footer">by <a href="https://codepen.io/nickefr-the-flexboxer/pen/GRLBNwr">nick</a></div>
  </div>
  <!-- JavaScript scripts -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jqueryui/1.13.2/jquery-ui.min.js"></script>
  <script src="script.js"></script>
</body>
</html>
```










