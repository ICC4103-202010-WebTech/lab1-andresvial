Andres Vial Correa

How is the list of news articles structured with HTML?   

- Each article is in a row (<tr>), which itself is divided in cells (<td>): the number is one td, 
the arrow pointing upwards is another td, and finally the title of the article is another td (which is of class="title").
So there is many tr from top to bottom, where each tr is an article. All of these tr are in a <tbody>,
the tbody is inside the <center>, which is inside the <body> of the HTML.

Briefly describe what you see in files with names starting with hn.js and news.css. How are
these files different? What is their purpose?

- The files that end in .css contains all the format of the text (the color, aligment, font, size, etc...) in the page, the files that ends with .js are javascript
files that indicates the logic of the HTML, the funtions of it.

How many requests has it taken for the browser to download the Hacker News main page? What are the
HTTP request methods in each case? Check out the HTTP response headers and find out
what kind of web server is used for this website.

- There are 7 resources, all of them were obtained via GET requests. The kind of server used in this web page is nginx