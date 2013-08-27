#Colorize

Randomly colorize any web page you are visiting.

##How to Use
1. Add this link to your bookmarks: javascript:(function(){var allElements = document.querySelectorAll('body, body *');for (var i=0; i < allElements.length; i++) {allElements[i].style.background = '#'+(Math.floor(Math.random()*16777216)).toString(16);allElements[i].style.color = '#'+(Math.floor(Math.random()*16777216)).toString(16);}})()
2. Visit a page and click the bookmark
3. Behold COLORZ
