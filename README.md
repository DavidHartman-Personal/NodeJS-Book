# Node.js Web Development - Fifth Edition

This is the code repository for [Node.js Web Development - Fifth Edition](https://www.packtpub.com/web-development/node-js-web-development-fifth-edition?utm_source=github&utm_medium=repository&utm_campaign=9781838987572), published by Packt.

**Server-side web development made easy with Node 14 using practical examples**

## What is this book about?
Node.js is the leading choice of server-side web development platform, enabling developers to use the same tools and paradigms for both server-side and client-side software. This updated fifth edition of Node.js Web Development focuses on the new features of Node.js 14, Express 4.x, and ECMAScript, taking you through modern concepts, techniques, and best practices for using Node.js.

This book covers the following exciting features: 
* Install and use Node.js 14 and Express 4.17 for both web development and deployment
* Implement REST services using the Restify framework
* Develop, test, and deploy microservices using Kubernetes and Node.js
* Get up to speed with using data storage engines such as MySQL, SQLite3, and MongoDB
* Secure your web applications using headless browser testing with Puppeteer
* Implement HTTPS using Let's Encrypt and enhance application security with Helmet

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1838987576) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Chapter 2 Notes

### Setup of WebStorm
Added a package.json file to this project and added dependencies into the file.  WebStorm prompted to use npm to install those packages.

E.g. When hexy was added to the packages.json file, the version options were prompted for and then Webstorm prompted to use npm and install them.  These end up getting installed in the node_modules/ directory.
```json
{
  "name": "NodeJS-Book",
  "version": "1.0.0",
  "dependencies": {
    "hexy": "^0.3.4"
  }
}
```