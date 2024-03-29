# Go API Starter SQL

Note: This is just a simple starter project I created while learning golang. A lot of improvement can be done. Please don't use it without reviewing the code first

## Tech Stack
* Go
* MySql

## Feature 
* Dockerized
* Database using [gorm](https://gorm.io/index.html)
* Migration
* Config using [dotenv](https://github.com/joho/godotenv)
* Validation using [validator](https://github.com/go-playground/validator)
* Route using [Mux](https://github.com/gorilla/mux)
* Auth using [JWT](https://github.com/golang-jwt/jwt)

### Installation
Make sure you have docker installed.

* Clone the repo

    ```bash
    git clone git@github.com:dev-parvej/go-api-starter-sql.git

* Copy env from env.example

    ```bash
    cp .env.example .env

* Run

    ```bash
  docker-compose up --build

You only have to include ```--build``` on the first run. 

You can also run the project without docker. For that you have to install the MySql and Go separately and then run 

```bash
go run main.go
