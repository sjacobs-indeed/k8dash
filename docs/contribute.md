---
layout: default
title: How to Contribute
permalink: /docs/contribute/
---

K8dash is installed as a standard at Indeed. 

### High-level Architecture

K8dash has two main components: 

* Client-side
* Server-side

**Client-side**

K8dash's client-side architecture consists of: 

* A React application built with `create-react-app`
* Sass
* Minimal third-party dependencies

The client-side code is in the `client` &gt; `src` folder. 
Within this folder you can find: 
* `index.js` 
* The views and art in SVG format 

**Server-side**

K8dash's client-side architecture consists of: 

* `@kubernetes/client-node`, the Kubernetes npm module
* Express webserver
* Node JS
* `http-proxy-middleware` for proxy requests to the Kubernetes API
* `openid-client` npm module for Open ID Connect (OIDC)

The server-side code in index.js is a proxy to the Kubernetes API consisting of less than 200 lines of code. 
