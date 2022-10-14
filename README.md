### Dockerizing an application

1. Use a local Docker or a online service like:
```
https://labs.play-with-docker.com/
```

2. Create a new project or downloading a existing project:
```
git clone https://github.com/williansmartins/dockerizing-application.git
```

3. Set a Docker file
```
FROM nginx:1.17.1-alpine
COPY ./dist/* /usr/share/nginx/html/app
```

4. Build an image
```
docker build -t my-app-image .
```

5. Run a instance of image
```
docker run --name my-app-container -d -p 8085:80 my-app-image
```