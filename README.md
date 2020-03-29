# Learnings

* Node ships with a package called 'http'
* Http has a built-in function called createServer
* Require http and user http.createServer() to build your server
* createServer accepts a function that includes both a request and a response
* Node includes the "event loop", meaning it will run as long as a listener is active
* End the Node process using process.exit()
* Instruct your server to listen on a port using server.listen(PORT #)