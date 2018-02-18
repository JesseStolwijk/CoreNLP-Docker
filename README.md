# Dockerfile for Stanford CoreNLP server

[Official CoreNLP server documentation](https://stanfordnlp.github.io/CoreNLP/corenlp-server.html)

[Docker hub](https://hub.docker.com/r/jessestolwijk/corenlp/)

# Use pre-build docker image
`docker pull jessestolwijk/corenlp`

`docker run -p 9000:9000 jessestolwijk/corenlp`

# Build image from Dockerfile
`git clone git@github.com:JesseStolwijk/CoreNLP-Docker.git`

`cd CoreNLP-Docker`

`docker build ./`

`docker run -p 9000:9000 <image_name>`

