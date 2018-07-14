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
Slack ([Kubernetes](http://slack.k8s.io/)): xmudrii  
Twitter: [xmudrii](https://twitter.com/xmudrii)  
Time zone: UTC+02:00 (Central European Summer Time)  
Mentors: [David Eads](https://github.com/deads2k), [Dr. Stefan Schimanski](https://github.com/sttts)  

## Links

* [Project Repository (`xmudrii/etcdproxy-controller`)](https://github.com/xmudrii/etcdproxy-controller)
* [Submitted Proposal](https://github.com/xmudrii/gsoc-2018-meta-k8s/blob/master/proposal/proposal.pdf)
* [Proposal Draft (Google Doc)](https://docs.google.com/document/d/10IpBTo1dnaQ9H4u9Uwek-fL-gP1om4Zte0ZSvPbPLnY/edit?usp=sharing)
* [Project on GSoC website](https://summerofcode.withgoogle.com/projects/#6400208972283904)
* [Project on SIG-API-Machinery Mailing list](https://groups.google.com/forum/#!msg/kubernetes-sig-api-machinery/rHEoQ8cgYwk/iglsNeBwCgAJ)
* [CNCF GSoC Projects Announcement](https://www.cncf.io/blog/2018/06/22/cncf-joins-google-summer-of-code-2018-with-projects-envoy-proxy-containerd-coredns-prometheus-kubernetes-and-rook/)
* [Progress Tracker (Trello Board)](https://trello.com/b/XeaS0l5E) 
* [Progress Tracker (Google Document)](https://docs.google.com/document/d/1LoqDnhb-1WV4Ja-8iS5n5Tm3NPVG50DndxsVbE17imE/edit?usp=sharing)


## Blog posts

* [GSoC Journey: Week 1 & 3 — Community Bonding](https://xmudrii.com/posts/gsoc-weeks-1-3/)
* [GSoC Journey: Week 2 — Getting started with Kubernetes & KubeCon](https://xmudrii.com/posts/gsoc-week-2-kubecon/)

## Pull Requests, Issues and Reviews made to the `etcdproxy-controller` repository

The following list is automatically generated using https://github.com/nikhita/github-contrib.

**Repository: etcdproxy-controller**

Total Pull Requests Created: 29
1. [xmudrii/etcdproxy-controller#48](https://github.com/xmudrii/etcdproxy-controller/pull/48) - Rename core-etcd certificates to match names used by Kubernetes
2. [xmudrii/etcdproxy-controller#47](https://github.com/xmudrii/etcdproxy-controller/pull/47) - Enable RBAC in Travis-CI Minikube cluster and fix APIServer ConfigMap/Secret Role APIGroup
3. [xmudrii/etcdproxy-controller#46](https://github.com/xmudrii/etcdproxy-controller/pull/46) - Implement CA for handling EtcdProxy certificates
4. [xmudrii/etcdproxy-controller#45](https://github.com/xmudrii/etcdproxy-controller/pull/45) - Import GCP plugin to prevent controller startup failures in GKE
5. [xmudrii/etcdproxy-controller#42](https://github.com/xmudrii/etcdproxy-controller/pull/42) - Add note about GKE permissions note needed to deploy the controller and fix typo
6. [xmudrii/etcdproxy-controller#40](https://github.com/xmudrii/etcdproxy-controller/pull/40) - Set appropriate EtcdStorage condition on error. Improve event handling and error messages.
7. [xmudrii/etcdproxy-controller#39](https://github.com/xmudrii/etcdproxy-controller/pull/39) - Enable E2E tests in Travis-CI using Minikube and Kubernetes v1.10.0
8. [xmudrii/etcdproxy-controller#38](https://github.com/xmudrii/etcdproxy-controller/pull/38) - Upgrade etcd for etcd proxy pods to v3.3.8
9. [xmudrii/etcdproxy-controller#37](https://github.com/xmudrii/etcdproxy-controller/pull/37) - Prevent UpdateStatus loops
10. [xmudrii/etcdproxy-controller#36](https://github.com/xmudrii/etcdproxy-controller/pull/36) - Allow multiple core etcd endpoints to be specified
11. [xmudrii/etcdproxy-controller#35](https://github.com/xmudrii/etcdproxy-controller/pull/35) - Handle certificates for the etcd-proxy
12. [xmudrii/etcdproxy-controller#33](https://github.com/xmudrii/etcdproxy-controller/pull/33) - Add deploying Flunder resource to the sample-apiserver E2E story and fix minor bugs
13. [xmudrii/etcdproxy-controller#32](https://github.com/xmudrii/etcdproxy-controller/pull/32) - Add E2E tests
14. [xmudrii/etcdproxy-controller#29](https://github.com/xmudrii/etcdproxy-controller/pull/29) - Add server and client certificates to the core etcd deployment
15. [xmudrii/etcdproxy-controller#28](https://github.com/xmudrii/etcdproxy-controller/pull/28) - Create manifests for deploying the sample-apiserver
16. [xmudrii/etcdproxy-controller#23](https://github.com/xmudrii/etcdproxy-controller/pull/23) - Remove Kubeconfig validation rule
17. [xmudrii/etcdproxy-controller#22](https://github.com/xmudrii/etcdproxy-controller/pull/22) - Fix lint errors
18. [xmudrii/etcdproxy-controller#21](https://github.com/xmudrii/etcdproxy-controller/pull/21) - Use double-slash prefixed flags in controller deployment manifest
19. [xmudrii/etcdproxy-controller#20](https://github.com/xmudrii/etcdproxy-controller/pull/20) - Remove Config function in favor of Validate and ApplyTo
20. [xmudrii/etcdproxy-controller#19](https://github.com/xmudrii/etcdproxy-controller/pull/19) - Remove license headers from Go and Bash files
21. [xmudrii/etcdproxy-controller#16](https://github.com/xmudrii/etcdproxy-controller/pull/16) - Add documentation describing required setup and how to run EtcdProxyController
22. [xmudrii/etcdproxy-controller#15](https://github.com/xmudrii/etcdproxy-controller/pull/15) - Refactor the main package to use Cobra
23. [xmudrii/etcdproxy-controller#14](https://github.com/xmudrii/etcdproxy-controller/pull/14) -  Add status subresource and conditions to EtcdStorage CRD
24. [xmudrii/etcdproxy-controller#13](https://github.com/xmudrii/etcdproxy-controller/pull/13) - Make etcd image configurable. Add OwnerRef if object exists. Tighten functions to a private helper.
25. [xmudrii/etcdproxy-controller#6](https://github.com/xmudrii/etcdproxy-controller/pull/6) - Update Dockerfile to utilize Makefile
26. [xmudrii/etcdproxy-controller#4](https://github.com/xmudrii/etcdproxy-controller/pull/4) - Disable Travis fail email notifications
27. [xmudrii/etcdproxy-controller#3](https://github.com/xmudrii/etcdproxy-controller/pull/3) - Add manifest for deploying the controller
28. [xmudrii/etcdproxy-controller#2](https://github.com/xmudrii/etcdproxy-controller/pull/2) - Create controller for handling etcd proxy pods and services
29. [xmudrii/etcdproxy-controller#1](https://github.com/xmudrii/etcdproxy-controller/pull/1) - Add manifests for deploying core etcd and etcd proxy

Total Issues Opened: 19
1. [xmudrii/etcdproxy-controller#44](https://github.com/xmudrii/etcdproxy-controller/issues/44) - Update EtcdStorage CRD to check are provided name/namespace pairs for certificate ConfigMaps/Secrets valid
2. [xmudrii/etcdproxy-controller#43](https://github.com/xmudrii/etcdproxy-controller/issues/43) - Update certificates type and ConfigMap/Secret names to match Kubernetes TLS type and Secret names
3. [xmudrii/etcdproxy-controller#41](https://github.com/xmudrii/etcdproxy-controller/issues/41) - Improve event handling and error messages
4. [xmudrii/etcdproxy-controller#34](https://github.com/xmudrii/etcdproxy-controller/issues/34) - E2E tests are using incorrect Docker image for deploying the controller
5. [xmudrii/etcdproxy-controller#31](https://github.com/xmudrii/etcdproxy-controller/issues/31) - EtcdProxy Controller deployment doesn't work in GKE
6. [xmudrii/etcdproxy-controller#30](https://github.com/xmudrii/etcdproxy-controller/issues/30) - Add fields to EtcdStorage Spec for name and namespace of proxy etcd certs Secret/ConfigMap
7. [xmudrii/etcdproxy-controller#27](https://github.com/xmudrii/etcdproxy-controller/issues/27) - Improve redundancy and handle etcd proxy pod failures
8. [xmudrii/etcdproxy-controller#26](https://github.com/xmudrii/etcdproxy-controller/issues/26) - Allow multiple core etcd endpoints
9. [xmudrii/etcdproxy-controller#25](https://github.com/xmudrii/etcdproxy-controller/issues/25) - Add manifests for deploying sample-apiserver
10. [xmudrii/etcdproxy-controller#24](https://github.com/xmudrii/etcdproxy-controller/issues/24) - Add E2E tests
11. [xmudrii/etcdproxy-controller#18](https://github.com/xmudrii/etcdproxy-controller/issues/18) - Add additional conditions for EtcdStorage resources
12. [xmudrii/etcdproxy-controller#17](https://github.com/xmudrii/etcdproxy-controller/issues/17) - Remove license headers from files
13. [xmudrii/etcdproxy-controller#12](https://github.com/xmudrii/etcdproxy-controller/issues/12) - Update README file to include instructions how to use controller and how to run it out/in-cluster
14. [xmudrii/etcdproxy-controller#11](https://github.com/xmudrii/etcdproxy-controller/issues/11) - Tighten newReplicaSet and newService functions to a private helper
15. [xmudrii/etcdproxy-controller#10](https://github.com/xmudrii/etcdproxy-controller/issues/10) - Make etcd image property for creating ReplicaSet configurable
16. [xmudrii/etcdproxy-controller#9](https://github.com/xmudrii/etcdproxy-controller/issues/9) - Add OwnerRef if object already exists instead of failing
17. [xmudrii/etcdproxy-controller#8](https://github.com/xmudrii/etcdproxy-controller/issues/8) - Utilize the subresource status capability of the CRDs when updating CRD status
18. [xmudrii/etcdproxy-controller#7](https://github.com/xmudrii/etcdproxy-controller/issues/7) - Refactor the main package
19. [xmudrii/etcdproxy-controller#5](https://github.com/xmudrii/etcdproxy-controller/issues/5) - Switch to spf13/cobra for controller's CLI

## Pull Requests, Issues and Reviews made to the `kubernetes` organization

The following list is automatically generated using https://github.com/nikhita/github-contrib.

**Repository: kubernetes**

Total Pull Requests Created: 4
1. [kubernetes/kubernetes#65916](https://github.com/kubernetes/kubernetes/pull/65916) - [1.10] gc: remove crd and apiservice from ignored resources
2. [kubernetes/kubernetes#65206](https://github.com/kubernetes/kubernetes/pull/65206) - sample-apiserver: Add RBAC roles and ClusterRoleBindings for Admission Webhooks
3. [kubernetes/kubernetes#63068](https://github.com/kubernetes/kubernetes/pull/63068) - Add Establishing Controller to avoid race between Established condition and CRs actually served
4. [kubernetes/kubernetes#60592](https://github.com/kubernetes/kubernetes/pull/60592) - apiextensions-apiserver: TestFinaliazationAndDeletion integration test

Total Issues Opened: 3
1. [kubernetes/kubernetes#65442](https://github.com/kubernetes/kubernetes/issues/65442) - Create aggregated ClusterRole for API Servers to allow getting Namespaces and Admission Webhooks
2. [kubernetes/kubernetes#63656](https://github.com/kubernetes/kubernetes/issues/63656) - Revisit Creating CustomResourceDefinitions from apiextensions-apiserver integration tests
3. [kubernetes/kubernetes#62725](https://github.com/kubernetes/kubernetes/issues/62725) - Improve Establishing logic for CRDs by implementing Installing status to prevent race conditions

Total Pull Requests Reviewed: 4
1. [kubernetes/kubernetes#65918](https://github.com/kubernetes/kubernetes/pull/65918) - [1.9] GC: remove CRD and APIService from ignored resources
2. [kubernetes/kubernetes#65856](https://github.com/kubernetes/kubernetes/pull/65856) - only need to ignore resources that match discovery conditions
3. [kubernetes/kubernetes#63587](https://github.com/kubernetes/kubernetes/pull/63587) - apiextensions: handle CRD conflict errs in integration tests
4. [kubernetes/kubernetes#55476](https://github.com/kubernetes/kubernetes/pull/55476) - apiserver: document how to run sample-apiserver standalone outside the cluster
