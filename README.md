
# Getting Started
 
### SPRINGAI
https://docs.spring.io/spring-ai/reference/index.html
 
### Langgraph
Home for graph at http://localhost:8080/index.html
 
### RAG
https://medium.com/@saphynogenov/spring-ai-simple-and-flexible-rag-with-advisor-strategies-b559bacd053b
https://vaadin.com/blog/advanced-rag-techniques-with-spring-ai
 
### EMBEDDINGS
https://medium.com/@TheCodemonkey/semantic-search-with-embeddings-in-spring-kotlin-83e2c2f3406f
 
### Reference Documentation
For further reference, please consider the following sections:
 
* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/3.5.3/maven-plugin)
* [Create an OCI image](https://docs.spring.io/spring-boot/3.5.3/maven-plugin/build-image.html)
* [Spring Web](https://docs.spring.io/spring-boot/3.5.3/reference/web/servlet.html)
* [OpenAI](https://docs.spring.io/spring-ai/reference/api/chat/openai-chat.html)
* [Spring Data MongoDB](https://docs.spring.io/spring-boot/3.5.3/reference/data/nosql.html#data.nosql.mongodb)
 
### Guides
The following guides illustrate how to use some features concretely:
 
* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [Accessing Data with MongoDB](https://spring.io/guides/gs/accessing-data-mongodb/)
 
### Maven Parent overrides
 
Due to Maven's design, elements are inherited from the parent POM to the project POM.
While most of the inheritance is fine, it also inherits unwanted elements like `<license>` and `<developers>` from the parent.
To prevent this, the project POM contains empty overrides for these elements.
If you manually switch to a different parent and actually want the inheritance, you need to remove those overrides.

