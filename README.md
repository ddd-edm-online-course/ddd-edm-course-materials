# ddd-edm-course-materials
Course Materials for Domain-Driven Design and Event-Driven Microservices Online Course

This class will be offered via [O'Reilly's Live Online Training Platform](https://www.safaribooksonline.com/live-training/) on a semi-monthly basis. Watch the link for scheduled offerings!

## Syllabus

New architectural paradigms like microservices and evolutionary architecture, as well as the challenges associated with managing data and transactional contexts in distributed systems, have generated a renewed interest in disciplined software design and modular decomposition strategies. We know that the secret to obtaining the benefits of these architectures is getting the boundaries right, both at the team and the component/service level, and then keeping them right as the software continues to evolve! A key reason for getting the boundaries right is that it allows us to create a unified and ubiquitous language within the bounded contexts those boundaries enclose, allowing the business and engineers to have productive and coherent conversations. Fortunately, there is a mature, battle-tested approach to domain modeling and system decomposition that is a perfect compliment to these architectures: Domain-Driven Design (DDD). In this course, we’ll leverage an exemplar business domain, that of a pizza delivery store, to illustrate DDD-based decomposition strategies, data architecture patterns, and implementations.

### Prerequisites:

* Basic familiarity with Domain-Driven Design concepts can ease your understanding of the course material. I recommend reading Domain-Driven Design Distilled by Vaughn Vernon to get a quick, 101-level overview.
* We will leverage multiple technical architecture concepts in this course. Vaughn Vernon provides a great overview of them in Chapter 4 of Implementing Domain-Driven Design.
* Understanding Test-Driven Development is key to programming exercises we’ll complete. Test-Driven Development: By Example is a classic treatment of these concepts. You may also find Growing Object-Oriented Software, Guided by Tests a nice contextual treatment of TDD, mock objects, and object-oriented design.
* We will use the Java programming language, as well as testing libraries such as JUnit, Mockito, and AssertJ. You should be comfortable with Java programming and automated testing libraries. 
* Familiarity with Git and GitHub will be required. If you need to brush up your Git(Hub) skills, this Complete Git and GitHub Masterclass can be helpful.

### Setup Instructions:

**TODO**

### Schedule:

#### Day One:

**Class Introduction** (10 minutes)
* Intro to the Course
* Intro to the Instructor
* Class Logistics
* Class Outline

**Lecture:** Why do we need DDD? (15 minutes)

**Lecture:** What is Ubiquitous Language and why is it so important? (15 minutes)

**Open Q&A and Class Discussion:** Why DDD / Ubiquitous Language (10 minutes)

**Break** (10 minutes)

**Lecture:** DDD 101 - Strategic Design: Bounded Contexts, Context Mapping, Subdomains (25 minutes)

**Open Q&A and Class Discussion:** Strategic Design (10 minutes)

**Lecture:** DDD 101 - Tactical Design: Aggregates, Entities, Value Objects, Domain Events, Application Services, Domain Services (25 minutes)

**Open Q&A and Class Discussion:** Tactical Design (10 minutes)

**Lecture:** Overview of Event Storming (15 minutes)

**Break** (10 minutes)

**Interactive Screen Share:** Introduction to the Pizza Shop domain (10 minutes)

**Open Q&A and Class Discussion:** Event Storming and Pizza Shop Domain (10 minutes)

**Student Activity:** Pizza Shop Event Storming exercise (20 minutes)

**Interactive Screen Share:** Pizza Shop Event Storming solution (15 minutes)

**Lecture:** Discuss how Event Storm concepts translate into DDD concepts, User Stories, and TDD code (20 minutes)

**Open Q&A and Class Discussion:** Day One AMA (10 minutes)

#### Day Two:

**Day One Recap** (10 minutes)

**Lecture:** DDD and Technical Architectures (25 minutes)

**Break** (10 minutes)

**Interactive Screen Share:** Overview of the Pizza Shop Coding Exercise Environment (10 minutes)

**Student Activity:** Lab 1: TDD Aggregate Root - Create Kitchen Commands with Business Logic and Invariants (20 minutes)

**Interactive Screen Share:** Lab 1 Solution (5 minutes)

**Student Activity: Lab 2:** TDD Aggregate Root - Create and Publish Kitchen Domain Events (20 minutes)

**Interactive Screen Share:** Lab 2 Solution (5 minutes)

**Student Activity: Lab 3:** TDD Aggregate Repository - Create Kitchen Repositories and Add Domain Events (20 minutes)

**Interactive Screen Share:** Lab 3 Solution (5 minutes)

**Student Activity: Lab 4:** TDD Aggregate Repository - Rehydrate Kitchen Aggregates by Reference (20 minutes)

**Interactive Screen Share:** Lab 4 Solution (5 minutes)

**Student Activity: Lab 5:** TDD Application Service - Expose Kitchen Business Interface and Implement Transactions (20 minutes)

**Interactive Screen Share:** Lab 5 Solution (5 minutes)

**Student Activity: Lab 6:** TDD Policy - Subscribe to a Kitchen Domain Event from within an Aggregate and Create CQRS View (20 minutes)

**Interactive Screen Share:** Lab 6 Solution (5 minutes)

**Student Activity: Lab 7:** TDD Policy - Subscribe to a Kitchen Domain Event from an Adjacent Aggregate and Update State (20 minutes)

**Interactive Screen Share:** Lab 7 Solution (5 minutes)

**Open Q&A and Class Discussion:** Day Two AMA (10 minutes)



