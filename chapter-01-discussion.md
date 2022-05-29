# Chapter 1 Discussion Questions Answers

Answers to discussion questions from chapter 1 in the book Software Architecture in Practice, Fourth Edition.

## Question 1

Definition of software architecture from the book:

> The software architecture of a system is the set of structures needed to reason about the system. These structures comprise software elements, relations among them, and properties of both.

There are other definitions of software architecture.

IEEE 1471:

> Architecture is the fundamental organization of a system embodied in its components, their relationships to each other, and to the environment, and the principles guiding its design and evolution.

Synopsys, what is software architecture:

> The software architecture of a system depicts the system’s organization or structure, and provides an explanation of how it behaves.

Hayes-Roth, 1994:

> ..an abstract system specification consisting primarily of functional components described in terms of their behaviors and interfaces and component-component interconnections.

Definitions of software architecture can include considerations like rationale for decisions or how the architecture will evolve over time. This can be considered to be not strictly necessary meta information. But there are benefits with adding this type of information, over time we tend to forget why a decision was taken, and keeping notes on what is left is useful if the work shall be handed over to someone new.

## Question 2

A software architecture is typically made up of a set of structures than enables reasoning, analysis, and making decisions about the system. There are three types of structures:

1) Module structures shows the system as a set of code or data units to be constructed or obtained by buying or using an open source solution. This structure enables planning of the work for what to be developed and what can be reused from previous projects. This structure will also aid in making time estimations more accurate since it is easier to make a correct time estimates of smaller parts a compared to the system as a whole.

2) Component-and-connector structures show the system as a set of elements that have runtime behavior (components) and interactions (connectors). This structure specifies how information (data) will be propagated in the system. This enables scheduling analysis and performance analysis. Identifies resource bottlenecks and possibilities for parallelism.

3) Allocation structures maps software elements to components and hardware, illustrates where things are stored and how the system is to be configured. This enables analysis related to deployment, test, and work assignment between different teams in larger multi-team projects.

So an software architecture documents a system enabling spreading understanding on how the system is to work from different perspectives. Shared understanding will in turn make it possible for the various stakeholders to perform analysis and provide feedback enabling decision making about the development and maintenance of the system.
