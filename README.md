# DevOps999
Class assignment

Run with:

docker run -d -p 8080:8080 u1ih/hello

Steps:

1: Get Source
git clone https://github.com/u1i/docker-hello

2: Make changes
modify index.html in the app directory

3: Build Container
change into the directory: cd docker-hello

docker build . -t myhello

4: Run Container
docker run -d -p 8080:8080 myhello



