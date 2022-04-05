# Hak5-CloudC2-Docker
A Docker container for Hak5's Cloud C2.

## Built On
* Ubuntu 18.04.3

## Setup

#### Step 1:
Clone this repository on a server with Docker.

#### Step 2:
Edit the start.sh file and change CLOUDC2_HOSTNAME to your Cloud C2 DNS

#### Step 3:
Build the container:
```
docker-compose build
```
#### Step 4:
Run the container and complete setup:
```
docker-compose up -d
```
#### Step 5:
Once setup is complete, stop the docker container from another terminal window, and restart it.
```
docker-compose down
docker-compose up -d
```
