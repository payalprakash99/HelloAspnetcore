# HelloAspnetcore
Containerizing an ASP.NET Core 3.0 Web API

# Building docker image
 docker build -t hello-aspnetcore:v1 .
 
# Running docker image
docker run -it --rm -p 8080:80  hello-aspnetcore:v1

# Stop docker image
press ctrl + c
