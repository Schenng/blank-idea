# Introduction #

This repo serves as my general purpose "Oh this is a great idea, we should build it" starter. 
You never know what the next idea will be, but you may as well be ready for it. The stack choice is purely based on my experience and may not be the best choice depending on the idea.

## Web 🏠

#### create-react-app-2 (w/ typescript)
Packages:
  - axios (promise based HTTP client)
  - redux (application level state)
  - react-router (routing)
  - http-proxy-middleware (allows custom url proxies)
  - typescript (javascript that scales)
  - ESLint (force code cleanliness)
  - palantir redoodle (typed actions which flow to reducers)

## Mobile 🏡

#### create-react-native-app
React Native stock is pretty good as is.
Packages:
  - axios
  - redux
  - react-navigator

## Backend 👷

#### Dropwizard (Java)
  - Dropwizard is a Java framework for developing ops-friendly, high-performance, RESTful web services.
    Dropwizard pulls together stable, mature libraries from the Java ecosystem into a simple, light-weight package that lets       you focus on getting things done.
#### Express (NodeJS)
  - Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and      mobile applications.

##  Infrastructure/Deployment 🏗️

#### Google Cloud
  - It's expensive but... it's got some great tools, and its kubernetes support is top notch
#### Kubernetes
  - Kubernetes (K8s) is an open-source system for automating deployment, scaling, and management of containerized applications.
#### CircleCI
  - CircleCI will handle tests, building the images via Docker, deploying to staging (on merge), and deploying to production (on release)
#### NGINX (web server)
  - NGINX is a free, open-source, high-performance HTTP server and reverse proxy, as well as an IMAP/POP3 proxy server. 
#### Node/Java (application server)
  - Depending on the backend chosen, use the default CircleCI provided images. Node:8 or OpenJDK


