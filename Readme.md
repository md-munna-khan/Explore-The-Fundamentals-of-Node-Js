
Welcome to the new mission, today we pull back the curtain on how the web truly works and introduce you to the powerful world of Node.js! 🌐



In this module, you'll gain a solid understanding of the internet’s backbone—from how a browser talks to a server, to the difference between frontend and backend, and why Node.js is a game-changer in modern development.



We’ll explore:

The magic of the event loop 🌀 and how Node.js handles millions of requests without breaking a sweat,
The single-threaded nature of Node.js and how it still manages to stay lightning fast ⚡,
How to install Node.js like a pro using fnm (no more versioning nightmares!),
And master the modular system that makes Node.js both clean and powerful—CommonJS, ES Modules, IIFE, index exports—you’ll cover it all!


By the end of this module, you’ll not only understand the “what” but the “why” behind Node.js and how it's structured to be efficient, modular, and scalable. Whether you're building APIs, tools, or full-stack apps, these concepts will level up your backend journey in no time.



Node.JS Documentation: https://nodejs.org/en/learn/getting-started/introduction-to-nodejs



Let’s get started and unlock the server-side superpowers of JavaScript! 💪

# Explore The Fundamentals of Node.js

## 12-1 How the web works
- Request Response Model / Client-Server Architecture
![alt text](image.png)
- https ==> Protocol
- web.programming-hero.com ===> Domain name
- success ==> Resource
![alt text](image-1.png)
- Domain Address is not real Address 
- real Address is api address in dns server as like 139.59.2345:443
![alt text](image-2.png)
![alt text](image-3.png)
 ##### tcp/ip socket connection
 - ip = internet protocol
 - tcp = transmission Control Protocol
 ![alt text](image-5.png)
 ![alt text](image-4.png)
## 12-2 Frontend vs Backend Development
###### static web site it is pre make website
- cross device not supported design all device create make extra responsive
- A static website is made up of fixed content — HTML, CSS, and maybe a little JavaScript. The content does not change unless a developer manually updates the code.
![alt text](image-6.png)
###### dynamic web side  server side rendering first order then he is maked
- A dynamic website can show different content and respond to user input. It uses server-side languages (like Node.js, PHP) and databases (like MongoDB, MySQL) to generate content dynamically.

![alt text](image-7.png)
###### Dynamic website client side rendering using api
- This is a modern and popular approach. The frontend is built using frameworks like React.js, and it gets content/data from an API — often from a backend server or a third-party service.
![alt text](image-8.png)
![alt text](image-9.png)
 ###### Benefits of using API
 - cross device supported all device auto design selected phone,laptop etc
 - one data model create multiple device application
![alt text](image-10.png)

## 12-3 Why Node.js was invented
![alt text](image-11.png)
- 2 dependencies
![alt text](image-12.png)
![alt text](image-13.png)
![alt text](image-14.png)
##### LipUv implements 2 important parts of node.js
- 1 even Loop connect with v8 engine
- 2 thread Pool cpu intensive task 
![alt text](image-15.png)

## 12-4 High Level Overview of Node.js Architecture
![alt text](image-16.png)
 ##### what is process?
your instruction ==> Disk ====> Ram (this is process)

![alt text](image-17.png)

 ##### What is a Single Thread?
A thread is like a lane of execution — where your program runs step by step.

A Single Thread means your program runs one task at a time, in order
![alt text](image-18.png)
![alt text](image-19.png)