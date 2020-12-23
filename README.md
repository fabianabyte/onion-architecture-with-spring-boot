## This is an example how to apply Onion Architecture accompanying the blog post "Onion Architecture with Spring Boot"

### Intro
This SpringBoot maven project is part of my [blog post](https://blog.mimacom.com/onion-architecture-spring-boot/) where you could find not only explanation for it, but also theoretical background for:
- What is the history of Hexagonal-like Architectures
- Implementation tips helping to apply the Onion Architecture with Spring Boot

### Prerequisites:
- JDK11+

### Few words about the illustrated example

How to test the ShoppingList's APIs?

After you start the project, navigate to: http://localhost:8081/swagger-ui/index.html#/shopping-list-controller and then from shopping-list-controller use the following API's:
- Create a new ShoppingList and copy the retrieved URL;
- Add item to the ShoppingList;
- Get the total price.

🔔 Note that the total price contains shipping costs of 10 credits (the shipping is free of charge if the shopping list has items for more than 100 credits).

Have fun and do not hesitate to contact me if you have any questions or suggestions!

### About me
My name is [Andrey Zahariev Stoev](https://www.linkedin.com/in/andistoev). 
I am working as Senior Software Architect in Switzerland.
I love software craftsmanship and systems thinking.
I am passionate about travel, languages and cultural diversity exploration.

