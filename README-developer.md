### Generating APP

1. Install the Angular CLI globally:
```
npm install -g @angular/cli
```

2. Create a new project:
```
ng new app
```

3. Go to a dist source folder 
```
cd app
```

4. Generate dist folder :

```
ng build --base-href=/app/ --output-path=../dist
```