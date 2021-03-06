# The Nature of Code, NYUAD, JTerm 2016, NYC

Can we capture the unpredictable evolutionary and emergent properties of nature in software? Can understanding the mathematical principles behind our physical world world help us to create digital worlds? This class focuses on the programming strategies and techniques behind computer simulations of natural systems. We explore topics ranging from basic mathematics and physics concepts to more advanced simulations of complex systems. Subjects covered include forces, trigonometry, fractals, cellular automata, self-organization, and genetic algorithms. No computer programming experience is required, the course will start with the basics of code using HTML, CSS, and JavaScript (with the [p5js](http://p5js.org/) framework). In addition to learning technical skills and discussing scientific concepts, students will have the opportunity to visit science museums, art galleries, and artist studios in the NYC area. 

* Daniel Shiffman, daniel dot shiffman at nyu dot edu
* Course Number: COREA-AD 17J (Cross-listed with Interactive Media and Technology)
* Meets daily: 10am - 1pm
* Office hours daily: 2pm - 3pm (and by appointment via e-mail)
* Credit Hours 4
* [Class google group for discussion / questions / announcements](https://groups.google.com/a/itp.nyu.edu/group/nature-of-code-abu-dhabi?hl=en)
* [Homework wiki](https://github.com/shiffman/The-Nature-of-Code-JTerm-2016/wiki)
* [p5.js web site](http://p5js.org)
* [p5.js web editor](http://p5ide.herokuapp.com/editor)
* [p5.js web editor github](https://github.com/therewasaguy/p5js-webIDE)
* [Getting Started with p5 code](https://github.com/lmccart/gswp5.js-code)
* [All p5.js Nature of Code examples](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js/)

## Field Trips
* [Museum of Math](http://momath.org/) - Friday, Jan 8, 2:00 - 3:30 pm (details TBA)
* [American Museum of Natural History](http://www.amnh.org/) - Monday, Jan 11, details TBA
* [Second Story](http://secondstory.com/) -- Tues, Jan 12, details TBA
* [Lab at Rockwell](http://www.rockwellgroup.com/search/LAB) -- Wed, Jan 13, details TBA
* [New York Hall of Science](http://nysci.org/) - Friday, Jan 15 -- meet at the museum at 1:45pm.
* [Eyebeam Art and Technology Center](http://eyebeam.org/) -- Tues, Jan 19, detials TBA

## Class 1 -- Introduction -- Monday, Jan 4
* Meets 2-4:30pm today (as to not conflict with morning orientation).
* What is computational media?
  * What is programming?
  * How can I apply programming to my field of interest?
  * [Example projects](https://github.com/ITPNYU/ICM-2015/wiki/Projects).
  * What is the potential for software within the visual arts?
  * As a ____________, why would I want or need to write software?
* Programming language discussion
  * General discussion of programming languages
  * History of creative coding frameworks
      * Processing and p5.js (and what's processing.js?): [What is p5.js video](https://vimeo.com/channels/learningp5js/137979313)
      * openframeworks, cinder
      * max/msp dataflow programming
      * How does arduino fit in?
* p5.js in the context of the browser
  * Landscape of HTML, CSS, and JavaScript
  * Other JS frameworks
  * Server-side vs. client-side
  * What is the difference between p5 and JavaScript?
  * Development options -- [p5.js web IDE](https://github.com/therewasaguy/p5js-webIDE), [p5.js desktop IDE](https://github.com/processing/p5.js-editor), [your own local server](https://github.com/processing/p5.js/wiki/Local-server)
  * Though this will be unnecessary since we are using the web IDE, you might also want to check out [how to upload](https://github.com/ITPNYU/ICM-2015/wiki/SFTP-Tutorial)
* Participating in an open-source community
  * What are git and github?
  * When should you post to a forum vs. file a github issue?
  * Who makes these things?
* Basics of blogging
  * Introduction to wordpress
  * Your blog is at yournetid.nyuad.im/blog.  Follow the install instructions at that link (it should be fairly self explanatory).  If you are stuck you can watch this [video walkthrough](https://www.dropbox.com/s/mz1tt4guamnmgl9/wordpress.mov?dl=0).
  * [If you want to get a bit more into wordpress, you can start here](http://codex.wordpress.org/First_Steps_With_WordPress).
* Supplemental Reading / Watching
  * Read p. 8-41 of Form + Code
  * Getting Started with p5.js: Chapters 1-3
  * [Videos 1.0-1.3](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)

## Class 2 -- Drawing and Animation -- Tues, Jan 5
  * Drawing
    * [Examples](https://github.com/shiffman/The-Nature-of-Code-JTerm-2016/tree/master/01_drawing)
    * Drawing with numbers: [video tutorial](https://vimeo.com/channels/learningp5js/137979314)
    * Shape and color functions: [video tutorial](https://vimeo.com/channels/learningp5js/137979312)
    * [Sol Lewitt](http://www.massmoca.org/lewitt/)
  - Program flow (what's a function?)
    - Setup, draw, and other events
    - Variation: mouseX and mouseY
    - [video tutorial](https://vimeo.com/channels/learningp5js/138327548)
  - More about variables
    - make your own variables (numbers and strings), [video tutorial](https://vimeo.com/channels/learningp5js/138331676)
    - JS objects (variables inside variables), [video tutorial](https://vimeo.com/channels/learningp5js/138327558)
  - [random()](http://p5js.org/reference/#/p5/random), [video tutorial](https://vimeo.com/channels/learningp5js/138327559)
  - [map()](http://p5js.org/reference/#/p5/map), [video tutorial](https://vimeo.com/channels/learningp5js/138331801)
  - [Transformations](http://www.genekogan.com/code/p5js-transformations/)
  * [Reading / Homework]](https://github.com/shiffman/The-Nature-of-Code-JTerm-2016/wiki/Assignment-1)

## Class 3 -- Interaction and Functions -- Wed, Jan 6
 - Conditional Statements
    - Boolean expressions
    - if statement
    - relational operators
    - [video tutorial](https://vimeo.com/channels/learningp5js/138935676)
    - Case study, bouncing ball: [video tutorial](https://vimeo.com/channels/learningp5js/138935675)
    - else, else if, and, or [video tutorial](https://vimeo.com/channels/learningp5js/138935678)
    - buttons, rollovers, switches [video tutorial](https://vimeo.com/channels/learningp5js/138935677)
 - Loops (while and for)
    - while and for [video tutorial](https://vimeo.com/channels/learningp5js/139013336)
    - nested loops [video tutorial](https://vimeo.com/channels/learningp5js/139013372)
 - Functions
    - Calling vs. defining
    - Modularity: [video](https://vimeo.com/channels/learningp5js/139587733)
    - Arguments and parameters
    - Re-usability: [video](https://vimeo.com/channels/learningp5js/139587732)
    - Return types: [video](https://vimeo.com/channels/learningp5js/139587730)
    - Functions inside objects: [video](https://vimeo.com/channels/learningp5js/139587731)
    - Recursion
      - [Fractals](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js/tree/master/chp08_fractals)
 - More on randomness and perlin noise
 - Intro to Objects
 * [Reading / Homework](https://github.com/shiffman/The-Nature-of-Code-JTerm-2016/wiki/Assignment-2)

## Class 4 -- Object Oriented Programming -- Thurs, Jan 7
- Transformations
- Perlin Noise
- Modulo
- Object Oriented Programming
  - Principles and Theory (Encapsulation)
  - JS literal object: [video tutorial](https://www.youtube.com/watch?v=-e5h4IGKZRY&index=7&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
    * properties - name/value pairs
    * functions inside objects
    * `this` keyword
  - Object "constructor" function: [video tutorial](https://www.youtube.com/watch?v=F3GeM_KrGjI&index=23&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
  - Clicking on objects: [video tutorial](https://www.youtube.com/watch?v=DEHsr4XicN8&index=26&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
  - Object intersection: [video 1](https://www.youtube.com/watch?v=uAfw-ko3kB8&index=28&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA), [video 2](https://www.youtube.com/watch?v=GY-c2HO2liA&index=29&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
* [Homework 3](https://github.com/shiffman/The-Nature-of-Code-JTerm-2016/wiki/Assignment-3)

## Class 5 -- Arrays and Loops, Museum of Math Field Trip -- Fri, Jan 8
- **New schedule!**
  - **Class will meet at our usual location at ITP from 10:30am - 12:00pm**
  - **We will then reconvene at the [Museum of Math](http://momath.org/) for a tour from 2:00-3:30pm**
- Review loops (while and for)
  - while and for [video tutorial](https://vimeo.com/channels/learningp5js/139013336)
  - nested loops [video tutorial](https://vimeo.com/channels/learningp5js/139013372)
* What is an array? [video tutorial 6.1](https://vimeo.com/141211396)
  * declaring, intializing
  * numeric indices
  * arrays and for loops: [video tutorial 6.2](https://vimeo.com/141211394)
  * `length` property
* An array of objects! [video tutorial 6.3](https://vimeo.com/141211395)
* Adding and deleting from an array, `push()` and `splice()` [video tutorial. 6.5](https://vimeo.com/141211392), [video tutorial 6.8](https://vimeo.com/141919523)
* [Homework 4](https://github.com/shiffman/The-Nature-of-Code-JTerm-2015/wiki/Assignment-4)

## Class 6 -- AMNH field trip -- Monday, Jan 11
**Meet at museum at 1:45pm, tour and planetarium from 2:00-4:00pm, time to explore 4-5:45pm.  Check e-mail for details.**

## Class 7 -- Images and Pixels and Second Story Trip -- Tues, Jan 12
- **New schedule!**
  - **Meet at 11am to go to [Second Story](http://secondstory.com/) for a tour starting at 12:00pm**
  - **Regular class will be from 3-4:30pm**
- Images
  - There are video lessons in progress about these topics in Processing.  They cover all the same content but the syntax in JavaScript is different.  [Videos 15.0 - 15.9](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YB9x6f23CBftiyx0u_5sO9)
  - Load and display images
  - Writing pixels to screen
  - Reading image pixels, image processing: brightness, threshold, etc
  - [Chapter 15 examples](https://github.com/shiffman/LearningProcessing-p5.js/tree/master/chp15_images_pixels)
  - In class exercise: make an interactive image processing filter
- Video and sound: 
  - [Code Examples](https://github.com/ITPNYU/ICM-2015/raw/master/09_video_sound/09_video_sound.zip)
  - [p5.sound reference](http://p5js.org/reference/#/libraries/p5.sound)
  - [Video/capture: p5.MediaElement reference](http://p5js.org/reference/#/p5.MediaElement)
  - [Chapter 16 examples](https://github.com/shiffman/LearningProcessing-p5.js/tree/master/chp16_video)
- Intro to Computer Vision
- Related reading:
  - [Computer Vision for Artists and Designers by Golan Levin](http://www.flong.com/texts/essays/essay_cvad/)
  - Learning Processing, Chapters 15-16
* [Homework 5](https://github.com/shiffman/The-Nature-of-Code-JTerm-2015/wiki/Assignment-5)

## Class 8 -- Data and Rockwell Labs Visit -- Wed, Jan 13
  - **Meet at 10am to go to [Rockwell Labs](http://www.rockwellgroup.com/search/LAB) for a tour starting at 11:00am**
  - **Regular class will be from 2-3:30pm**
* Intro to Data
  * events and callbacks
* Query strings
* Web services: AJAX, JSON, and APIs
* [Homework 6](https://github.com/shiffman/The-Nature-of-Code-JTerm-2015/wiki/Assignment-6)

## Class 9 -- Intro to Physics -- Thurs, Jan 14
  * **Regular class from 11am-2pm. At 1 pm we'll have lunch and presentations by ITP students.**
  * [Vectors](http://natureofcode.com/book/chapter-1-vectors/)
  * [Forces](http://natureofcode.com/book/chapter-2-forces/)
  * [Physics Libraries](http://natureofcode.com/book/chapter-5-physics-libraries/)
  * Additional Reading
    * Computational Beauty of Nature: introduction
    * Computational Beauty of Nature: Chapter 16
    * There are also the [Nature of Code videos](https://vimeo.com/channels/natureofcode).
  * [All examples](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js)
  * [Related and past projects](https://github.com/shiffman/The-Nature-of-Code-S14/wiki/Nature-of-Code-Related-and-Past-Projects)
* [Homework 7](https://github.com/shiffman/The-Nature-of-Code-JTerm-2015/wiki/Assignment-7)

## Class 10 -- Queens Hall of Science -- Friday, Jan 15
- **New schedule!**
  - **Class will meet at our usual location at ITP from 10:00am - 11:30am**
  - **We will then reconvene at the [NY Hall of Science](http://nysci.org/) for a tour from 2:00-3:30pm**
* Complex Systems:
  * [Autonomous Agents](http://natureofcode.com/book/chapter-6-autonomous-agents/), [Example code](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js/tree/master/chp06_agents)
  * [Cellular Automata](http://natureofcode.com/book/chapter-7-cellular-automata/), [Example code](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js/tree/master/chp07_CA)
  * [Fractals](http://natureofcode.com/book/chapter-8-fractals/), [Example code](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js/tree/master/chp08_fractals)
* [Nature of Code p5.js chapter 6 examples](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js/tree/master/chp06_agents)
* Reading:
  * [Craig Reynolds Steering Behavior](http://www.red3d.com/cwr/steer/)
  * Computational Beauty of Nature: Chapter 5-6, 15, 20
* [Create a final project proposal](https://github.com/shiffman/The-Nature-of-Code-JTerm-2016/wiki/Project-Proposal)

## Class 11 -- Final Project Proposals -- Tuesday, Jan 19
* **Meet at Eyebeam Art and Technology Center at 12pm, we will have class there until ~4pm**
* [Final Project Proposal](https://github.com/shiffman/The-Nature-of-Code-JTerm-2016/wiki/Project-Proposal)

## Class 12 - Final Project Workshop - Wed, Jan 20
* [ITP Unconference Schedule](http://itp.nyu.edu/unconference/)
* Evolutionary Computing session at 2pm in room 50
  * [Introduction to Genetic Algorithms](http://natureofcode.com/book/chapter-9-the-evolution-of-code/)
  * Also Chapter 20 in Computational Beauty of Nature
  * [Example code](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js/tree/master/chp09_ga)
* [Workshop Schedule](https://github.com/shiffman/The-Nature-of-Code-JTerm-2016/wiki/Final-Project-Workshop)

## Class 13 - Final Project Workshop and Presentations -- Thurs, Jan 21
* [ITP Unconference Schedule](http://itp.nyu.edu/unconference/)
* [Final Project Presentations](https://github.com/shiffman/The-Nature-of-Code-JTerm-2016/wiki/Final-Project-Presentations)

## Class 14 - Final Project Breakfast - Friday, Jan 22
* 9:30 - 11:30: breakfast and exhibiton
* Don't forget to [add your documentation links](https://github.com/shiffman/The-Nature-of-Code-JTerm-2016/wiki/Final-Project-Presentations)!

## Expectations
* Assignments will include readings, programming exercises, and written documentation of your work.
* Each student will be required to post their homework to the class blog (instructions provided in class).
* Over the course of the term, you should have completed ten blog posts (8 exercises, 1 final project proposal, 1 final project summary). In total this should amount to at least 7,000 words (equivalent to 18 double-spaced pages.) Each blog post should contain a written response to material presented in class (specific questions will be provided), a description of your homework assignment, and questions regarding the technical material.
* For your final project proposal and summary, you will be required to write about your project concept and project development process.
* Students will be expected to collaborate, to document their work, to make presentations and to discuss their ideas regularly in class.

## Teaching Methodologies
* Class time will be divided between technical lectures, independent project development, individual meetings with instructor, and project presentations / critique.
* In addition to regular class meetings, the instructor will organize a series of field trips to visit artist studios, gallery shows, and museum exhibits in the London area.

## Learning Outcomes
* Define the fundamentals of computation.
* Build creative software sketches that demonstrate knowledge of these fundamentals.
* Critically examine interactive art in the context of screen, sculpture, and web.
* Apply concepts from physics and mathematics to real-time software animation.
* Develop methodologies for simulating nature using computational algorithms.
* Propose and build a creative project made from computational methods.

## Grading
* Class Participation (attendance, discussions, project proposal and implementation presentations) : 25%
* Writing Assignments: 25%
* Programming Assignments: 35%
* Final Project: 15%

## Presenting in class
* One liner – What did you do?
* Content – Why did you do it? Who is the audience? How does it engage with the theoretical and technical concerns we have discussed in this class?
* Demo
* Comments/Critique

## Books
* The Nature of Code, Daniel Shiffman
* The Computational Beauty of Nature, Gary Flake
* Form + Code, Casey Reas / Chandler McWilliams
* Make: Getting Started with p5.js: Making Interactive Graphics in JavaScript and Processing, Lauren McCarthy, Casey Reas, Ben Fry
