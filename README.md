# dsci522-dockerfile-practice
Practice with Docker for Individual Assignment 2

Build the image:

```bash
docker build --platform=linux/amd64 --tag assignment_2_image .
```

Test the image:

```bash
docker run --rm -p 8889:8888 assignment_2_image
```