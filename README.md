### Setup/ install
* make sure the docker daemon is running, ie, start docker desktop
* `yarn`
* `docker run -it -v $PWD:/e2e -w /e2e cypress/included:9.6.1 --browser firefox`