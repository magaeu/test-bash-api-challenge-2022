# test-bash-api-challenge-2022

api tests using postman to solve test bash challenge

[![Newman Run](https://github.com/magaeu/test-bash-api-challenge-2022/actions/workflows/postman-tests.yml/badge.svg)](https://github.com/magaeu/test-bash-api-challenge-2022/actions/workflows/postman-tests.yml)

# Content

1. [Requirements](#requirements)
2. [Install postman](#install-postman)
3. [Install newman](#install-newman)
4. [Run postman collection](#run-postman-colletion)
5. [Run newman](#run-newman)

### Requirements

- Postman (7.4+)
- Newman (4.5+) - _optional_
- Node.js (10.0+) 

### Install Postman

- Download the [latest version](https://www.postman.com/downloads/)
- Follow the instructions on [Official website](https://learning.postman.com/docs/postman/launching-postman/installation-and-updates/)

### Install Newman

- Follow the instructions on [Official website](https://www.npmjs.com/package/newman)

### Run Postman Collection

- Setup your environment ([heroku](environment/heroku.postman_environment.json)

- Click on runner (Further instructions on [Official website](https://learning.postman.com/docs/postman/collection-runs/intro-to-collection-runs/))

### Run Newman

- Run newman command line with collection and enviroment (newman run <postman_collection.json> -e <environment.json>)

```shell
$ newman run booker.postman_collection.json -e environment/heroku.postman_environment.json
```
