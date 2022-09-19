# NestJS API Documentation

## Why use Swagger/OpenAPI when you have your REST defined in Insomnia/Postman?

<br>
The need for a more clear documentation starts to become appearent when the project has new members joining or the client wants some detailed explanations of why a new request was implemented and how the request will be applied with it's examples to show the impact on the application. 
<br><br>
If all you have is the requests on Insomnia for example, it's hard to show it to the client, since many times the requests may be integrated with responses from other requests to make testing easy for developers, but while it makes it easier for devs it certainly does not make it easier for the client to understand what is going on behind the requests. 
<br><br>
With OpenAPI you can have a clear and concise documentation well detailed on a easy to use webpage, with each request having it's description, examples for input and output, verification required and also a list of detailed objects on the bottom used on the requests.
<br><br>

## What are the documentation specs Swagger, OpenAPI 2.0, OpenAPI 3.0?

<br>
Albeit their names are different Swagger and OpenAPI are actually the same standard, when the company behind Swagger was bought, their new owners Smart Bears renamed the spec to OpenAPI. So that makes it Swagger to be actually OpenAPI 1.0 the first major release.
<br><br>
When the second major version was released it was titled OpenAPI 2.0 and more recently we have a new major version that is being widely adopted called OpenAPI 3.0 below we can see that OpenAPI 3.0 has a more generic abstraction for the specification with a better reusability and simplification of objects. OpenAPI 3.0 is what we are going to use for NestJS.
<br><br>

![OpenAPI Comparison](./openapi.jpg "OpenAPI Comparison 2.0 vs 3.0")
<br><br>

## How to use OpenAPI with NestJS?

<br>
NestJS actually has a dedicated module for generating an OpenAPI documentation.
