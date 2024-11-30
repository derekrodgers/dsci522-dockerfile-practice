# dsci522-dockerfile-practice
Practice with Docker for Individual Assignment 2

Build the image:

```bash
docker build --platform=linux/amd64 --tag derekrodgers/dsci522-dockerfile-practice .
```

Test the image:

```bash
docker run --rm -p 8889:8888 derekrodgers/dsci522-dockerfile-practice
```