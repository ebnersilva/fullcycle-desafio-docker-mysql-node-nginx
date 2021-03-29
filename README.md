<h3 align="center">
  Challenge Fullcycle
</h3>

<blockquote align="center">Image Docker with Nginx/Node/Mysql app</blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/ebnersilva/fullcycle-desafio-docker-mysql-node-nginx?color=%2304D361">

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">

  <a href="https://github.com/ebnersilva/fullcycle-desafio-docker-mysql-node-nginx/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/ebnersilva/fullcycle-desafio-docker-mysql-node-nginx?style=social">
  </a>
</p>

<p align="center">
  <a href="#rocket-about-the-app">About the challenge</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## :memo: How to use?

- **`git clone https://github.com/ebnersilva/fullcycle-desafio-docker-mysql-node-nginx`**
- **`cd cloned directory`**
- **`docker compose up -d`**
- **`😄 enjoy 😄`**

## :rocket: About the challenge

In this challenge you will put into practice what we have learned in relation to the use of nginx as a reverse proxy. The main idea is that when a user accesses nginx, he will make a call to our node.js application. This application in turn will add a record to our mysql database, registering a name in the people table.

The return of the node.js application to nginx should be:

<h1> Full Cycle Rocks! </h1>

- List of names registered in the database.

Manage the docker-compose in a way that just runs: docker-compose up -d that everything should be working and available on the port: 8080.

Upload everything into a repository and deliver.

## :memo: Technologies

- :memo: **`Docker`**
- :memo: **`Nginx`**
- :memo: **`Node.JS`**
- :memo: **`Mysql`**

### Features

- **`Proxy`**: On run this container, Nginx will be ahead of the application
- **`Insert`**: On run this container, The node js app will insert a data on database
- **`Select`**: On run this container, The nod js app will return all data that is on database

## :memo: License

This project use a MIT license. See the file [LICENSE](LICENSE.md) to more details.

---

Done with affection 💜 by Ebner Silva :wave: