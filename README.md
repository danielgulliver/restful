# RESTful Web Service

This is a RESTful web service built using Spring Boot. It is an incredibly simple example application taken from the
article [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/). I'd recommend giving the tutorial
a go if you're at all interested in learning Spring Boot - it only takes 15 mins.

## API
Make a request to `/greeting` and you will get back a simple JSON object:
```json
{
  "id": 1,
  "content": "Hello World"
}
```

You can customise the greeting by specifying the `name` parameter. For example, if you make a request to `/greeting?name=Daniel`, you will get back something like the following:
```json
{
  "id": 2,
  "content": "Hello Daniel"
}
```

Notice how `id` is incremented each time you make request.