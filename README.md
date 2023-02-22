[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-f4981d0f882b2a3f0472912d15f9806d57e124e0fc890972558857b51b24a6f9.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=10230905)
# CSSE6400 Week 1 Practical

Construction of a simple HTTP server in Python.

Please see the [instructions](https://csse6400.uqcloud.net/practicals/week01.pdf) for more details.

To run this server run the following:
pipenv run flask --app todo run

This requires the local pipenv to have flask installed

To test the API endpoints the file endpoints.http can be run using REST Client in VSCode or alternatively using another HTTP client tester like PostMan

The APIs created are the following:

| Request Type | Endpoints | Action |

| GET | api/health | to check that the server is running normally

| GET | api/todos | get all the todos

| GET | api/todos/<int:id> | to get a particular todo by id

| POST | api/todos | to post a todo

| PUT | api/todos/<int:id> | to update a particular todo by id

| DELETE | api/todos/<int:id> | to delete a particular todo by id


