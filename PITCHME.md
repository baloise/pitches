---
@title[GraphQL]

# GraphQL

![Logo](graphql.png)

---
@title[Overview]
### Overview
* Why GraphQL
* How does it work
* API-Design concepts
* How to start
* DEMO

---
@title[Why GraphQL]

### Facebook 2012
![facebook](facebook_loading.jpg)



+++
@title[Facebook Services]

@snap[north]
<h4>Facebook Services 2012</h4>
@snapend

![](rest_architecture.png)

@snap[south-west]
@ul
- Graph of objects
- Multiple endpoints
@ulend
@snapend

@snap[south-east]
@ul
- Overfetching
- Fixed json models
@ulend
@snapend


+++

@title[GraphQL]
@snap[north]
<h4>Solution</h4>
@snapend

@snap[west sidebar]
![ARCH](graphQl_architecture.png)
@snapend

@snap[east sidebar]
@ul(false)
- Single API endpoint
- GraphQL as Query-Language
- Query a graph of objects
- Select fields
@ulend
@snapend

---
@title[How does it work]

### Concepts

* Type
* Query
* Mutation

+++
@title[Query]
### Type
+++
@title[Query]

@title[GraphQL]
@snap[north]
<h4>It all starts with a Type Definition</h4>
@snapend


@snap[west sidebar]
![ARCH](type.png)
@snapend

@snap[east]
@ul(false)
- Droid: GraphQL Object Type
- id, name, appearsIn and friends: fields on Droid
- !: non nullable type
@ulend
@snapend
+++
@title[Query]
### Query
+++
@title[Query]

Query Definition

```
{
  type Query {
    hero(episode: Episode): Character
    droid(id: Int!): Droid
  }
}
```
+++
@title[Query]

Simple droid query


```
{
  droid(id: 3) {
    name
    # Queries can have comments!
    friends {
      name
    }
  }
}
```
```
{
  "data": {
    "droid": {
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

+++
@title[Alias]
### Alias

```
{
  empireHero: hero(episode: EMPIRE) {
    name
  }
  jediHero: hero(episode: JEDI){
    name
  }
  other: hero(episode: OTHER){
     name
  }
}
```
+++
@title[Mutation]
### Mutation

+++
@title[MutQuery]

Mutation Definition

```
type Mutation {
  createReviewForEpisode(commentary: String!, stars: Int!, episodeId: Int!): Review
}
```
+++
@title[MutQuery]

Simple mutation


```
mutation {
  createReviewForEpisode(commentary: "This is a great movie!", stars: 5, episodeId: 5) {
    stars
    commentary
  }
}
```
```
{
  "data": {
    "createReviewForEpisode": {
      "stars": 5,
      "commentary": "This is a great movie!"
    }
  }
}
```
+++
@title[How does it work]

### Mutation

* CUD operations
* Multiple Mutations in one operation possible
* Query your desired return values

---
@title[Best practices]

### API-Design Concepts

* Think in graphs
* Shared language

+++
@title[Implementation]

### Think in Graphs

* With GraphQL, you model your business domain as a graph
* Query your business objects
* Which relation does my client need?
* It is not the same as database relation

+++
@title[Implementation]

### Rest Thinking

![rest](rest_endpoint.png)

+++
@title[Implementation]

### GraphQL Thinking

![graphql](graphql_endpoint.png)

+++
@title[Implementation]

### Shared Language

* Refer to DDD use ubiquitous Language
* To build a good schema you need clear business descriptions
* Shared understanding and consensus of business in team

---
@title[Java implementation]

### How to start

* Design your schema
* Choose your programming language

+++
@title[Java implementation]

### Design your schema

+++
@title[Java implementation]

### Schema type definition

```
type Partner{
  id: Int
  name: String
  firstName: String
  gebDate: LocalDate
  sex: Int
}
```
+++
@title[Java implementation]

### Query + Mutation + schema

```
type Query {
  getPartner(id: Int):Partner
}
type Mutation {
  createPartner(id: Int!, name: String!, firstName: String!): Partner
  deletePartner(id: Int!): Partner
}
schema {
  query: Query
  mutation: Mutation
}
```
+++
@title[Implementation]

### Schema

* Language independent
* Service definition similar to wsdl
* Supports schema validation of request

+++
@title[Java implementation]

### Supported programming languages

![rest](languages.png)

---
@title[DEMO]

### “Talk is cheap. Show me the code.”
Linus Torvalds

---

# Thanks - QA?

---

### Sources
* [Graphql Github](https://graphql.github.io/)
* [4-Years of GraphQL](https://www.graphql.com/articles/4-years-of-graphql-lee-byron)
* [GraphQL under the hood](https://about.sourcegraph.com/graphql/graphql-under-the-hood)
* [Eric-Baer-GraphQL under the hood](https://www.youtube.com/watch?v=fo6X91t3O2I)
* [graphql-java](https://github.com/graphql-java/graphql-java)
* [data-loader](https://medium.com/@gajus/using-dataloader-to-batch-requests-c345f4b23433)


