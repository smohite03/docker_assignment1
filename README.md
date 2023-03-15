# Run app on locally by installing dependencies locally
### Clone the project locally
```
$ git clone https://github.com/smohite03/docker_assignment1.git
```
### Install dependencies localy
```
$ npm install
```
### Run the app
```
$ npm run start
```
### Checkout app on browser
```
http://localhost:8080
```

# Run app using docker 
### Pull the docker Image
```
$ docker pull shashwat0309/assignment1:1.0
```
### Check for docker image named shashwat0309/assignment1
```
$ docker images
```
### Run the app
```
$ docker run -p 8080:8080 <image_id>
```
### Checkout app on browser
```
http://localhost:8080
```
