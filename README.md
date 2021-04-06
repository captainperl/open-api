# swagger-ui Redux
> Original version by
> [schickling](https://github.com/schickling/dockerfiles/tree/master/swagger-ui)

Swagger UI [2.1.4](https://github.com/swagger-api/swagger-ui/releases/tag/v2.1.4) with API_URL and API_KEY injection (45 MB)

## Usage

```sh
$ docker run -d -p 80:8080 -e API_URL=http://localhost:4000/swagger inanimate/swagger-ui
```

### Variables

* `API_URL` - Swagger endpoint for your API
* `API_KEY` - Default API Key (optional)
