---
layout: post
title:  "Entorno de trabajo"
date:   2015-12-07 02:19:14 -05:00
categories: jenkins docker sonarqube nexus docker-compose gogs git
---
El entorno de trabajo que usaremos en los meetups ha sido creado, es una primera versión basada en [Docker](http://www.docker.com) y [Docker Compose](http://docs.docker.com/compose) que cuenta con:

* Jenkins - servidor de Integración Continua.
* SonarQube - servidor de Inspección Continua.
* Nexus Repository - repositorio de artefactos.
* Gogs - servidor Git.

Está primera versión cuenta con algunos plugins de Jenkins. El único requisito es tener instalado [Docker Toolbox](http://www.docker.com/docker-toolbox) que trae consigo *Docker* y *Docker Compose*, descarga los recursos de nuestro repositorio [docke-env](https://www.github.com/jenkinsperu/docker-env) en github y sigue los pasos descritos en el archivo [README](https://github.com/jenkinsperu/docker-env/blob/master/README.adoc).
