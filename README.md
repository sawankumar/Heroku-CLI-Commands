<h1 align="center">Heroku CLI Commands 🔥</h1> 

<hr>

- Login into your heroku account with command:
```
heroku login
```
- Initilize repository:
```
git init
```
- Create a new heroku app:
```
heroku create appname	
```
- Select This App in your Heroku-cli: 
```
heroku git:remote -a appname
```
- Change Dyno Stack to a Docker Container:
```
heroku stack:set container
```
- Add Files to push:
```
git add .
```
- Commit new changes:
```
git commit -m "Initial Commit"
```
- Push Code to Heroku:
```
git push heroku main --force
```
- Restart Worker by these commands:
```
heroku ps:scale worker=0
```
```
heroku ps:scale worker=1	 	
```