# PWA Text Editor -J.A.T.E

This is web text editor that meets the PWA criteria The application can also be installed on computer or mobile device to be used outside of the browser.  Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser.
The integrated service worker and Cache API's ensure that the application will remain fully functional even without active internet connection.

To build this text editor, we have implemented methods for getting and storing data to an database. J.A.T.E uses an IndexedDB database and the idb package which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Credits](#credits)
- [Contact Information](#contact-information)


## Installation

- Download or clone repository from GitHub to local machine.
- This application will require the installation of Node.js and various npm packages
- Node Package Manager (npm) is the standard package manager for Node.js. The package.json file contains all the details related to required packages and versions of the application.
- Open the terminal and navigate to root level of directory. Install required dependencies  by running command:
   ```
   npm run install
   ```

## Technologies

- Express
- IndexedDB
- Webpack 
- Concurrently
- Babel, Babel extensions
- Nodemon