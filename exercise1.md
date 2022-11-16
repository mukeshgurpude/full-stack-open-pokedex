## Python CI/CD Tools

Python has a large ecosystem of community managed packages. For linting purpose, some might use `black`, or `pylint`.
Both of these tools are awesome for linting purpose. Similar to linting, there are libraries for testing purpose, two of which are
`Pytest` and `Unittest`.

## CI tools
Beside github actions and jenkins, we can use CircleCI, TravisCI for CI purpose. Also, github alternatives `Gitlab`, and `Bitbucket`
provides their own solutions for the CI named Gitlab CI and Bitbucket pipelines respectively.

While all of these tools are available to be used directly through their own server (cloud based solution), we can also self-host them
for our own purpose. For the public projects, or small projects, we can just use cloud based solutions, as they provide us flexibility,
and keeps the developer away from process of maintaining the servers.
For propertiery projects, it might be beneficial to self host the services, as to keep the source private. This will also allow us
to customize the working of respective tools as per the need.
