# README

Steps Followed
Creating the Rails App
1. Downloaded Yarn, Ruby and then install rails
![downloaded rails](https://user-images.githubusercontent.com/72721433/173407485-c7aa3f49-a7fb-4be4-9e01-23d318df8bc3.jpg)
2. Add required gem files 
3. Ran "Bundle install"
4. Created student controller and model for app
5. Ran "rake db:migrate"
6. Edited the required view, contoller and routes related files
7. Ran "rails server" and tested

TASK 1 : To pack the rails app in a docker container image
1. Downloaded docker and all its required linx
2. Created a Dockerfile and gave it required commands
3. Created a Docker image for the app "docker build -t steelbuns/simpleform:1.0"
![creating docker image](https://user-images.githubusercontent.com/72721433/173410413-8bb331d3-01ba-4afa-a592-6b8d5d386ac5.jpg)
5. Created a Docker container with our wanted port number and ran it with the comand "docker run -p 8080:3000 1d3f1cf0d9ab"
![running container on dedicated port](https://user-images.githubusercontent.com/72721433/173410472-3fc76f1a-027d-4f2f-8627-bf5f80d745ad.jpg)
