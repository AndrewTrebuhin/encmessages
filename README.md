encmessages
===
Encrypt your message.
[See demo on Heroku.](https://encmessages.herokuapp.com/)

## Installation and launch
1. Clone the repo
```
git clone git@github.com:AndrewTrebuhin/encmessages.git
cd encmessages
```
2. Install all dependencies
```
bundle install
```
3. Rename base.db.example to base.db in db folder
```
cd db
mv base.db.example base.db
```
4. Return to root folder and run the app
```
cd ..
rackup
```
5.Visit http://localhost:9292 to see the app.
