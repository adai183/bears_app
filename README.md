# Bears App

Simple web app that classifies images with bears.

## Getting Started

Clone the repo
```
git clone https://github.com/adai183/bears_app.git
cd bears_app
```

Build docker image
```
docker build -t bears_app .
```

Run your new docker build locally
```
docker run -d --name bears_app --publish 80:8008 bears_app:latest
```

Go to [http://localhost/](http://localhost/) to see the client interface

