### Dockerizing an application

Use a local Docker or a online service like:
```
https://labs.play-with-docker.com/
```

Create a new project or downloading a existing project:
```
git clone https://github.com/williansmartins/dockerizing-application.git
```

Go to a source folder 
```
cd dockerizing-application
```

Generate a distribution folder with static files

```
npm install -g @angular/cli
ng build --prod
```

Create workspace:

```
ng new [PROJECT NAME]
```

Run the application:

```
cd [PROJECT NAME]
ng serve
```