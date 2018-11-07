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

### Facebook Services

<div class="left">
<ul>
    <li>Slow performance due overfetching</li>
    <li>Fixed json models</li>
    <li>Graph of objects is needed</li>
</ul>
</div>
<div class="right">
![architecture](facebook_services.png)
</div>




+++
@title[GraphQL API]

### Solution
![architecture_new](facebook_services_new.png)

* Single API Endpoint
* Query a graph, select properties

---
@title[How does it work]

### Concepts

* Query
* Mutation

+++
@title[Query]

### Query

Simple hero query
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
        },
        {
          "name": "Han Solo"
        },
        {
          "name": "Leia Organa"
        }
      ]
    }
  }
}
```
@snapend

---

# Thanks - QA?
