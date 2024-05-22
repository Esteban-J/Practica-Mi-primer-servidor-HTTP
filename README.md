# Práctica | Mi primer servidor HTTP

This is an application that, through network manipulation, creates a server and manipulates http requests and responses made in a simple webpage, containing 4 different addresses.

## Getting Started

You can click the followin link to download the app source code files: https://github.com/Esteban-J/Practica-Mi-primer-servidor-HTTP/archive/refs/heads/main.zip

### Prerequisites

To be able to run and test the code above you'll need to have NodeJs already install in your system as this code is interpreted by the Node run-time enviorement.


### Installing

#### Installing Node

For Linux (using apt package manager, for Ubuntu/Debian):
```
sudo apt update
sudo apt install nodejs
sudo apt install npm
```

For macOS (using Homebrew):
```
brew update
brew install node
```

For Windows (using Chocolatey):
```
choco install nodejs
```

## Running a test
To execute  a test of the application run the following comand on a command line terminal:
```
node app.js
```
A server will be created.

Next, open a web browser and inside the address-bar type localhost:4444

The web browser will redirect you first to the home page of the website.

The following are the adrresses you can go to:

* (index.html) by entering localhost:4444
* (readme.txt) by entering localhost:4444/readme.txt
* (ventas.html) by entering localhost:4444/ventas.html
* (image.jpeg) by entering localhost:4444/images/image.jpeg

To check the implementation of the aplication you can press f12 to open the dev tools of the browser and corroborate if the "content type" of the current page corresponds to the extention type of the url.
  
This is how the aplication is manipulating and modyfing the responses made in the website.
 
## Built With

* javaSript
* NodeJs

## Authors

* **Jurado Carrera Gerardo Esteban**

## Acknowledgments

* Ramírez Martínez Luis Antonio

