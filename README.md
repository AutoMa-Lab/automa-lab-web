## To run the web locally
# Build the image first

```
docker build -t automa-lab-website .
```

# Run the container

```
docker run -p 8080:8080 -v $(pwd):/app automa-lab-website
```
