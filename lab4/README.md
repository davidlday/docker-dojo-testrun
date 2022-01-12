# Lab 4

```bash
docker run --rm --env mymessage=Containerize\ all\ the\ things! \
  -p 8080:8080 javaplus/cloud-app-demo
```

or

```bash
export mymessage=Containerize\ all\ the\ things\ again!
docker run --rm --env mymessage \
  -p 8080:8080 javaplus/cloud-app-demo
```
