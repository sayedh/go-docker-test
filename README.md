# Simple Go project with Docker
In this project I used Docker with a simple Go project.

## Technologies Used
* Go
* Docker

## Dependencies

* Install Go - https://go.dev/doc/install
* Install Docker - https://docs.docker.com/get-docker

## Executing program
* Download the repository onto your computer and go to project file
```
git clone https://github.com/sayedh/go-docker-test
cd go-docker-test
```
* Run Docker build command
```
docker build -t docker-test .
```
* Run the project
```
docker run -p 8080:8081 -it docker-test
```
* Go to your browser and type http://localhost:8080/ 

![image](https://user-images.githubusercontent.com/30685241/176720253-ccfb07fe-a61d-4c55-b76f-39b82f95d4bd.png)

* Next go to http://localhost:8080/hi

![image](https://user-images.githubusercontent.com/30685241/176720347-7020f59b-0dcc-41dd-83a4-4b7471a835b1.png)
