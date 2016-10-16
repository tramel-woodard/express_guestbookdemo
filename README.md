[![N|Solid](http://tramelwoodard:8888/public/images/global/tlw_icon.png)](http://tramelwoodard.com)
# Express.js Guestbook
This repository is a two-page guestbook demo running Express.js middleware on a Node.js server.

There are two main pages in this demo. The 'index' page where you may view current guestbook messages and a 'new-entry' page, where you may add your own message. Both pages are being served using the EJS (Extended JavaScript) template system.

### Installation
Clone the git repository to your local directory, change to the 'express_guestbookdemo' directory and install all dependencies from the package.json file using the 'npm install' command:
```sh
$ git clone git@github.com:tramel-woodard/express_guestbookdemo.git
$ cd express_guestbookdemo
$ npm install
```

### Installed Node Depedencies
The following Node modules have been installed from the package.json file in order to provide functionality to the guestbook:

* [body-parser] - Node.js body parsing middleware
* [EJS] - Embedded JavaScript templates
* [Express] - Node.js web application framework
* [Morgan] - HTTP request logger middleware for node.js

   [body-parser]: <https://github.com/expressjs/body-parser>
   [EJS]: <https://github.com/joemccann/dillinger.git>
   [Express]: <https://github.com/expressjs>
   [Morgan]: <http://twitter.com/thomasfuchs>

#### Running the Demo
Run the following command (in Terminal for Mac or Command Prompt for Windows) to launch the Guestbook demo:
```sh
$ npm start
```
Finally, open your preferred browser and visit the following URL:
```sh
http://localhost:3000
```
### Development
This is an open-sourced project. Please feel free to contribute. Code must use

### Todos
 - Individual Edit Capability for Messages
 - Possible conversion from JSON storage to MongoDB
 - Creation of Unit Test

License
----
ISC (License dependent upon individual node packages)
