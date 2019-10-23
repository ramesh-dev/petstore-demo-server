
# Petstore Demo Server 

Sample demo server for petstore open api definition, check out the medium article,

https://medium.com/swlh/end-to-end-restful-api-development-using-openapi-specification-c73d45e98c8d

## Overview
This code was generated by the [OpenAPI Generator](https://openapi-generator.tech) project.
By using the [OpenAPI-Spec](https://openapis.org), you can easily generate an API stub.
This is an example of building API stub interfaces in Java using the Spring framework.

The stubs generated can be used in your existing Spring-MVC or Spring-Boot application to create controller endpoints
by adding ```@Controller``` classes that implement the interface. Eg:
```java
@Controller
public class PetController implements PetApi {
// implement all PetApi methods
}
```

You can also use the interface to create [Spring-Cloud Feign clients](http://projects.spring.io/spring-cloud/spring-cloud.html#spring-cloud-feign-inheritance).Eg:
```java
@FeignClient(name="pet", url="http://petstore.swagger.io/v2")
public interface PetClient extends PetApi {

}
```
