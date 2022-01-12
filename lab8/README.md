# Lab 8

```bash
docker run -it ubuntu bash
apt-get update
apt-get install -y cowsay
export PATH=/usr/games:$PATH
cowsay "Let's keep MOOOOOving"
exit
```

And then build the new image.

```bash
docker build -t cowsay:1 .
docker run cowsay:1
```
