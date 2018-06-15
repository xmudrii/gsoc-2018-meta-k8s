# Tracker for my GSoC project for CNCF and Kubernetes

This repository is used to track progress on my GSoC project for CNCF &amp; Kubernetes - Storage API for Aggregated API Servers.  

To easier track the progress about the project, I've created a public Trello board and a Google Document.  
I'll provide daily updates about the progress in both the Google Document and the Trello Board.

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

* [Project Repository (`xmudrii/etcdproxy-controller`)](https://github.com/xmudrii/etcdproxy-controller)
* [Submitted Proposal](https://github.com/xmudrii/gsoc-2018-meta-k8s/blob/master/proposal/proposal.pdf)
* [Proposal Draft (Google Doc)](https://docs.google.com/document/d/10IpBTo1dnaQ9H4u9Uwek-fL-gP1om4Zte0ZSvPbPLnY/edit?usp=sharing)
* [Project on GSoC website](https://summerofcode.withgoogle.com/projects/#6400208972283904)
* [Project on SIG-API-Machinery Mailing list](https://groups.google.com/forum/#!msg/kubernetes-sig-api-machinery/rHEoQ8cgYwk/iglsNeBwCgAJ)
* [Progress Tracker (Google Document)](https://docs.google.com/document/d/1LoqDnhb-1WV4Ja-8iS5n5Tm3NPVG50DndxsVbE17imE/edit?usp=sharing)
* [Progress Tracker (Trello Board)](https://trello.com/b/XeaS0l5E) 

## Blog posts

* [Blogpost: GSoC Journey: Week 1 & 3 — Community Bonding](https://xmudrii.com/posts/gsoc-weeks-1-3/)

## Pull Requests, Issues and Reviews made to the `etcdproxy-controller` repository

The following list is automatically generated using https://github.com/nikhita/github-contrib.

**Repository: etcdproxy-controller**

Total Pull Requests Created: 14
1. [xmudrii/etcdproxy-controller#23](https://github.com/xmudrii/etcdproxy-controller/pull/23) - Remove Kubeconfig validation rule
2. [xmudrii/etcdproxy-controller#22](https://github.com/xmudrii/etcdproxy-controller/pull/22) - Fix lint errors
3. [xmudrii/etcdproxy-controller#21](https://github.com/xmudrii/etcdproxy-controller/pull/21) - Use double-slash prefixed flags in controller deployment manifest
4. [xmudrii/etcdproxy-controller#20](https://github.com/xmudrii/etcdproxy-controller/pull/20) - Remove Config function in favor of Validate and ApplyTo
5. [xmudrii/etcdproxy-controller#19](https://github.com/xmudrii/etcdproxy-controller/pull/19) - Remove license headers from Go and Bash files
6. [xmudrii/etcdproxy-controller#16](https://github.com/xmudrii/etcdproxy-controller/pull/16) - Add documentation describing required setup and how to run EtcdProxyController
7. [xmudrii/etcdproxy-controller#15](https://github.com/xmudrii/etcdproxy-controller/pull/15) - Refactor the main package to use Cobra
8. [xmudrii/etcdproxy-controller#14](https://github.com/xmudrii/etcdproxy-controller/pull/14) -  Add status subresource and conditions to EtcdStorage CRD
9. [xmudrii/etcdproxy-controller#13](https://github.com/xmudrii/etcdproxy-controller/pull/13) - Make etcd image configurable. Add OwnerRef if object exists. Tighten functions to a private helper.
10. [xmudrii/etcdproxy-controller#6](https://github.com/xmudrii/etcdproxy-controller/pull/6) - Update Dockerfile to utilize Makefile
11. [xmudrii/etcdproxy-controller#4](https://github.com/xmudrii/etcdproxy-controller/pull/4) - Disable Travis fail email notifications
12. [xmudrii/etcdproxy-controller#3](https://github.com/xmudrii/etcdproxy-controller/pull/3) - Add manifest for deploying the controller
13. [xmudrii/etcdproxy-controller#2](https://github.com/xmudrii/etcdproxy-controller/pull/2) - Create controller for handling etcd proxy pods and services
14. [xmudrii/etcdproxy-controller#1](https://github.com/xmudrii/etcdproxy-controller/pull/1) - Add manifests for deploying core etcd and etcd proxy

Total Issues Opened: 13
1. [xmudrii/etcdproxy-controller#27](https://github.com/xmudrii/etcdproxy-controller/issues/27) - Improve redundancy and handle etcd proxy pod failures
2. [xmudrii/etcdproxy-controller#26](https://github.com/xmudrii/etcdproxy-controller/issues/26) - Allow multiple core etcd endpoints
3. [xmudrii/etcdproxy-controller#25](https://github.com/xmudrii/etcdproxy-controller/issues/25) - Add manifests for deploying sample-apiserver
4. [xmudrii/etcdproxy-controller#24](https://github.com/xmudrii/etcdproxy-controller/issues/24) - Add E2E tests
5. [xmudrii/etcdproxy-controller#18](https://github.com/xmudrii/etcdproxy-controller/issues/18) - Add additional conditions for EtcdStorage resources
6. [xmudrii/etcdproxy-controller#17](https://github.com/xmudrii/etcdproxy-controller/issues/17) - Remove license headers from files
7. [xmudrii/etcdproxy-controller#12](https://github.com/xmudrii/etcdproxy-controller/issues/12) - Update README file to include instructions how to use controller and how to run it out/in-cluster
8. [xmudrii/etcdproxy-controller#11](https://github.com/xmudrii/etcdproxy-controller/issues/11) - Tighten newReplicaSet and newService functions to a private helper
9. [xmudrii/etcdproxy-controller#10](https://github.com/xmudrii/etcdproxy-controller/issues/10) - Make etcd image property for creating ReplicaSet configurable
10. [xmudrii/etcdproxy-controller#9](https://github.com/xmudrii/etcdproxy-controller/issues/9) - Add OwnerRef if object already exists instead of failing
11. [xmudrii/etcdproxy-controller#8](https://github.com/xmudrii/etcdproxy-controller/issues/8) - Utilize the subresource status capability of the CRDs when updating CRD status
12. [xmudrii/etcdproxy-controller#7](https://github.com/xmudrii/etcdproxy-controller/issues/7) - Refactor the main package
13. [xmudrii/etcdproxy-controller#5](https://github.com/xmudrii/etcdproxy-controller/issues/5) - Switch to spf13/cobra for controller's CLI

## Pull Requests, Issues and Reviews made to the `kubernetes` organization

The following list is automatically generated using https://github.com/nikhita/github-contrib.

**Repository: kubernetes**

Total Pull Requests Created: 2
1. [kubernetes/kubernetes#63068](https://github.com/kubernetes/kubernetes/pull/63068) - Add Establishing Controller to avoid race between Established condition and CRs actually served
2. [kubernetes/kubernetes#60592](https://github.com/kubernetes/kubernetes/pull/60592) - apiextensions-apiserver: TestFinaliazationAndDeletion integration test

Total Issues Opened: 2
1. [kubernetes/kubernetes#63656](https://github.com/kubernetes/kubernetes/issues/63656) - Revisit Creating CustomResourceDefinitions from apiextensions-apiserver integration tests
2. [kubernetes/kubernetes#62725](https://github.com/kubernetes/kubernetes/issues/62725) - Improve Establishing logic for CRDs by implementing Installing status to prevent race conditions

Total Pull Requests Reviewed: 2
1. [kubernetes/kubernetes#63587](https://github.com/kubernetes/kubernetes/pull/63587) - apiextensions: handle CRD conflict errs in integration tests
2. [kubernetes/kubernetes#55476](https://github.com/kubernetes/kubernetes/pull/55476) - apiserver: document how to run sample-apiserver standalone outside the cluster
