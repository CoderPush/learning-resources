# https://roadmap.sh/backend
## **Node.js lite**


1. Explain the origin of Node.js from **[V8](https://v8.dev/)**.
2. **[ECMA](https://tc39.es/ecma262/)** is specs and **[V8](https://v8.dev/)** is implementation of that specs. In 4-5 sentences, explains this as easy to understand as talking to a 10 years old child.
3. One key thing in design that makes Node.js popular is Node.js is an event driven and non-blocking I/O. In 4-5 sentences, explains this concept.
4. Install **[Node.js](https://nodejs.org/en/)** to your local machine.
5. Node.js can do quite many things. Read the **[official docs](https://nodejs.org/dist/latest-v18.x/docs/api/)** and the internet to:


## Express.js HTTP server


1. What does it mean when Express calling itself as "Fast, unopinionated, minimalist web framework for Node.js"?
2. Create an HTTP server with Express
3. Express middleware is a clever way to create separate logic to handle an HTTP request. Write 3 separate middlewares to:

* 1st authentication: check if the request payload has secret key A. If yes, carry on to the next middleware. If no, reject the request with 403.
* 2nd role check: check if the request payload has role X to access this API. If yes, carry on to the next middelware. If no, reject the request with 403.
* 3rd response: wait for 2 seconds then return JSON { reward: here are your cookies } to the caller.

## **Cloud services**

* AWS: **[use free tier](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=\*all&awsf.Free%20Tier%20Categories=\*all)** (no cc required, no charge) to understand what popular services are and how to use them with Node.js: EC2, S3,…


## **HTTP/HTTPS server Nginx**


1. What is an HTTP/HTTPS server?
2. An HTTP/HTTPS server basically can response to any kinds of request from client. Watch this short **[Nginx Server introduction](https://www.youtube.com/watch?v=JKxlsvZXG7c&ab_channel=Fireship)** and reference **[Nginx official docs](http://nginx.org/en/docs/)**, as well as the internet if needed to:
   * install nginx to your local machine
   * serve html content with your nginx
   * serve images with your nginx
   * serve videos with your nginx
   * serve 404 with your nginx
   * serve 301 with your nginx
3. Nginx is known for its well performance. What is the __one__ most important feature in Nginx design that makes it gains such reputation?
4. What is a proxy server? Why do we need it? And why Nginx is usually used as a proxy server?


## **Unit test with Jest**


1. Test is to put our function in different scenarios (mimicking real life use) to make sure the function behave correctly, ideally in any situation in real life.
2. Tests help us to think ahead of time and predict what can happen with function inputs before shipping code. Hence, tests improve reliability and help to ship code with more confidence.
3. use **[Jest](https://jestjs.io/docs/api)** to setup test environment and test functions.
4. Use **[mock](https://jestjs.io/docs/mock-function-api)** and **[jest object](https://jestjs.io/docs/jest-object)** mock out external function calls to create more real life, sophisticated test cases.
5. What are the similarities and differences between **[mock](https://jestjs.io/docs/mock-function-api)** and **[jest object](https://jestjs.io/docs/jest-object)** functions?
