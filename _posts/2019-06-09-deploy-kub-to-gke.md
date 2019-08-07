---
layout: post
title: Deploying a Kub App on GKE
# permalink: /guides/deploy-kubernetics-to-gke
logoUrl: /assets/img/guides/kubernetics_image.png
excerpt: Before we can deploy a dockerized app, we need to first create one. For the purposes of this guide we will create a basic Node.js app that responds to requests on port 8080.
categories: [guides]
tags: [Kubernetics, GKE]
toc: true
---

* TOC 
{:toc}
* 
## In order to follow this guide you will need
1. A GCP account with billing enabled. There is a free tier that includes $300 of free credit over a 12 month period.
2. Terraform v0.10.3 or later installed locally.
3. A recent version of the gcloud command-line tool.
4. A basic understanding of Node.js is also recommended.

## Creating A Basic App

Before we can deploy a dockerized app, we need to first create one. For the purposes of this guide we will create a basic Node.js app that responds to requests on port 8080.
Start by creating a file called server.js and paste in the following source code:
Before we can deploy a dockerized app, we need to first create one. For the purposes of this guide we will create a basic Node.js app that responds to requests on port 8080.
Start by creating a file called server.js and paste in the following source code:Before we can deploy a dockerized app, we need to first create one. For the purposes of this guide we will create a basic Node.js app that responds to requests on port 8080.
Start by creating a file called server.js and paste in the following source code:Before we can deploy a dockerized app, we need to first create one. For the purposes of this guide we will create a basic Node.js app that responds to requests on port 8080.
Start by creating a file called server.js and paste in the following source code:
![My helpful screenshot](/assets/img/guides/code-block.png)

Next, we need a simple package.json file in order to make this work properly:
![My helpful screenshot](/assets/img/guides/code-block.png)

Before we can deploy a dockerized app, we need to first create one. For the purposes of this guide we will create a basic Node.js app that responds to requests on port 8080.
Start by creating a file called server.js and paste in the following source code:
![My helpful screenshot](/assets/img/guides/code-block.png)

Next, we need a simple package.json file in order to make this work properly:
![My helpful screenshot](/assets/img/guides/code-block.png)