# UnsafeRepo

## Testing

Use `npm run test` to perform a single run of all files with a test coverage report.

 

Use `npm run test:watch` to rerun tests on only files changed (by default) after every file save. To update snapshots, use this command and press `u`.

 

Environment variables from the `.env.test` are used when running tests. Adding a `.env.test.local` will allow overriding these variables.

 

### Environment Variables

Environments can be configured using the `.env.<ENV>`, where `<ENV>` is the environment. For example, `.env.development` targets running the application in development. Do not add any secret values to these files, such as API keys. The following is the intent of the environment targets:

 

environment | target

-|-

development | for running locally

production | for running in production

staging | for running in staging

test | for running tests locally

 

To configure overrides for a given environment, create a `.env.<ENV>.local` file, such as `.env.development.local`. This file will not be added to version control and can therefore contain secrets such as API keys.

 
#---------------------Testimonial Begin----------------------------------

This is an unsafe repo.
console.log("Hello World");

Ive never seen such bad code in my life.

#---------------------Testimonial End------------------------------------
