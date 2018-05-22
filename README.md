# Tracker for my GSoC project for CNCF and Kubernetes

This repository is used to trace progress on my GSoC project for CNCF &amp; Kubernetes - Storage API for Aggregated API Servers.  

To easier track the progress about the project, I've created public Trello board and a Google Document.  
I'll provide daily updates about the progress in both the Google Document and Trello Board.

* [Google Document](https://docs.google.com/document/d/1LoqDnhb-1WV4Ja-8iS5n5Tm3NPVG50DndxsVbE17imE/edit?usp=sharing)
* [Trello Board](https://trello.com/b/XeaS0l5E)

## Abstract

Kubernetes offers two ways to extend the core API, by using the CustomResourceDefinitons or by setting up an aggregated API server. This ensures users don’t need to modify the core API in order to add the features needed for their workflow, which later ensures the more stable and secure core API.

One missing part is how to efficiently store data used by aggregated API servers. This project implements a Storage API, with a main goal to share the cluster’s main etcd server with the Aggregated API Servers, allowing it to use cluster’s main etcd just like it would use it’s own etcd server.

## General Information

Name: Marko Mudrinić  
E-mail: mudrinic.mare@gmail.com  
Website and Blog: https://xmudrii.com  
GitHub: [xmudrii](https://github.com/xmudrii)  
Slack (Kubernetes): xmudrii  
Twitter: [xmudrii](https://twitter.com/xmudrii)  
Time zone: UTC+02:00 (Central European Summer Time)  

## Links

* [Submitted Proposal](https://github.com/xmudrii/gsoc-2018-meta-k8s/blob/master/proposal/proposal.pdf)
* [Proposal Draft (Google Doc)](https://docs.google.com/document/d/10IpBTo1dnaQ9H4u9Uwek-fL-gP1om4Zte0ZSvPbPLnY/edit?usp=sharing)
* [Project on GSoC website](https://summerofcode.withgoogle.com/projects/#6400208972283904)
* [Project on SIG-API-Machinery Mailing list](https://groups.google.com/forum/#!msg/kubernetes-sig-api-machinery/rHEoQ8cgYwk/iglsNeBwCgAJ)
* [Progress Tracker (Google Document)](https://docs.google.com/document/d/1LoqDnhb-1WV4Ja-8iS5n5Tm3NPVG50DndxsVbE17imE/edit?usp=sharing)
* [Progress Tracker (Trello Board)](https://trello.com/b/XeaS0l5E) 

## Other Useful Links

* [Blogpost: GSoC Journey: Week 1 & 3 — Community Bonding](https://xmudrii.com/posts/gsoc-weeks-1-3/)

## Pull Requests and Issues

**Total: 4**

### Pull requests

Total Pull Requests Created: 2

1. [kubernetes/kubernetes#60592](https://github.com/kubernetes/kubernetes/pull/60592): apiextensions-apiserver: TestFinaliazationAndDeletion integration test
2. [kubernetes/kubernetes#63068](https://github.com/kubernetes/kubernetes/pull/63068): Add Establishing Controller to avoid race between Established condition and CRs actually served

### Issues

Total Issues Created: 2

1. [kubernetes/kubernetes#62725](https://github.com/kubernetes/kubernetes/issues/62725): Improve Establishing logic for CRDs by implementing Installing status to prevent race conditions
2. [kubernetes/kubernetes#63656](https://github.com/kubernetes/kubernetes/issues/63656): Revisit Creating CustomResourceDefinitions from apiextensions-apiserver integration tests