# The Trouble with Distribution

Accompanying repository for The trouble with distribution talk given at [J on the Beach]() 2017. Feel free to open any issues for questions and/or to say hi :)

### Abstract
Centralized applications are easy: your entire system lives in one physical location and you can reason about, vertically scale, and manage your system with minimal friction. Unfortunately, applications aren’t built this way anymore. Our systems are distributed, have external dependencies, and may even have to be geographically redundant.

Dealing with distribution is a must at Fastly, where our applications are deployed all over the world and must be highly performant and resilient. But there are some inherent challenges related to designing and building systems that scale. In this talk we’ll go over the key lessons we learned while building our Image Optimization service. What worked, what didn’t, the tradeoffs we made, and what can you do as a systems engineer to learn from our experiences while building your own applications.

### Outline

* Intro
* Context setting
* Hard things
  * Meeting your system goals
  * Deducing with no global state
  * Verifying your system
  * Ensuring resilience
* Conclusions


### References
* [Kyle Kingsbury's An introduction to distributed systems class notes](https://github.com/aphyr/distsys-class)
* [Alvaro Videla's What we talk about when we talk about Distributed Systems](http://alvaro-videla.com/2015/12/learning-about-distributed-systems.html)
* [Alvaro Videla's Failure modes in Distributed Systems](http://alvaro-videla.com/2013/12/failure-modes-in-distributed-systems.html)
* [Jeff Hodges's Notes on Distributed Systems for Young Bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods)
* [Distributed Computing: Principles, Algorithms, and Systems
Textbook by Ajay D. Kshemkalyani and Mukesh Singhal](https://www.cs.uic.edu/~ajayk/DCS-Book)
*

### Thank you!
Thank you to everyonw who helped with feedback, resources, and advice for this talk. Special thanks to: Tyler McMullen, Jed Denlea, Adam Thomason, Ian Fung, Elaine Greenberg, and Greg Bako.
