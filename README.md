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
* [Further Reading](http://natureofcode.com/book/further-reading/)

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
    * [Particle System API, by David K. McAllister](http://www.siggraph.org/education/materials/HyperGraph/animation/particle.htm)
    * [Particle Systems by Allen Martin](http://www.cs.unc.edu/+++~+++davemc/Particle/)

Week 5 - Physics Libraries - 3/3/14
-----------------------------------
* [Nature of Code Chapter 5: Physics Libraries](http://natureofcode.com/book/chapter-5-physics-libraries/)
* Box2D
    * [Box2D web site](http://box2d.org/)
    * [JBox2D web site](http://www.jbox2d.org/)
    * [PBox2D github repo](https://github.com/shiffman/PBox2D)
    * [Videos 5.1 - 5.9](http://video.natureofcode.com/5.1/)
    * [Processing examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp5_physicslibraries/box2d)
    * p5.js coming soon
* Toxiclibs
    * [Videos 5.13 - 5.16](http://video.natureofcode.com/5.1/)
    * [Processing examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp5_physicslibraries/toxiclibs)
    * p5.js coming soon
    * [ToxicLibs](http://toxiclibs.org/)
    * [The Making of Nokia Friends](https://vimeo.com/1472427)
    * [Advanced Character Physics](http://www.gamasutra.com/resource_guide/20030121/jacobson_pfv.htm)
* Bullet
    * [bRigid Processing Library](http://www.lab-eds.org/bRigid)
* Other libraries?
* Homework TBA (exercise picking one physics library)
* Supplemental Reading
    * TBA

Week 6 - Autonomous Agents - 3/10/14
-----------------------------------
* [Nature of Code Chapter 6](http://natureofcode.com/book/chapter-6-autonomous-agents/)
* [Processing Examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp6_agents)
* p5.js examples coming soon
* Related
    * [Reas Process Compendium](https://vimeo.com/22955812)
    * [Braitenberg Vehicles](http://books.google.com/books/?id=7KkUAT_q_sQC)
    * [Craig Reynolds' Steering Behaviors for Autonomous Characters](http://www.red3d.com/cwr/steer/)
* Homework.  Prepare a midterm project presentation.  Your midterm can be anything that *builds off of* or *is inspired by* the concepts we've covered this first half of the semester (motion and physics).  You should feel free to think non-traditionally, i.e. your midterm need not be a Processing sketch.  The midterm does not need to be a fully realized project, it is useful to use this time to build out a single component of a larger idea or test out a concept that you are thinking about for a final.  If you are stuck, feel free to come and talk to me.  Or try one of these suggestions:
    * Extend one of the examples into 3D
    * Design a simulation of a single creature (that you imagine living in a larger eco-system).
    * Develop a non keyboard/mouse way of interacting with an environments' forces (i.e. video tracking, sensors, etc.)
    * Use physics simulation to fabricate something -- a print, a sculpture, etc.
    * You could also try one of these exercises about steering behaviors
        * Implement seeking a moving target, often referred to as “pursuit.“  In this case, your desired velocity won't point towards the object's current location, rather its “future“ location as extrapolated based on its current velocity.
        * Create a sketch where a Vehicle's maximum force and maximum speed do not remain constant, but rather vary according to environmental factors.
        * Create a flow field that changes over time
        * Create a flow field based on image data
        * Expand the path following example to have a path that changes over time.  Can the points that define the path itself have their own steering behaviors?
        * Create something inspired by Braitenberg's Vehicles
        * Flocking
            * Implement Flake's "View" rule, described in Computational Beauty of Nature
            * Create a flocking simulation where all of the parameters (separation weight, cohesion weight, alignment weight, maximum force, maximum speed) change over time.  They could be controlled by Perlin noise or by user interaction.
            * Build a creature with countless steering behaviors (as many as you can reasonably add).  Think about ways to vary the weights of these behaviors so that you can dial those behaviors up and down, mixing and matching on the fly.    How are creatures' initial weights set?  What rules drive how the weights change over time?
            * Use applyForce() in Box2D or addForce() in Toxiclibs to create a flocking simulation in one of those physics engines
            * Complex systems can be nested.  Can you design a single creature out of a flock of boids?  And can you then make a flock of those creatures?
    * If you are still struggling for ideas, here are some links to midterm projects from previous years:
        * [Dollee's Mon Mon Monsters](http://itp.nyu.edu/~db2497/itp/?p=329)
        * [Mark's Plop Plop Fizz Fizz](http://www.markbreneman.com/blog/2012/03/06/plop-plop-fizz-fizz/)
        * [Natalie's Trees](http://itp.nyu.edu/~nbe206/blog/?p=673)
        * [Ben's Genetic Verlet Physics](http://blog.benturner.com/2012/03/07/nature-of-code-midterm-genetic-crossing-with-verlet-physics/)
        * [Peter's Name Swarm](http://stu.itp.nyu.edu/~pmd299/NOC/midterm/)
        * [Nick's Cosmic Crossfire](http://nicksantan.com/blog/2012/03/cosmic-crossfire/)
        * [Jannae's Collide](http://jann.ae/collide/)
        * [Mark's Waiting Game airport project](http://stu.itp.nyu.edu/~mk3981/blog/?p=1311)

### No class, 3/17/14, Spring Break

Week 7 - Mid-Semester Project Presentations - 3/24/14
-----------------------------------------------------
* Schedule TBA

Week 8 - Cellular Automata / Fractals - 3/31/14
-----------------------------------------------
* Cellular Automata
    * [Nature of Code Chapter 7](http://natureofcode.com/book/chapter-7-cellular-automata/)
    * [Processing Examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp7_CA)
    * p5.js examples coming soon
    * [A New Kind of Science](http://www.wolframscience.com/nksonline/toc.html)
    * [Elementary Cellular Automaton](http://mathworld.wolfram.com/ElementaryCellularAutomaton.html)
    * [2D Water Ripples CA](http://freespace.virgin.net/hugo.elias/graphics/x_water.htm)
* Fractals
   * [Nature of Code Chapter 8](http://natureofcode.com/book/chapter-8-fractals/)
   * [Processing Examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp8_fractals)
   * p5.js examples coming soon
   * [PBS Nova - Fractals - Hunting the Hidden Dimension](http://www.youtube.com/watch?v=LemPnZn54Kw)
   * [Fractal Geometry of Nature](http://en.wikipedia.org/wiki/The_Fractal_Geometry_of_Nature)
   * [How Long is the Coastline of Britain by Benoit Mandelbrot](http://en.wikipedia.org/wiki/How_Long_Is_the_Coast_of_Britain%3F_Statistical_Self-Similarity_and_Fractional_Dimension)
   * [Toby Schachman's Recursive Drawing](http://recursivedrawing.com/)
   * [Algorithmic Beauty of Plants](http://algorithmicbotany.org/papers/#abop)
   * [L-Systems in Computational Beauty of Nature](http://books.google.com/books?id=0aUhuv7fjxMC&pg=PA78)
*  Assignment: Final Project Proposal.
   * Your final project is a four week assignment to be completed in two stages (proposal and implementation).  Proposals presentations will divided between weeks 9 and 10.
   * The final project should be a creative project that *builds off of* or *is inspired by* the concepts we've covered this semester.  You should feel free to think non-traditionally, final projects do not need to be screen-based or even involve programming.
   * For your proposal it's up to you to best present your idea, but at a minimum you should include:
       * Title and short paragraph description
	   * Visual documentation -- drawings, videos, images, code sketches, etc
	   * Links to inspiration and source material

Week 9 - Genetic Algorithms / Final Project Proposals - 4/7/14
--------------------------------------------------------------
* [Nature of Code Chapter 9](http://natureofcode.com/book/chapter-9-the-evolution-of-code/)
* [Processing Examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp9_ga)
* p5.js examples coming soon
* Final Project Proposal Schedule TBA

Week 10 - Neural Networks / Final Project Proposals - 4/14/14
--------------------------------------------------------------
* [Nature of Code Chapter 10](http://natureofcode.com/book/chapter-10-neural-networks/)
* [Processing Examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp10_nn)
* p5.js examples coming soon
* Final Project Proposal Schedule TBA

Week 11 - User Testing Week - 3/21/14
-------------------------------------
* Guidelines TBA

Week 12 - Final Project Presentations - 3/28/14
-----------------------------------------------
* Presenation Schedule and Guidelines TBA
