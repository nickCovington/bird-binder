app fetches its data from a HTTP req
(remember we deleted local array & added 'db.json')

because of this, we need 2 things to run app:

1. start json-server
2. serve angular app

# data server:
```
npm install -g json-server
json-server --watch db.json
```

# run app:
```
ng serve
```
