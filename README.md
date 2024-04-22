## Starter for Nest.js & MongoDB /w mongoose ##

 Includes: 
- pre-built users schema created with `mongoose`
  - you can modify it as you need
- users DTO (create & update)
- user ID validation MW (can be deleted if no need to validate ID's)
- hash user passwords with `bcrypt`
- auth control with `jwt`, `passport` and Nest.js [Guards](https://docs.nestjs.com/guards):
  - Jwt strategies
  - Guards with auth and roles
