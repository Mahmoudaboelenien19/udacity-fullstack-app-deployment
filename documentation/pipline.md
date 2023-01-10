# PIPELINE Process

- we need to push the fullstack app to a github repo

- then connect repo to circleCI

- if we can change code locally and push it to that repo.

  -circleCI trigger and pipline will start.

1. install Node with required version
2. install aws cli
3. install AWS eb
4. install frontend dependencies
5. lint it to check it if there any errors in code.
6. build it to convert typescript to Javascript
7. install backend dependencies
8. lint it to check it if there any errors in code.
9. build it
10. hold till user approval
11. trigger changes on eb with new code
12. trigger changes on frontend with new code
13. now the app is successfully updated
