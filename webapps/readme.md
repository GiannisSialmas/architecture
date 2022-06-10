# General for scalable systems
## Backend
- If you have multiple modules(groups of microservices with distinct functions) in your infrastructure, create a new microservice as single point of entry for your application. This entrypoint will handle things like validation, authentication, authorization, throttling, etc and will consume your other microservices as needed.
- Make your backend a rest api and keep it in it's own seperate domain.
- 


# 
