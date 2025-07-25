# Go-URL-Shortener (First Iteration)

Go URL shortener application w/ rate limiter and ability to provide custom URL 

## Installing

* You must have [Go v1.21](https://go.dev/doc/install) (or higher) installed on your system
* You must have [Redis](https://redis.io/docs/getting-started/installation/install-redis-from-source/) installed on your system
* You must have [Docker](https://www.docker.com/) installed on your system 

## Executing program

* Clone this repository to the location of your choosing
* Provide necessary information to *.env* file
* Open your terminal
* Navigate to the saved location using ```cd folderName``` command, where *folderName* is the name of your path folder
* When in right location run:
```
docker-compose up -d
```
## Usage

* To shorten specified URL, send *POST* request to *DOMAIN/api/v1/* with the link provided in JSON format in the body, i.e:
> ```
> {"url": "https://github.com/lackingworth"}
> ```

## Version History

* v.0.0.1:

    * Initial Release

Tested w/ Postman
