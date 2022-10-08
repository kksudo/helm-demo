# A helm-demo repository 

A helm-demo repository to show how to use GitHub actions with the common app development tasks

## What this repository does

GitHub actions:

1. Build a docker image
2. Push them to the dockerHub
3. Lint a Helm chart
4. Deploy a Helm chart to a Kubernetes cluster


## Deploy changes to your k8s cluster



## Run locally 

### Run a react app on  your local machine

1. Clone this repo.
2. CD into github-actions-heroku.
3. run `yarn/npm install`.
4. run `yarn start/npm run start`.

### Run a dockerized react app

1. `docker build -t react-demo:0.0.2 .`
2. `docker run -d --rm --name react -p 8080:80 react-demo:0.0.2`
3. open [http://localhost:8080](http://localhost:8080) in your browser. 
