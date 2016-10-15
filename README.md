# express_guestbookdemo

Welcome to my demo of the Express mainframe that can be found in the book 'Express in Action'.

This demo is for anyone who's getting their feet wet with Node.js, Express.js and aren't sure how to put the two technologies together for view in a browser.

The main bridge you may be missing (or unable to articulate in your code) is the 'view engine' function of Express.js, which allows you to assign a 'public' folder (in this case our 'views' folder) and connect a given url (localhost:3000/views/yourfile) to a file that you've actually filled with your website design code (localhost:3000/views/yourfile.ejs).

In this sense, all of the pages you would use with traditional HTML (localhost:3000/public/about.html, localhost:3000/public/contact.html, etc.) are now placed in a 'views' folder and your HTML pages will now be rendered using Extended JavaScript (ejs) files (localhost:3000/views/about.ejs, localhost:3000/views/contact.ejs, etc.).

Please keep in mind because the '.ejs' extension will be removed (as well as the 'views' directory being invisible on the browser level), each page will appear to be it's own 'directory' (keeping in presentation principle with a 'Single Page' or 'Template' style application):

http://localhost:3000/ (home page)
http://localhost:3000/new-entry (add message page)

This demo is meant to be fairly simple and uncomplicated, so those new to the MEAN stack or Express.js and third-party modules will have a chance to thoroughly digest all components.

Enjoy!


Tramel Woodard
