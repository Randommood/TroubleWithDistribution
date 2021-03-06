# The Trouble with Distribution (and pugs)

Accompanying repository for The trouble with distribution talk given at [J on the Beach](http://jonthebeach.com/) 2017. Feel free to open any issues for questions and/or to say hi :)

You can find the slides [here](https://speakerdeck.com/randommood/the-trouble-with-distribution), video link coming soon.

### Abstract
Centralized applications are easy: your entire system lives in one physical location and you can reason about, vertically scale, and manage your system with minimal friction. Unfortunately, applications aren’t built this way anymore. Our systems are distributed, have external dependencies, and may even have to be geographically redundant. 

Dealing with distribution is a must at Fastly, where our applications are deployed all over the world and must be highly performant and resilient. But there are some inherent challenges related to designing and building systems that scale. In this talk we’ll go over the key lessons we learned while building our [Image Optimization service](https://www.fastly.com/io). What worked, what didn’t, the tradeoffs we made, and what can you do as a systems engineer to learn from our experiences while building your own applications.

### Outline
* Intro
* Context setting
* Hard things
  * Meeting your system goals
  * Deducing with no global state
  * Verifying your system
  * Ensuring resilience
* Conclusions

### Thank you!
Thank you to everyonw who helped with feedback, resources, and advice for this talk. Special thanks to: Tyler McMullen, Jed Denlea, Adam Thomason, Ian Fung, Joao Taveira, Ezekiel Templin, Ashok Lalwani, Matt Whiteley, Kyle Kingsbury, Peter Bourgon, Camille Fournier, Caitie McCaffrey, Lorenzo Saino, Elaine Greenberg, and Greg Bako.

### References
* [Kyle Kingsbury's An introduction to distributed systems class notes](https://github.com/aphyr/distsys-class)
* [Alvaro Videla's What we talk about when we talk about Distributed Systems](http://alvaro-videla.com/2015/12/learning-about-distributed-systems.html)
* [Alvaro Videla's Failure modes in Distributed Systems](http://alvaro-videla.com/2013/12/failure-modes-in-distributed-systems.html)
* [Jeff Hodges's Notes on Distributed Systems for Young Bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods)
* [Distributed Computing: Principles, Algorithms, and Systems Textbook by Ajay D. Kshemkalyani and Mukesh Singhal](https://www.cs.uic.edu/~ajayk/DCS-Book)
* [Harvest, Yield, and Scalable Tolerant Systems](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.24.3690&rep=rep1&type=pdf)
* [You can't sacrifice partition tolerance](http://codahale.com/you-cant-sacrifice-partition-tolerance/)
* ["Building Scalable Stateful Services" by Caitie McCaffrey](https://www.youtube.com/watch?v=H0i_bXKwujQ)
* [Clients are Jerks by Caitie McCaffrey](https://caitiem.com/2015/06/23/clients-are-jerks-aka-how-halo-4-dosed-the-services-at-launch-how-we-survived/)
* [Matt Ranney's Design for failure](https://www.youtube.com/watch?v=nuiLcWE8sPA)
* [Composability](https://en.wikipedia.org/wiki/Composability)
* [HTTP ETag](https://en.wikipedia.org/wiki/HTTP_ETag)
* [Fastly Shielding](https://docs.fastly.com/guides/performance-tuning/shielding)
* [Fastly ImageOpto API Docs](https://docs.fastly.com/api/imageopto/)
* [Fastly Imageopto Demo](https://www.fastly.com/io/)
* [Dynamic Servers](https://docs.fastly.com/api/dynamicservers)
* [facepug.io](http://http://facepug.io/)
* [ICC profiles](https://en.wikipedia.org/wiki/ICC_profile)
* [Pug reverse sneezing](https://www.youtube.com/watch?v=nIePT1-6HWk)
