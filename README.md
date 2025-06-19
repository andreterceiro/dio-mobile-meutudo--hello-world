# Introduction

![Engines](images/engines.png)

Teacher refered to the "user interface" in the previous image as CSS.

After teacher talked about V8 and Libuv and explained that Ryan Dahl (creator of Node.js and Deno) obtained the V8 engine from Chrome and made the interatction of V8 and a operating system with Libuv.

![V8 and Libuv](images/v8-and-libuv.png)

To be more clear, see the Node.JS components:

![Node.JS components](images/nodejs-components.png)

Teacher explained that after the code being interpreted by V8, the result is a JavaScript object, which is then passed to the Libuv. Libuv is a C++ library that provides an asynchronous I/O interface for Node.js.