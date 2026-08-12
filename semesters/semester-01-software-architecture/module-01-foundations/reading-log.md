# Reading Log

## Introduction (Chapter 1)

### Biggest Idea
---
This was an interesting introduction to Software Architecture - as it focused on the actula role of the architect vs. core architecture principles.  Seeing how the role of an architect and its many aspects - although somewhat relatable from my day-to-day job and interactions with LM Architects, helped get a better perspective on where I am in my career.

### Questions
* How to balance day-to-day deliverables and staying up-to-date with technologies?
* When is the 'stopping' point of deriving if this is the proper job/career path?

### Things I Disagree With
There are two points where I feel that I'm not 100% on board, or don't find much interest in.  One is `Politics` in the sense of software architect role.  I personally don't enjoy the ins-and-outs of handling the interpersonal relationships between the organization, and hope that my own deliveries can carry what I have.  On the other hand, I know one of my lacking areas is the issue of 'self-selling'.

Another aspect that I not necessarily disagree with, but better to acknowledge, is the idea of `Domain Knowledge`.  When solving individual problems on a technical level, I can excel just fine - it's just that during my own personal career progression, I'm finding the lack of domain knowledge intimidating when looking to make that next step up.

### How does this apply to Arena Simulator?
Although no direct points for architectural role as this is a solo project, there are a few points that popped up with my thought of building this out.

* Building an evolving architecture (MVP, and scaling up)
* Increasing my domain knowledge, and handling as much design up front as possible.
* Being my own 'business' side, and working to define my requirements (aka - game design) as well, to eliminate possible unknowns.
* Design for 'why' and now 'how'


### Follow-up Research
 * Handling 'Unknown unkowns'
 * Martin Fowler — *Who Needs an Architect?*


## Martin Fowler - *Who Needs an Architect?*

This section is a follow-up of the previous readings research.

### Article Biggest Idea
After reading through Martin's article on Architect and architecture, it showed me a couple different approaches to being an architect.  The bigest takeaway is the overall definition that it left, giving an idea that architecture is the decisions that you *wish* you had made.  Seeing this a little bit even in my current work project - we're doing a lot of design decisions and layout for the upcoming initiative that we are delivering.  Although the *architecture* of the application is mostly in place, it's us learning and adapting to it to make these major refactoring changes.

### Unknown Unknowns
One aspect from my first set of readings was the thought of handling 'unknown unknowns', and understanding 1) what they are and 2) how to deal with them.  Ironically enough, #1 was turning them into 'known unknowns'.  Now it comes down to finding the right strategy that works for me to better handle these.

After doing some brainstorming and figuring out strategies, one thing that I can actively participate in even in my current career is to better document and learn from mistakes - hosting post mortums and adding these failures into my perosnal 'library' of architectural decisions.

Another strategy that can apply to my own personal project is to document and fullfil my 'unknowns' as I'm working on design - both game design and system design.  This way, I can make a running list of "tickets" to work on and research as I build out my *Arena Simulator*.

## Chapter 2 

### Biggest Idea
---
This chapter dealt with a lot about the definition of an architect, and the skillset to be a proper one.  The main topics that were covered were the definition between an architect and a developer - and their knowledge depth vs. breadth, the necessity to know and define trade-offs in software development (in which there are _always_), and the balance of architecture and hands-on coding/POCs.

The thing that struck me the most was the necessity to define the trade-offs for architecture and technology choices.  The thing that I tend to have issues with - even going from my current role to a Solutions Engineer - is the ability to better define these trade-offs and to define the possible options.  My day-to-day, I tend to do quick research and go with my gut vs. the deeper analysis that is needed for architecture.

### Questions
* In the world of GenAI, how does one maintain their coding prowess?  Even with POCs, you can generate them on the fly.
* How can I better define myself with technology trade-offs vs. going with the 'gut' for the best solution?

### Things I Disagree With
None - I was pretty agreeable with this chapter, and it provided a number of useful insights and ideas for myself.

### How does this apply to Arena Simulator?
After defining the solid requirements and necessities for the system/game I want to make (including online multiplayer), I can take these ideas and options and lay them out to better architect the system.  Not only will this help me with what tools and frameworks I can work with, but it will also provide a checkpoint to make sure I'm building the correct things and making the proper technology choices I want to.

### Follow-up Research
N/A

## Chapter 3

### Biggest Idea
---
This chapter dealt a lot with coupling and cohesion - surprisingly a lot more technical and detail oriented than I had expected for an architecture learning.  These topics were discussion points and problem solving during my undergrad times, and having a better refresher on them was helpful.

Taking this into account into my professional work, I can see a benefit of keeping the balance of cohesion and coupling within my work important.  One thing I always strive for is to have clean code that is straightforward to understand (high cohesion).  With the idea of coupling definitely grows into the concept of not only at a detailed coding level, but also at an architectural/modular level.

### Questions
* We've learned that coupling can apply at the lower code and module levels, but what strategies can we go with in terms of higher level systems.  Can we better analyze the trade offs of systems depending on the level of coupling there are between modules.
* Are there any automated tools for calculating cohesion/coupling metrics that are also free?

### Things I Disagree With
N/A

### How does this apply to Arena Simulator?
I feel this is part of a design experiment that should be done as I lay out the groundwork for the coding/implementation of this game I want to make.  By keeping things properly contained with a cohesive implementation, I can easily add in new and scaled out systems to the game itself - not only gameplay systems, but also metric/logging/telemetry features as well.

### Follow-up Research
N/A