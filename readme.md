# Homework Intro to node:

Follow these steps:
- Install `Node.js` and create a `Node.js ﬁle` called `HelloWorld.js`. This code should create a web server that returns a web page that says “Hey! I can use Node!”. Your web server should listen for HTTP requests on port 3000.


- Create a module called `primes.js` that ﬁnds and returns all the prime numbers between 1 and 100.


- Create a `Node.js` ﬁle called `myNumbers.js` that uses the module (primes.js) that you created. The program should:
  - Write the word “Primes:” and then the prime numbers returned by `primes.js` in a text ﬁle called `nums.txt`.

  - Write a message to the console that indicates whether the ﬁle was created successfully or not.
  - Read `nums.txt` and display the contents of this ﬁle in the browser when the user navigates to http://localhost:8000/

- Create a module called deleteFile.js that will delete nums.txt when called.
