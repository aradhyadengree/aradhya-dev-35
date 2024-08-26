````
```Dockerfile
FROM ubuntu
RUN apt install nginx
WORKDIR /app
CMD ["nginx", "-g", ""daemon off]
```
