---
@title[GraphQL]

# GraphQL

![Logo](graphql.png)

---
@title[Overview]
### Overview
* Why GraphQL
* How does it work
* Java implementation

---
@title[Why GraphQL]

### Facebook 2012
![facebook](facebook_loading.jpg)



+++
@title[Facebook Services]

@snap[north]
<h4>Facebook Services</h4>
@snapend

@snap[west]

@ul
- Overfetching
- Fixed json models
- Graph of objects
@ulend

@snapend

@snap[east]
![](facebook_services.png)
@snapend


+++

@title[GraphQL]
@snap[north]
<h4>Solution</h4>
@snapend

@snap[west]
@ul
- Single API Endpoint
- Query a graph
- Select properties
@ulend

@snapend

@snap[east]
![](facebook_services_new.png)
@snapend

---
@title[How does it work]

### Concepts

* Query
* Mutation

+++
@title[Query]

@snap[north-east]

Simple hero query
@snapend

@snap[west]
```
{
  hero {
    name
    # Queries can have comments!
    friends {
      name
    }
  }
}
```
@snapend
@snap[east]
```
{
  "data": {
    "hero": {
      "name": "R2-D2",
      "friends": [
        {
          "name": "Luke Skywalker"
        }
      ]
    }
  }
}
```
@snapend

---

# Thanks - QA?
