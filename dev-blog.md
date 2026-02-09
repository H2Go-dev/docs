# This md file will contain what I finished on each day to get feedback from my mentor and also to keep track of my progress.

# Day 1 (2026-02-03)
- completed database initial design
- did a rough estimation on how long the project will take based on the database design.

# Day 2 (2026-02-04)
- started working on the project.
- setup the environment:
  - Database setup using docker 
  - setup Spring Boot
  - created the basic structure of the project.
  - added dependencies for Spring Data JPA, Spring Web, and postgresql Connector, etc...
  - configured the actuators for monitoring the application.
  - added .env file to store environment variables, and configured spring to automatically load the variables from the .env file on  application startup.
  - setup opendoc for API documentation with swagger.

# Day 3 (2026-02-05)
- suffered with setting up the enitty mapper.
- created the initial User entity, repository, service, and controller.
- created the initial DTOs for User entity.
- created the mapping between User entity and User DTO using MapStruct.
- created the basic CRUD operations for User entity.
- added global exception handling for the application.
- tested the User CRUD operations using Postman.
- started dabbling with spring security

# Day 4 (2026-02-07)
- Suffered with setting up spring security.
- finished authentication

# Day 5 (2026-02-08)
- finally got spring security working with JWT authentication.
- created the authentication controller for login and registration.
- Made authorization work.

# Day 6 (2026-02-09)
- cleaned up authorization code.
- configured swagger to work with JWT authentication.
- completed the basic user management module.


