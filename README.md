## Backend Coding Challenge

You can find [here](CHALLENGE.md) the instructions of the challenge. It is basically a REST API that simulates a social network. 

### Summary

As I did not have too much time to develop the coding challenge, I tried to focus on the code and the use cases (structure, tests, etc) following DDD. 
I made some assumptions that were not in the instructions and there are some things that I would like to improve if I had more time. 

If you have any doubt don't hesitate to contact me.

### Assumptions

- User needs to be authenticated to perform actions.
- Password does not need encoding.


### Post work 

- Document the API with swagger
- Configure logger and add logs
- Deploy it on heroku using travis as CI/CD tool (I usually do this, you can check my other repos in github)


## Build & Run

If you want to build and run the system you just have to execute:

`./gradlew bootRun`

## Tests

If you want to run a test suite execute the following sentence while server is running:

`bash -c scripts/legacy-test`