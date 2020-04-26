# API Design

[API design](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design) \#article - by Microsoft. “This guidance describes issues that you should consider when designing a web API.”

[API Design Guide](https://cloud.google.com/apis/design/) \#article - by Google. “This is a general design guide for networked APIs. It has been used inside Google since 2014 and is the guide that Google follows when designing Cloud APIs and other Google APIs. This design guide is shared here to inform outside developers and to make it easier for us all to work together.”

[How to Design Great APIs - Parse Developer Day 2013](https://www.bing.com/videos/search?q=api+design&&view=detail&mid=A5A89E9C41A22383C32DA5A89E9C41A22383C32D&&FORM=VRDGAR) \#video

* Be intuitive
  * To be intuitive is to work just like other things the developer has seen before.
  * If two things inside the API work kind of the same, they should look the same. Be consistent.
  * Use parallel structure by using smaller design components to build up higher-level API patterns
  * Make dangerous or ugly operations look ugly. Makes it intuitive to the user that they probably shouldn’t be doing this.
* Be well-documented
  * All APIs need documentation.
  * One line of code in the docs can save people hours and hours of work.
  * Simple questions should be simple to answer.
  * What are the simple questions you want your docs to answer?
    * “What does X do?” 
      * Should be answered by your reference docs.
      * Reference docs should be boring and exhaustive.
    * “How do I do X?”
      * For people who are starting at 0.
      * Answered by tutorials and guides.
      * Should not be boring. Should be interesting.
      * Each should cover one topic and make sense to someone who isn’t familiar with your product.
    * “What can I do in two minutes?”
      * Answered by your quickstart.
      * It’s as simple as possible.
      * Should be usable by literally anyone.
      * “How can I do something of any value as absolutely fast as possible?”
* Be opinionated
  * Especially when it comes to eternal debates.
  * You have to take sides and run with it.
  * Create a philosophy for your API.
  * This becomes more difficult when multiple people are working on the same API.
  * The solution is to be very opinionated, and make your philosophy visible, spread it among both your users and those building the product.
  * Especially be opinionated when there is no right or wrong

[Insomnia](https://insomnia.rest/) - "Debug APIs like a human, not a robot. Finally, a REST client you'll love"

[Postman](https://www.getpostman.com/) \#software - “Postman Makes API Development Simple. Developers use Postman to build modern software for the API-first world.”

\_\_[_Web API Design_](https://pages.apigee.com/rs/apigee/images/api-design-ebook-2012-03.pdf) \#book - "This e-book is a collection of design practices that we have developed in collaboration with some of the leading API teams around the world, as they craft their API strategy through a design workshop that we provide at Apigee."

## GraphQL

[Apollo GraphQL](https://www.apollographql.com/docs/react/) - "Simplify app development by combining APIs, databases, and microservices into a single data graph that you can query with GraphQL"

[Graphene-Python](https://graphene-python.org/) - "Graphene-Python is a library for building GraphQL APIs in Python easily, its main goal is to provide a simple but extendable API for making developers' lives easier."

[GraphiQL](https://github.com/graphql/graphiql) - "GraphiQL is the reference implementation of this monorepo, GraphQL IDE, an official project under the GraphQL Foundation. The code uses the permissive MIT license."

[graphql-docs](https://github.com/mhallin/graphql-docs) - "Dynamically generated documentation explorer for [GraphQL](http://graphql.org/) schemas. It aims to provide a better overview of a schema than [GraphiQL](https://github.com/graphql/graphiql), but without querying features."

[Lessons from 4 Years of GraphQL](https://www.youtube.com/watch?v=zVNrqo9XGOs&list=WL&index=3&t=0s) \#video - "GraphQL has been in use at Facebook for over four years and evolved a lot before it was open sourced. During that time we learned a lot about what works and why, and derived a series of best practices. Hopefully our best practices and lessons learned are relevant not only to your use of GraphQL, but how you design and build all sorts of software."

[Thinking in Graphs](https://graphql.org/learn/thinking-in-graphs/) \#article - "Graphs are powerful tools for modeling many real-world phenomena because they resemble our natural mental models and verbal descriptions of the underlying process. With GraphQL, you model your business domain as a graph by defining a schema; within your schema, you define different types of nodes and how they connect/relate to one another. On the client, this creates a pattern similar to Object-Oriented Programming: types that reference other types. On the server, since GraphQL only defines the interface, you have the freedom to use it with any backend \(new or legacy!\)."

## OpenAPI

[Better API Design with OpenAPI \(Cloud Next '18\)](https://www.youtube.com/watch?v=uBs6dfUgxcI) \#video - "OpenAPI is a vendor neutral, portable, open specification for designing, describing, and deploying APIs. It enables you to describe APIs in a manner consumable by humans and apps. Learn why OpenAPI is useful throughout the API lifecycle, from brainstorming to consumption."

[OpenAPI](https://www.openapis.org/) - "The OpenAPI Specification: a broadly adopted industry standard for describing modern APIs." [GitHub](https://github.com/oai).

[Stoplight](https://stoplight.io/) - "The API Design Management Platform powering the world's leading API first companies."

[Swagger](https://swagger.io/) - "Simplify API development for users, teams, and enterprises with the Swagger open source and professional toolset. Find out how Swagger can help you design and document your APIs at scale."

