The Nature of Code (Spring 2014)
================================

Key info
--------
* Daniel Shiffman
* Mondays, 11:00am - 1:55pm, ITP Room 50
* [Office Hours Signup](https://itp.nyu.edu/inwiki/Signup/Shiffman)

Key Links
---------
* [All coures videos](http://video.natureofcode.com/)
* [Online textbook](http://natureofcode.com/book/)
* [All code examples in Processing](https://github.com/shiffman/The-Nature-of-Code-Examples)
* [Code examples ported to p5.js](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js)
* [Other ports](https://github.com/shiffman/The-Nature-of-Code-Examples/blob/master/README.md)

Related Reading and Watching
----------------------------
* [Coding Math Video Series](http://www.youtube.com/user/codingmath)
* [Generative Design with Processing](http://www.amazon.com/gp/product/1616890770/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1616890770&linkCode=as2&tag=natureofcode-20)
* [Mathematics and Physics for Programmers](http://www.amazon.com/gp/product/1435457331/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1435457331&linkCode=as2&tag=learniproces-20)
* [Computational Beauty of Nature](http://www.amazon.com/gp/product/0262561271/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=0262561271&linkCode=as2&tag=natureofcode-20)
* [Form and Code](http://formandcode.com/)

Mailing List
------------
- [Sign up here](https://groups.google.com/a/itp.nyu.edu/forum/#!forum/natureofcode)

Week 1 - Introduction - 1/27/14
-------------------------------

* Class Intro / Overview
    * [Related and Past Projects](https://github.com/shiffman/The-Nature-of-Code-S14/wiki/Nature-of-Code-Related-and-Past-Projects)
* [Processing](http://www.processing.org) review
* [p5.js Discussion](https://github.com/lmccart/p5.js)
* Randomness, Probability, and Perlin Noise
    * [Nature of Code Introduction](http://natureofcode.com/book/introduction/)
    * [Videos I.1 - I.5](http://video.natureofcode.com/i.1/)
    * [Processing examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/introduction)
    * [p5.js examples](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js/tree/master/introduction)
* Object Oriented Programming Review & Vectors
    * [Nature of Code Chapter 1](http://natureofcode.com/book/chapter-1-vectors/)
    * [Videos 1.1 - 1.6](http://video.natureofcode.com/1.1/)
    * Note the above videos will be screened Thursday, Jan 30th in room 15 from 1-2pm.  Mimi Yin is working on a video annotation project and will be using this session user testing (and also available to answer your questions about vectors!)
    * [Processing examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp1_vectors)
    * p5.js examples coming soon
* Assignment
    * [Sign up for class mailing list](https://groups.google.com/a/itp.nyu.edu/forum/#!forum/natureofcode)
    * Develop a Processing sketch (or program in the environment of your choosing) that experiments with motion. You should feel free to design your own assignment.  If you are stuck for an idea here are some suggestions.  
        * Create a random walker with dynamic probabilities.  For example, can you give it a 50% chance of moving in the direction of the mouse?
        *  Gaussian random walk is defined as one in which the step size (how far the object moves in a given direction) is generated with a normal distribution.  Implement this variation of our random walk.
        * Try implementing a [self-avoiding walk](http://en.wikipedia.org/wiki/Self-avoiding_walk).
        * Try implement the random walk known as [a Levy Flight](http://en.wikipedia.org/wiki/L%C3%A9vy_flight).
        * Try a walk in 3D, for example: [http://en.wikipedia.org/wiki/Quantum_Cloud](http://en.wikipedia.org/wiki/Quantum_Cloud).
        * Use the random walker as a template to simulate some real-world "natural" motion. Can you develop a set of rules for simulating that behavior?  Ideas: nervous fly, hopping bunny, slithering snake, etc.  (Consider the challenge of using minimal visual design, i.e. b&w primitive shapes.  Can you give your "being" a personality?  Can it express emotions -- happiness, sadness, fear, etc.?  
        * There are also more exercises in [The Nature of Code Introduction](http://natureofcode.com/book/introduction/).
    * *You'll need to create a web page to document your homework.*  It could be as simple as the auto-generated page created by Processing's JavaScript mode.  It could also be a blog post or something custom you design.  NOTE TO SELF: ADD LINK TO WIKI HERE
 * Supplemental Reading
    * [Mathematics and Physics for Programmers](http://www.amazon.com/gp/product/1584503300/) Chapter 5
    * [Computational Beauty of Nature](http://www.amazon.com/gp/product/0262561271/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=0262561271&linkCode=as2&tag=natureofcode-20), Introduction
    * [Probability Theory](http://www.probabilitytheory.info/)


Week 2 - Forces - 2/3/14
------------------------
* [Nature of Code Chapter 2: Forces](http://natureofcode.com/book/chapter-2-forces/)
* [Videos 2.1 - 2.6](http://video.natureofcode.com/2.1/)
* [Processing examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp2_forces)
* [p5.js examples](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js/tree/master/chp2_forces)
* Assignment: Choose one or create your own. Post your work as a link in the comments below.
    * Rework your motion sketch from week 1 using PVector.  Try incorporating the concept of _forces_ into the environment by affecting _only_ the acceleration.   Create a formula for calculating a dynamic acceleration, one that changes over time based on any number of factors.  What happens if you make more than one object via an array.
    * Using forces, simulate a helium-filled balloon floating upward (and bouncing off the top of a window).  Can you add a wind force which changes over time, perhaps according to Perlin noise?
    * Create an example where instead of objects bouncing off the edge of the wall, an invisible force pushes back on the objects to keep them in the window.  Can you weight the force according to how far the object is from an edge, i.e. the closer it is, the stronger the force?   
    * Create pockets of air resistance / friction in a Processing sketch.  Try using circles instead of rectangles, i.e. pockets of mud (or ice).  What if you vary the strength (drag / friction coefficient) of each circle?   What if you make some of them the opposite of drag—i.e., when you enter a given pocket you actually speed up instead of slow down?
    * Can you create an example where all of the Mover objects are attracted to the mouse, but repel each other?  Think about how you need to balance the relative strength of the forces and how to most effectively use distance in your force calculations.
    * Research a force not covered in class and implement it as a vector.
    * Use the concept of forces to visualize some input (could be data, literal example would be get windspeed online and translate to a wind force in Processing, but feel free to think more abstractly)
    * Build a sketch that has both "Movers" and "Attractors".  What if you make the Attractors invisible?  Can you create a pattern / design from the trails of objects moving around attractors?  See the [Metropop Denim project by Clayton Cubitt and Tom Carden](http://processing.org/exhibition/works/metropop/) for an example.
* Just as with last week, please create a web page to document your homework. Make sure it include some visual documentation of your work as well as the source code.
* Supplemental Reading
    * [Newtonian Physics, An Online Textbook](http://www.lightandmatter.com/area1book1.html) (This is long, you may find Chapter 4 to be particularly relevant to this week's discussion.)
    * [The Physics Classroom -- Newton's Laws](http://www.physicsclassroom.com/Class/newtlaws/newtltoc.html)
    * [Mathematics and Physics for Programmers](http://www.amazon.com/gp/product/1584503300/), Chapters 12 and 14

Week 3 - Oscillation - 2/10/14
-------------------------------
* [Nature of Code Chapter 3: Oscillation](http://natureofcode.com/book/chapter-3-oscillation/)
* [Videos 3.1 - 3.5](http://video.natureofcode.com/3.1/)
* [Processing examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp3_oscillation)
* p5.js coming soon
* Assignment: Incorporate oscillatory motion into a previous assignment (or create a new one).  Some suggestions:
    * Design a creature with oscillating parts (legs, wings, antennae, etc.)  Consider tying the speed of oscillation to the speed of the creature's linear motion.  Can you make it appear that the creature's internal mechanics (oscillation) drive its locomotion? [Example solution](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/Processing/chp3_oscillation/NOC_3_07_oscillating_objects)
    * Create a simulation where objects are shot out of a cannon.  Each object should experience a sudden force when shot (just once) as well as gravity (always present).   Add rotation to the object to model its spin as its shot from the cannon.  How realistic can you make it look?
    * Create a simulation of a vehicle that you can drive around the screen using the arrow keys: left arrow accelerates the car to the left, right to the right.  The car should point in the direction it is currently moving.
    * Simulate the spaceship in the game Asteroids.   In case you aren't familiar with Asteroids, here is a brief description. A spaceship (represented as a triangle) floats in two dimensional space.   The left arrow keys turns the spaceship counter-clockwise, the right clock-wise.  The space bar applies a “thrust“ force in the direction the spaceship is pointing. [Example Solution](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/Processing/chp3_oscillation/Exercise_3_05_asteroids)
    * String together a series of pendulums so that the endpoint of one is the origin point of another.
    * Use trigonometry to model a box sliding down an incline with friction.  Note that the magnitude of the friction force is equal to the normal force. 
    * Rework the wave examples to have a Wave class and visualize the wave using something other than circles. [Example Answer (minus the change in visualization)](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/Processing/chp3_oscillation/Exercise_3_10_OOPWave)
    * Using the Spring example as a basis, create a system of multiple bobs and spring connections.  How would you have a Bob connected to a Bob with no fixed anchor?
    * Research and implement a simulation of [Torque](http://en.wikipedia.org/wiki/Torque).
* As always, please create a web page to document your homework. Make sure it include some visual documentation of your work as well as the source code.
* Supplemental reading
    * The Mathematics of Oscillatory Motion (refer to e-mail to class list.)
    * [Trigonometry, What is it good for?](http://www.phy6.org/stargaze/Strig1.htm)
    * [Mathematics and Physics for Programmers](http://www.amazon.com/gp/product/1584503300/), Chapter 4  

### No class, 2/17/14, Presidents Day

Week 4 - Systems - 2/24/14
-------------------------------
* [Nature of Code Chapter 4: Systems](http://natureofcode.com/book/chapter-4-systems/)
* [Videos 4.1 - 4.9](http://video.natureofcode.com/4.1/)
* [Processing examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp4_systems)
* p5.js coming soon
* Assignment:  Try one of the following or design your own.
    * Use a particle system in the design of a "Mover" object.  In other words take, say, one of our earlier examples and instead of rendering a Mover object as a simple circle, emit particles from the mover's location.  For example, building off [Chapter 3’s "Asteroids" example](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/Processing/chp3_oscillation/Exercise_3_05_asteroids), use a particle system to emit particles from the ship’s “thrusters” whenever a thrust force is applied. The particles’ initial velocity should be related to the ship’s current direction.
    * Create a particle system where the particles respond to each other via forces.  For example, what if you connect the particles with spring forces?  Or an attraction / repulsion force?
    * Model a specific visual effect using a particle system -- fire, smoke, explosion, waterfall, etc.
    * Create a simulation of an object shattering into many pieces. How can you turn one large shape into many small particles? What if there are several large shapes on the screen and they shatter when you click on them?
    * Create a particle system in which each particle responds to every other particle.  (Note we'll be doing this in detail in Week 6.
    * Create a particle system with different “kinds” of particles in the same system. Try varying more than just the look of the particles. How do you deal with different behaviors using inheritance?
    * Use an array of images and assign each Particle object a different image. Even though single images are drawn by multiple particles, make sure you don’t call loadImage() any more than you need to, i.e. once for each image file.
* As always, please create a web page to document your homework. Make sure it include some visual documentation of your work as well as the source code.
* Supplemental Reading
    * ["Particle animation and rendering using data parallel computation", Karl Sims](http://doi.acm.org/10.1145/97879.97923) (available via NYU network/proxy)
    * ["Particle Systems, a Technique for Modeling a Class of Fuzzy Objects", Reeves](http://doi.acm.org/10.1145/357318.357320) (available via NYU network/proxy)
    * [How my Dog learned Polymorphism](http://www.javaranch.com/campfire/StoryPoly.jsp)
    * [Particle Systems (Siggraph)](http://www.siggraph.org/education/materials/HyperGraph/animation/particle.htm), [Particle System API, by David K. McAllister](http://www.cs.unc.edu/+++~+++davemc/Particle/), [Particle Systems by Allen Martin](http://www.cs.wpi.edu/+++~+++matt/courses/cs563/talks/psys.html)

Week 5 - Physics Libraries - 3/3/14
-----------------------------------
* [Nature of Code Chapter 5: Physics Libraries](http://natureofcode.com/book/chapter-5-physics-libraries/)
* Box2D
    * [Videos 5.1 - 5.9](http://video.natureofcode.com/5.1/)
    * [Processing examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp5_physicslibraries/box2d)
    * p5.js coming soon
* Toxiclibs
    * [Videos 5.13 - 5.16](http://video.natureofcode.com/5.1/)
    * [Processing examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp5_physicslibraries/toxiclibs)
    * p5.js coming soon
* Bullet
    * [bRigid Processing Library](http://www.lab-eds.org/bRigid)
* Other libraries?
* Homework TBA (exercise picking one physics library)

Week 6 - Autonomous Agents - 3/10/14
-----------------------------------

### No class, 3/17/14, Spring Break

Week 7 - Mid-Semester Project Presentations - 3/24/14
-----------------------------------------------------

Week 8 - Cellular Automata / Fractals - 3/31/14
-----------------------------------------------

Week 9 - Genetic Algorithms - 4/7/14
------------------------------------

Week 10 - Final Project Proposals - 3/14/14
-------------------------------------------

Week 11 - User Testing Week - 3/21/14
-------------------------------------

Week 12 - Final Project Presentations - 3/28/14
-----------------------------------------------
