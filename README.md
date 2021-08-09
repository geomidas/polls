# polls
demo django app

To run locally in Docker:

1. Pull this repo
2. Build the container image
```
   cd littlepolls
   docker build -t geomidas/polls .
```
3. Run the container
```
   docker run -it --rm -p 8000:8000 --name polls geomidas/polls
```
4. Visit: http://localhost:8000/polls

