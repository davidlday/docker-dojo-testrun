# Lab 6

```bash
git clone https://github.com/javaplus/DockerDojo.git
cd DockerDojo
docker build -t python-demo:1 .
docker run --rm -it -p 8080:5000 python-demo:1
```

Notes:

- On my machine, 5000 was in use. Swapped to 8080.
