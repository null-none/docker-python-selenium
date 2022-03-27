# docker-python-selenium
A docker image for selenium in python. 

Including python3, selenium, selenium-requests, xvfb, xvfbwrapper, firefox, geckodriver, and requests.

Based on alpine.


## Clear
```bash
docker system prune -a
docker volume prune
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
docker rmi $(docker images -a -q)
```

## Usage
```bash
docker-compose up
```
