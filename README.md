# 4 step are there

## step 1
### prepare:
	installing packages required

## step 2
### up:
	I) running docker-compose.yml and Dockerfile
	II) creating mysql connection with php and printing the client and server version

## step 3
### down:
	I) stoping all running containers
	II) storing all usefull files in ~/docker/*

## step 4
### teardown:
	I) deleting all file present in ~/docker/*

1) to begin with it just run make in this folder
2) run "localhost:3000" in your browser ( RUNNING SQL SERVER TAKES TIME )
3) you may check its status by "docker logs db -f" press CTRL+C to exit
4) after 2-3 mint delay, at "localhost:3000" will print client-server version 

5) for testing purpose step 1 and step 2 will run
6) you can add all step in "makefile" by this "all: up teardown"
