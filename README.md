# Easy React Dev Environment

- This is a Docker-based local dev environment boilerplate with a barebone React application ready for quick setup.

- This React-only app is for educational/R&D purposes.

- React recommends using a framework (NextJS) for real-life, production-ready React applications.

## How to use

### `$ git clone git@github.com:ivallogenes/react-dev-env.git`

### Create the app folder where the React app will live

### `$ mkdir app`

### Run the below command once:

### `$ docker-compose up -d --build`

### To spin up your node container thereafter run:

### `$ docker-compose run --rm cli`

### `$ npm install` OR `npx create-react-app`

### `$ npm start`

### Access your app from a browser, use your VM IP address:

**http://127.0.0.1:3000/**

### To upgrade React version:

### `$ npm install react-scripts@latest`

>
----
- You can specify node version in the Dockerfile before building.

- ./app folder is used for the React application root directory.
- The ./app folder is in .gitignore

- Use Git outside the node container aka from your main cli prompt.
----

## Pre-requisites

- SSH / Bash command-line interface
- Docker Engine installed on Linux / Ubuntu OS

I prefer VirtualBox VM with Ubuntu Server OS installed, Docker and everything installed in it, then using Putty for ssh and shared network folder for file access with VScode. Over using Docker Desktop with mutagen and Windows Sub-system 4 Linux.

Make sure you give your virtual machine enough hardware resources:

- Disk space: 100G and above.
- RAM: 8G and above.
- Processors: the more the better.
