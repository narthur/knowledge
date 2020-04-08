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

## GraphQL

[Apollo GraphQL](https://www.apollographql.com/docs/react/) - "**Apollo Client** is a complete state management library for JavaScript apps. Simply write a GraphQL query, and Apollo Client will take care of requesting and caching your data, as well as updating your UI."

[Graphene-Python](https://graphene-python.org/) - "Graphene-Python is a library for building GraphQL APIs in Python easily, its main goal is to provide a simple but extendable API for making developers' lives easier."

[GraphiQL](https://github.com/graphql/graphiql) - "GraphiQL is the reference implementation of this monorepo, GraphQL IDE, an official project under the GraphQL Foundation. The code uses the permissive MIT license."

[graphql-docs](https://github.com/mhallin/graphql-docs) - "Dynamically generated documentation explorer for [GraphQL](http://graphql.org/) schemas. It aims to provide a better overview of a schema than [GraphiQL](https://github.com/graphql/graphiql), but without querying features."

