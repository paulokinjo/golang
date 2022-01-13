# Build

```
$ docker build -t paulokinjo/go-cloudnative:1.0 .
```

# Run

```
$ docker container run -p 9999:8888 -d --name hello paulokinjo/go-cloudnative:1.0
```