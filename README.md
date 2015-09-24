# HTTP API Development Tools

## Introduction

This is a collection of useful resources for building RESTful HTTP+JSON APIs. There are a lot of good tools and entire ecosystems out there! It can be overwhelming not knowing what options are available, so you can use this as a reference starting point.

Contributions are most welcome. Categories are also open to suggestions!

## Table of Contents

*  [API Specification Languages](#api-specification-languages)
*  [API Specification Tools](#api-specification-tools)
*  [API Development Tools](#api-development-tools)
*  [API Client Library Tools](#api-client-library-tools)
*  [API Documentation](#api-documentation)
*  [API Testing](#api-testing)
*  [API Design Guides](#api-design-guides)
*  [API Publishing](#api-publishing)
*  [API Infrastructure](#api-infrastructure)
*  [API Monitoring](#api-monitoring)
*  [JSON Format Standards](#json-format-standards)
*  [REST Learning Resources](#rest-learning-resources)
*  [Miscellaneous](#miscellaneous)

## API Specification Languages
- [API Blueprint](https://github.com/apiaryio/api-blueprint)
- [JSON Schema](http://json-schema.org/)
- [RAML](http://raml.org/)
- [Swagger](http://swagger.io/)

## API Specification Tools
- [Swagger Editor](http://editor.swagger.io/#/): An editor for designing Swagger specifications.
- [Dredd](https://github.com/apiaryio/dredd): Validate API documentation written in API Blueprint against its backend implementation.

## API Development Tools
### Ruby
- [rails-api](https://github.com/rails-api/rails-api): Rails for API only applications.
- [pliny](https://github.com/interagent/pliny): Opinionated template Sinatra app for writing APIs in Ruby.
- [grape](https://github.com/intridea/grape): An opinionated micro-framework for creating REST-like APIs in Ruby.
- [ActiveModel::Serializer](https://github.com/rails-api/active_model_serializers): Brings convention over configuration to your JSON generation.
- [rabl](https://github.com/nesquena/rabl): Generate JSON and XML from any ruby object.
- [jbuilder](https://github.com/rails/jbuilder): Create JSON structures via a Builder-style DSL.

### Python
- [Django REST framework](http://www.django-rest-framework.org/): Toolkit that makes it easy to build Web APIs.
- [Tastypie](https://github.com/django-tastypie/django-tastypie): Webservice API framework for Django.
- [restless](https://github.com/toastdriven/restless): A lightweight REST miniframework for Python.
- [flask-restful](https://github.com/flask-restful/flask-restful): Simple framework for creating REST APIs.

### Javascript
- [hapi.js](http://hapijs.com/): Web and services application framework for Node.js.
- [node-restify](https://github.com/restify/node-restify): Node.js REST framework specifically meant for web service APIs.
- [expressjs](http://expressjs.com/): Fast, unopinionated, minimalist web framework for Node.js.
- [sailsjs](http://sailsjs.org/): Realtime MVC Framework for Node.js.

### Go
- [Go-Json-Rest](https://github.com/ant0ine/go-json-rest)

### Postgres
- [PostgREST](https://github.com/begriffs/postgrest): Serve a RESTful API from any existing PostgreSQL database.

### PHP
- [API Platform](https://github.com/dunglas/api-platform): API framework on top of Symfony with JSON-LD, Schema.org and Hydra support

## API Client Library Tools
### General
- [Swagger CodeGen](https://github.com/swagger-api/swagger-codegen): Generate client libraries automatically from a Swagger-compliant server.

### Ruby
- [heroics](https://github.com/interagent/heroics): Ruby HTTP client for APIs represented with JSON schema.
- [blanket](https://github.com/inf0rmer/blanket): A Ruby API wrapper.
- [nestful](https://github.com/maccman/nestful): Ruby HTTP/REST client.

## API Documentation
- [Swagger UI](https://github.com/swagger-api/swagger-ui): Dynamically generate documentation from a Swagger-compliant API.
- [Slate](https://github.com/tripit/slate): Static site generated documentation for your API.
- [prmd](https://github.com/interagent/prmd): JSON Schema tooling: scaffold, verify, and generate documentation from JSON Schema documents.
- [Aglio](https://github.com/danielgtaylor/aglio): An API Blueprint renderer with theme support that outputs static HTML.
- [Apiary](https://apiary.io/): Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.
- [Readme](http://readme.io/): API Documentation Hosting.
- [Embed curl](https://www.embedcurl.com/): Embeddable curl commands on the web.

## API Testing
- [Postman](https://www.getpostman.com/): Desktop API testing tool.
- [MockBin](https://mockbin.com/): Generate mock HTTP endpoints.
- [JSON Generator](http://www.json-generator.com/): Generate and host mock JSON data.
- [RequestBin](http://requestb.in/): Inspect and debug webhook POST requests.
- [Hurl.it](https://www.hurl.it/): Web-based HTTP client.

## API Design Guides
- [PayPal API Style Guide](https://github.com/paypal/api-standards/blob/master/api-style-guide.md)
- [Heroku Platform HTTP API Design Guide](https://github.com/interagent/http-api-design)
- [Haufe API Style Guide] (http://haufe-lexware.github.io/api-style-guide/)

## API Publishing
- [Mashape](mashape.com): API Marketplace.

## API Infrastructure
- [Kong](https://github.com/Mashape/kong): Open source API Gateway/Middleware layer.
- [API Umbrella](http://apiumbrella.io/):  Proxy that sits in front of your APIs.
- [APIAxle](https://github.com/apiaxle/apiaxle/): Proxy that sits in front of your APIs.
- [APIGrove](http://apigrove.github.io/apigrove/): API manager built in Java on top of Fuse ESB. 
- [APIUmbrella](https://github.com/NREL/api-umbrella):  API management platform
- [Tyk](http://tyk.io): API Mgmt Proxy in Go
- [Apigee127](https://github.com/apigee-127/a127-documentation/wiki/What-is-Apigee-127): nodejs based API Gateway
- [Pushpin](http://pushpin.org): Proxy for both request/response or streaming (long poll) of responses
- [Strongloop](https://github.com/strongloop/loopback-gateway): nodejs based API Gateway
- [Fusio](http://www.fusio-project.org/): PHP based open source API management platform

## API Monitoring
- [Runscope](https://www.runscope.com/): API Performance Monitoring.

## JSON Format Standards
- [HAL](http://stateless.co/hal_specification.html)
- [JSONAPI](http://jsonapi.org/faq/)

## REST Learning Resources
- [REST in Practice](http://shop.oreilly.com/product/9780596805838.do)
- [Roy Fielding's dissertation on REST](http://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)
- [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
- [How to Design a REST API](http://blog.octo.com/en/design-a-rest-api/)

## Miscellaneous
- [HTTP Status Codes Reference](http://httpstatus.es/)

## Contributing

[Pull Requests](https://github.com/Leventhan/api-development-tools/pulls) are most welcome!

Please write a brief one-sentence summary when adding a new resource.
