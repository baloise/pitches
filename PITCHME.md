---
@title[DDD]

## Domain-Driven-Design

![Logo](./img/blueBook.jpg)

---
@title[Overview]
### Overview
* Why DDD
* Key Concepts
* Event Storming
* DEMO

---
@title[Why DDD]

### Two worlds
![domainExpert](./img/dev_domainExperts.png)


+++
@title[Why DDD]

### Big Ball of Mud
![](./img/bbom_real.jpeg)

+++
@title[Why DDD]

### Big Ball of Mud in software
![](./img/bbom.png)

+++
@title[Why DDD]

### Whats the solution?
![](./img/boundedContexts.jpg)

---
@title[How does it work]


### Overview

![](./img/ddd_context.png)

+++
@title[BC]

### Strategic Design

* Ubiquitous Language
* Bounded Context
* Context Map


+++
@title[UL]
### Ubiquitous Language
+++
### One Language for all
![](./img/uq.png)

+++
@title[UL_Bullet]
### Ubiquitous Language

* One common language between developer and domain expert
* Use same terms for same concept
* Both need the same knowledge about the domain

+++
@title[BC]

### BoundedContext


+++
### BoundedContext

* A space where the ubiquitous language is valid
* Deals with large models by dividing them into different Bounded Contexts
* Define clear boundaries
+++
@title[cmap]
### Context Map

+++
@title[cmapdef]

![](./img/contextMap.png)

+++
@title[cmappoints]

### ContextMap

* Strategic Design big picture
* Define communication/relation between BoundedContexts
* Show dependencies between contexts
* Identify bottle-necks

+++

### Tactical Design

#### “The Tactical Design, is a set of technical resources used in the construction of your Domain Model, these resources must be applied to work in a single Bounded Context.”

---
### Event Storming

+++

---

@title[DEMO]

### “Talk is cheap. Show me the code.”
Linus Torvalds

---

# Thanks - QA?

---

### Sources
* [ddd-principles](https://www.amazon.de/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709/ref=sr_1_3?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=ddd&qid=1568885147&s=books-intl-de&sr=1-3)
* [ddd-evans](https://www.amazon.de/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215/ref=sr_1_2?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=2DBTY5TLDYZBC&keywords=tackling+complexity&qid=1568885072&s=books-intl-de&sprefix=tackling+compl%2Cenglish-books%2C166&sr=1-2)
* [ddd-distilled](https://www.amazon.de/Domain-Driven-Design-Distilled-Vaughn-Vernon/dp/0134434420)
* [bounded-contexts](https://martinfowler.com/bliki/BoundedContext.html)
* [context-mapping](https://stefan.kapferer.ch/2018/12/27/context-mapper-a-dsl-for-service-decomposition/)
* [tactical-design](https://thedomaindrivendesign.io/what-is-tactical-design/)

