# install
```
$ docker-compose build
$ docker-compose run --rm node sh -c "npm i -g create-react-app && create-react-app go"
```

# npm install
```
$ docker-compose run --rm node npm install
```

# run
```
$ docker-compose run --rm --service-ports node npm start