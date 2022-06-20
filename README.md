
<h1>Multithreaded-Server (Group Chat)</h1>
<hr>
This project aims to build a group chat application using Multithreading and Socket programming in C language.<br>
A simple server without multithreading can only deal with one client at a time, but using multithreading we can hadle multiple clients at once.<br>
By this once the server is active all the user can join the group and chat 

# How to Run Project
0. This project can only be compiled in linux based os.<br>
1. Install gcc compiler if not already installed.<br>
2. Open terminal in current directory and compile files using following commands "gcc server.c -o server" and "gcc clinet.c -o client".<br>
3. After compiling open terminal and type "./server <port>" to start server.(Replace <port> with any port like "8989" or "4040" or any port of choice.)<br>
4. After starting server now we can start adding clients by opening terminal (and typing "./client <port>),here <port> is same as mentioned in server.<br>
<hr>
  
# Learnings...
  
  1. Concept of Threads and Multithreading - working with threads and concept of mutex
  2. Socket Programming - reading and writing data from server and client
  3. How to deal with multiple client with the help of threads in such a way that their requested data do not clash with each other with the help of mutex.
  <hr>
  
# Resources
  <a href="https://www.geeksforgeeks.org/multithreading-c-2/">Multithreading in C</a>,
  <a href="http://www.csc.villanova.edu/~mdamian/threads/posixthreads.html">Threads</a>,
  <a href="https://www.geeksforgeeks.org/multithreading-in-cpp/?ref=rp">Multithreading in C++</a><br>
  <a href="https://www.geeksforgeeks.org/handling-multiple-clients-on-server-with-multithreading-using-socket-programming-in-c-cpp/?ref=rp">Multithreading and Socket programming</a>,
  <a href="https://tutorialspoint.dev/language/cpp/socket-programming-cc">Socket programming in C</a>,
  <a href="https://www.csd.uoc.gr/~hy556/material/tutorials/cs556-3rd-tutorial.pdf">Socket Programming in C </a>
<hr>
