# iban-validator
This is an iban validator lumen app authored by [Ehtisham Arshad](https://github.com/EhtishamArshad)


## Start environment
To start docker environment, you must install [Docker](https://www.docker.com/get-started) and digit this command in your favorite terminal:
```sh
make docker-start
```
When the process finishes, you can navigate to http://localhost:9001 to see your app works!

The api endpoint's basic structure is 
```
http://localhost:9001/validateIban/{iban}
```

## Stop environment
To stop your environment you must enter this command in your terminal:
```sh
make docker-stop
```