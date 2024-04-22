## Starter for Nest.js & MongoDB /w mongoose ##

 Includes: 
- pre-built users schema created with `mongoose`
  - you can modify it as you need
- users DTO (create & update)
- user ID validation MW (can be deleted if no need to validate ID's)
- hash user passwords with `bcrypt`
- auth control with `jwt`, `passport` and Nest.js [Guards](https://docs.nestjs.com/guards):
  - Jwt strategies
  - Guards endpoints with jwt and roles


To run this project:
```bash
git clone https://github.com/dkumza/nest_js_boilerplate
cd nest_js_boilerplate
# edit package.json as you need
# remove not needed includes from /src dir or code
yarn # or npm i to install modules
# open with your favorite IDE
yarn dev # or npm run dev
```
