# go-mux-api
This is  a REST API server that will expose endpoints to allow accessing and manipulating ‘products’.It gives functionality of creating a new product,updating an existing product,deleting an existing product, fetching an existing product, and fetching a list of products. In this I have used Gorilla Mux for routing and postgreSQL for database. And, it is inspired by awesome go github repo.

#How to run locally?
- Start postgres
- Prepare environment, fill DB parameters:

``` bash
$ source env-sample
```

- Build and run:

```bash
$ export GO111MODULE=on
$ export GOFLAGS=-mod=vendor
$ go mod download
$ go build -o gomuxapi.bin
$ ./gomuxapi.bin
```
