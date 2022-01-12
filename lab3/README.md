# Lab 3

```bash
docker run --rm -it -v $(pwd)/content:/root/lab3 busybox:latest
```

or

```bash
docker run --rm -it -v $(pwd)/content:/root/lab3 \
  busybox:latest \
  sh -c "sed 's/best/worst/' /root/lab3/lying.txt > /root/lab3/truth.txt"
```
