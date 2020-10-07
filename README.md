# Build the image

```
cd mysql
docker build -t mysql .
```

#Launch Container

```
cd ..
docker-compose up -d mysql
```


# After Launch the container if you want to login you must run the next command

```
docker exec -it mysql mysql -uroot -p
```
