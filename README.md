### Example Hello World App that can start in a Docker Container

To start the app execute the following command:

```console
./mvn clean package && docker build -t my-react-app . && docker run -d -p 8085:3000 my-react-app
```
```console
./mvn clean package
docker build -t my-react-app . 
docker run -d -p 8085:3000 my-react-app
```

Good luck ! 🤞🏽
