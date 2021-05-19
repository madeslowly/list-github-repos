# List GitHub Repos

 ## Overview
 This repo lists all GitHub repos onto a webpage. The styling and functionality can easily be customized to meet your needs.

 ## Prerequisites

 jQuery is required for this repo to work properly. You can import the script from CDN into your html page like below:

 ```html
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1jquery.min.js"></script>
 ```

 ## How To Use

Find the script.js file located at `js/script.js`, place the file in your project and uncomment and edit the following lines:

```javascript
var user = ""; //put GitHub username in the ""
window.onload = genRepo(user);
```

 Go to your projects's html page and make sure you reference the JavaScript file in the head if you haven't done so, eg:
 ```html
<script src="js/script.js"></script>
 ```

 In the html page and add a div named `repo-box` where you want the repositories to show:
```html
<div id="repo-box"></div>
```

Final step is to add the styling. My styles.css file can be found at `css/styles.css` You may use that or modify or create your own.
