# How to run in local 

- Install [docker](https://docs.docker.com/get-started/get-docker)
- Make sure docker deamon is running 
- Navigate to the project directory and run below steps

## Step 1: Build Image

`docker build -t whisper_api .`

## Step 2: Run Image

`docker run -p 8000:8000 whisper_api`

## Step 3: Open in browser

http://localhost:8000/
