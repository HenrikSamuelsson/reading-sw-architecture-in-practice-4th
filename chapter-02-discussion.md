# Chapter 2 - Discussion Questions Answers

Answers to discussion questions from chapter 2 in the book Software Architecture in Practice, Fourth Edition.

## Question 1

If you remember nothing else from this book, remember that:

> A system’s ability to meet its desired (or required) quality attributes is substantially determined by its architecture.

## Question 2

There a 13 reasons listed in chapter 2 why software architecture is important, an attempt is made in this discussion question to poke a hole in each reason.

> An architecture can either inhibit or enable a system’s driving quality attributes.

Software architecture can in deed inhibit quality attributes. Say that layers and interfaces between the layers are introduced to improve modifiability but there is never a second version of the software made. Then this software architecture decision will only mean extra development work and a performance hit to the system.

> The decisions made in an architecture allow you to reason about and manage change as the system evolves.

Test driven development (TDD) can be argued to solve this problem naturally without any need a lot of initial time to design an architecture and instead start implementation earlier. Employing TDD will produce a large set of tests that can be re-run after the changing the software while having control of that nothing brakes by the changes.

> The analysis of an architecture enables early prediction of a system's qualities.

Early prediction of a system's qualities can also be found quickly by building a prototype and having a prototype also have many other advantages, can for example be shown to stakeholder's to show progress.

> A documented architecture enhances communication among stakeholders.

It is true that an architecture can enhance the communication among the stakeholders but the format used to document software architecture, such as for example UML might not be really understandable by all stakeholders. Mockups, prototypes or questionnaires can be more successful to bolster communication.

> The architecture is a carrier of the earliest, and hence most-fundamental, hardest-to-change design decisions.

> An architecture defines a set of constraints on subsequent implementation.

> The architecture dictates the structure of an organization, or vice versa.

> An architecture can provide the basis for incremental development.

> An architecture is the key artifact that allows the architect and the project manager to reason about cost and schedule.

> An architecture can be created as a transferable, reusable model that forms the heart of a product line.

> Architecture-based development focuses attention on the assembly of components, rather than simply on their creation.

> By restricting design alternatives, architecture channels the creativity of developers, reducing design and system complexity.

> An architecture can be the foundation for training of a new team member.
