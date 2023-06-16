# onespace10/dockers - Introduction.

This git repository is for docker-compose script including react from Docker Hub Sample Project.

# Docker script list

| name                                                                                                 | description                                                            |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| [react-express-mongodb](https://github.com/onespace10/dockers/docker-compose/master/nginx)              | A sample React application with a Node.js backend and a Mongo database |
| [react-express-mysql](https://github.com/onespace10/dockers/docker-compose/master/nginx2)               | A sample React application with a Node.js backend and a MySQL database |
| [react-java-mysql](https://github.com/onespace10/dockers/docker-compose/master/centos7_user)            | A sample React application with a Spring backend and a MySQL database  |
| [react-nginx](https://github.com/onespace10/dockers/docker-compose/master/ubuntu_user)                  | A sample React application with Nginx                                  |
| [react-rust-postgres](https://github.com/onespace10/dockers/docker-compose/master/mysql)                | A sample React application with a Rust backend and a Postgres database |
| [slack-clone-docker-main](https://github.com/onespace10/dockers/docker-compose/master/pyspark-notebook) | A sample Slack Clone app built with the MERN stack                     |

# Docker file list

```
C:.
├─react-express-mongodb
│  ├─backend
│  │  ├─config
│  │  ├─db
│  │  ├─logs
│  │  ├─models
│  │  │  └─todos
│  │  ├─routes
│  │  └─utils
│  │      └─helpers
│  ├─data
│  │  ├─diagnostic.data
│  │  └─journal
│  └─frontend
│      ├─public
│      └─src
│          └─components
├─react-express-mysql
│  ├─.docker
│  ├─backend
│  │  ├─src
│  │  └─test
│  ├─db
│  └─frontend
│      ├─public
│      └─src
├─react-java-mysql
│  ├─backend
│  │  └─src
│  │      └─main
│  │          ├─java
│  │          │  └─com
│  │          │      └─company
│  │          │          └─project
│  │          │              ├─configuration
│  │          │              ├─controllers
│  │          │              ├─entity
│  │          │              └─repository
│  │          └─resources
│  │              └─META-INF
│  ├─db
│  └─frontend
│      ├─public
│      └─src
├─react-nginx
│  ├─.docker
│  ├─.nginx
│  ├─public
│  └─src
├─react-rust-postgres
│  ├─.docker
│  ├─backend
│  │  ├─migrations
│  │  └─src
│  └─frontend
│      ├─public
│      └─src
└─slack-clone-docker-main
    ├─eks
    ├─FrontEnd
    │  └─build
    │      └─static
    │          ├─css
    │          └─js
    ├─MongoDB
    ├─public
    ├─server
    └─src
        └─component
```

# todo

```
user@DAYA MINGW64 ~/docker-compose
$ git init
Initialized empty Git repository in C:/Users/user/docker-compose/.git/

$ git branch
*master
Then change master branch to main branch. Also pls check github repository settings(branch is main or not)

$ git branch -m master main

user@DAYA MINGW64 ~/docker-compose (main)
$ git add -A

user@DAYA MINGW64 ~/docker-compose (main)
$ git commit -m "My react dockers"


user@DAYA MINGW64 ~/dockers-master/dockers-master (main)
$ git remote add origin https://github.com/UserId/docker-compose.git

user@DAYA MINGW64 ~/dockers-compose (main)
$ git push -u origin main
```

# SEE ALSO

Some other stuff.
