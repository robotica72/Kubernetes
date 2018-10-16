<b>Kubernetes Information</b>

This Github sections is where I store documents that I have created on Kubernetes subjects.   Most of the documents you will find here assume you have a running Kubernetes cluster - there are many helpful docs out there to install a K8s cluster, but if you are new you may want to look into the instructions at Kubernetes.io: https://kubernetes.io/docs/setup/independent/install-kubeadm/

Current Documents in this repo:

1.  Integrating OpenID Connect (OIDC) with Kubernetes and LDAP
This document provides step by step directions to integrate an OIDC provider with your Kubernetes Cluster(s).  The provider I use for this document is Openunison by Tremolo Security - it's one of the best OIDC providers available including a web page for retrieving your tokens, a reverse proxy to K8s dashboard, audit reporting, and a process to request and grant namespaces.  All of this and a full API to inteegrate Openunison features into any custom systems/scripts in your organization.
