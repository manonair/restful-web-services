# RESTful Web Services

Social Media Application

Users -> Posts
1   ->  (n)

- Retrieve all Users    - GET /users
- Create a User         - POST /users
- Retrieve one User     - GET /users/{id}   -> /users/1
- Delete a User         - DELETE /users/{id}    -> /users/1 

- Retrieve all posts for a User     - GET /users/{id}/posts
- Create a post for a User          - POST /users/{id}/posts
- Retrieve details of a post        - GET /users/{id}/posts/{post_id}




1. Add a Services
2. Add the resource

 1. To validate a form we need to add 2 things
    - Add the @Valid anotation in the resource method
    - Add the validation types Size, Past in the User entity


## INTERNATIONALIZATION 
- LocalResolver
    - Default Locale - Locale.US
- ResourceBundleMessageSource

## USAGE
- Autowire MessageSource
- @RequestHeader(value = "Accept-Language", required = false) Locale locale
- messageSource.getMessage("helloWorld.message", null, locale)

Completed until #29