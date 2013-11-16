CRM Perf
========

A demo CRM for my talk on "The Thick Front-End".

There are 4 applications in this series:

* [CRM Rails](http://github.com/dickeyxxx/crm_rails). A standard Rails app with no ajax and an API. Shows the baseline of how most apps are developed today.
* [CRM Rails-jQuery](http://github.com/dickeyxxx/crm_rails_jquery). A fork of CRM Rails that uses basecamp-style ajax.
* [CRM Angular](http://github.com/dickeyxxx/crm_angular). An Angular.js app that interfaces to either CRM Rails or CRM node.js.
* [CRM node.js](http://github.com/dickeyxxx/crm_node). A drop-in replacement for the CRM Rails API written in node.js.

Back-End Performance Results
============================

DO NOT READ TOO MUCH INTO THESE. This was just me playing around writing super
contrived applications. You should try these experiments (and more!) yourself to
determine what the right stack for your application is. I'm not trying to prove
a point about anything here, just having fun.

[Rails (Webrick) + PostgreSQL + HTML](https://www.blitz.io/report/dd5557fe3122f5542d33807c4d43064b)

![Rails (Webrick) + PostgreSQL + HTML](rails-pg-webrick-html.png)

[Rails (Thin) + PostgreSQL + HTML](https://www.blitz.io/report/dd5557fe3122f5542d33807c4d826410)

![Rails (Thin) + PostgreSQL + HTML](rails-pg-thin-html.png)

[Rails (Webrick) + PostgreSQL](https://www.blitz.io/report/dd5557fe3122f5542d33807c4de38308)

![Rails (Webrick) + PostgreSQL](rails-pg-webrick.png)

[Rails (Thin) + PostgreSQL](https://www.blitz.io/report/dd5557fe3122f5542d33807c4de3086a)

![Rails (Thin) + PostgreSQL](rails-pg-thin.png)

Rails + MongoDB

![Rails + MongoDB](rails-mongodb.png)

[node.js + PostgreSQL](https://www.blitz.io/report/dd5557fe3122f5542d33807c4de36ccb)

![node.js + MongoDB](node-pg.png)

[node.js + MongoDB](https://www.blitz.io/report/dd5557fe3122f5542d33807c4d637839)

![node.js + MongoDB](node-mongo.png)

TODO
====

* API documentation
* Scala
