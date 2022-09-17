### Example of a flask app that connects to redis and is loadbalanced through nginx
```
docker-compose up --build --scale app=10
```

### Available urls:
- [http://0.0.0.0/](http://0.0.0.0/)
- [http://0.0.0.0/hit](http://0.0.0.0/hit)
- [http://0.0.0.0/reset](http://0.0.0.0/rest)
