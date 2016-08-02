# HTTP API Development Tools

## Introduction

This is a collection of useful resources for building RESTful HTTP+JSON APIs. There are a lot of good tools and entire ecosystems out there! It can be overwhelming not knowing what options are available, so you can use this as a reference starting point.

Contributions are most welcome. Categories are also open to suggestions!

## Table of Contents

*  [API Specification Languages](#api-specification-languages)
*  [API Specification Tools](#api-specification-tools)
*  [API Specifications](#api-specifications)
*  [API Frameworks](#api-frameworks)
*  [API Client Library Tools](#api-client-library-tools)
*  [API Documentation](#api-documentation)
*  [API Testing](#api-testing)
*  [API Design Guides](#api-design-guides)
*  [API Publishing](#api-publishing)
*  [API Gateways](#api-gateways)
*  [API Monitoring](#api-monitoring)
*  [JSON Format Standards](#json-format-standards)
*  [Learning Resources](#learning-resources)
*  [Blogs](#blogs)
*  [References](#references)

## API Specification Languages
- [API Blueprint](https://github.com/apiaryio/api-blueprint)
- [JSON Schema](http://json-schema.org/)
- [RAML](http://raml.org/)
- [Swagger](http://swagger.io/)

## API Specification Tools
- [Swagger Editor](http://editor.swagger.io/#/): An editor for designing Swagger specifications.
- [API Studio](http://apistudio.io/). Write, mock, and share your Swagger specifications online.
- [Dredd](https://github.com/apiaryio/dredd): Validate API documentation written in API Blueprint against its backend implementation.
- [APITransformer](https://apitransformer.com/): Transform API Descriptions from/to various formats e.g., Swagger, API Blueprint, RAML, WADL, Google Discovery, I/O Docs.
- [Restlet Studio](https://restlet.com/products/restlet-studio/): Web IDE for API Design.
- [API Spec Converter](https://lucybot.github.io/api-spec-converter/): Convert between different API spec formats.
- [Prism](http://stoplight.io/prism/): Supercharge any OAS file with mocking, transformations, validations, and more.

## API Specifications
- [APIS.guru](https://github.com/APIs-guru/api-models): Directory of API specs in OpenAPI(aka Swagger) 2.0 format.
- [AnyAPI](https://any-api.com/):  Documentation and Test Consoles for Public APIs.

## API Frameworks
### Ruby
- [rails-api](https://github.com/rails-api/rails-api): Rails for API only applications.
- [pliny](https://github.com/interagent/pliny): Opinionated template Sinatra app for writing APIs in Ruby.
- [grape](https://github.com/intridea/grape): An opinionated micro-framework for creating REST-like APIs in Ruby.
- [ActiveModel::Serializer](https://github.com/rails-api/active_model_serializers): Brings convention over configuration to your JSON generation.
- [rabl](https://github.com/nesquena/rabl): Generate JSON and XML from any ruby object.
- [jbuilder](https://github.com/rails/jbuilder): Create JSON structures via a Builder-style DSL.
- [roar](https://github.com/apotonick/roar): Parse and render REST API documents using representers.

### Python
- [Django REST framework](http://www.django-rest-framework.org/): Toolkit that makes it easy to build Web APIs.
- [Tastypie](https://github.com/django-tastypie/django-tastypie): Webservice API framework for Django.
- [restless](https://github.com/toastdriven/restless): A lightweight REST miniframework for Python.
- [flask-restful](https://github.com/flask-restful/flask-restful): Simple framework for creating REST APIs.
- [Falcon](https://github.com/falconry/falcon): Falcon is a low-level, high-performance Python framework for building HTTP APIs, app backends, and higher-level frameworks.

### Javascript
- [hapi.js](http://hapijs.com/): Web and services application framework for Node.js.
- [Restify](https://github.com/restify/node-restify): Node.js REST framework specifically meant for web service APIs.
- [Express](http://expressjs.com/): Fast, unopinionated, minimalist web framework for Node.js.
- [sailsjs](http://sailsjs.org/): Realtime MVC Framework for Node.js.
- [Actionhero](http://www.actionherojs.com/): Multi-transport Node.js API server with integrated cluster capabilities and delayed tasks.
- [Baucis](https://github.com/wprl/baucis): To build
- [Koa](http://koajs.com/): Next generation web framework for Node.js
- [Loopback](http://loopback.io/): Node.js framework for creating APIs and easily connecting to backend data sources.
- [Seneca](http://senecajs.org/): A microservices toolkit for Node.js.
- [Feathers](http://feathersjs.com/): Build RESTful and real-time APIs through Socket.io or Primus.

### Go
- [Go-Json-Rest](https://github.com/ant0ine/go-json-rest)

### Scala

- [Colossus](https://github.com/tumblr/colossus): I/O and microservice library for Scala.
- [Finatra](http://twitter.github.io/finatra/): Fast, testable, Scala HTTP services built on Twitter-Server and Finagle.
- [Play](https://www.playframework.com/): The high velocity web framework for Java and Scala.
- [Scalatra](http://www.scalatra.org/): Simple, accessible and free web micro-framework.
- [Skinny Micro](https://github.com/skinny-framework/skinny-micro): Micro-web framework to build servlet applications in Scala.
- [Spray](http://spray.io/): Open-source toolkit for building REST/HTTP-based integration layers on top of Scala and Akka.

### Java

- [Rest.li](http://rest.li/): REST framework using type-safe bindings and asynchronous, non-blocking IO.

### Haskell

- [Scotty](https://github.com/scotty-web/scotty): Micro web framework inspired by Ruby's Sinatra, using WAI and Warp.
- [Yesod](https://github.com/yesodweb/yesod): The Haskell RESTful web framework.

### Elixir

- [Phoenix](http://www.phoenixframework.org/): Framework for building HTML5 apps, API backends and distributed systems.
- [Plug](https://github.com/elixir-lang/plug): A specification and conveniences for composable modules between web applications.

### Erlang

- [Cowboy](https://github.com/ninenines/cowboy): Small, fast, modular HTTP server written in Erlang.
- [Gen Microservice](https://github.com/videlalvaro/gen_microservice): This library solves the problem of implementing microservices with Erlang.
- [Mochiweb](https://github.com/mochi/mochiweb): Erlang library for building lightweight HTTP servers.

### Postgres
- [PostgREST](https://github.com/begriffs/postgrest): Serve a RESTful API from any existing PostgreSQL database.

### PHP
- [API Platform](https://github.com/dunglas/api-platform): API framework on top of Symfony with JSON-LD, Schema.org and Hydra support

## API Client Library Tools
### General
- [Swagger CodeGen](https://github.com/swagger-api/swagger-codegen): Generate client libraries automatically from a Swagger-compliant server.
- [sdks.io](https://sdks.io/): Explore Automatically Generated SDKs.

### Ruby
- [heroics](https://github.com/interagent/heroics): Ruby HTTP client for APIs represented with JSON schema.
- [blanket](https://github.com/inf0rmer/blanket): A Ruby API wrapper.
- [nestful](https://github.com/maccman/nestful): Ruby HTTP/REST client.

### Java
- [Retrofit](http://square.github.io/retrofit/): A type-safe HTTP client for Android and Java.

## API Documentation
- [Swagger UI](https://github.com/swagger-api/swagger-ui): Dynamically generate documentation from a Swagger-compliant API.
- [Slate](https://github.com/tripit/slate): Static site generated documentation for your API.
- [prmd](https://github.com/interagent/prmd): JSON Schema tooling: scaffold, verify, and generate documentation from JSON Schema documents.
- [Aglio](https://github.com/danielgtaylor/aglio): An API Blueprint renderer with theme support that outputs static HTML.
- [Apiary](https://apiary.io/): Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.
- [Readme](http://readme.io/): API Documentation Hosting.
- [Embed curl](https://www.embedcurl.com/): Embeddable curl commands on the web.
- [Gelato](https://gelato.io/): Create developer portals for your API.
- [API Docs](http://api-docs.io/): Hosted public API documentation for OAS (Swagger) and RAML specs.


## API Testing
- [Postman](https://www.getpostman.com/): Desktop API testing tool.
- [Paw](https://luckymarmot.com/paw): REST client for Mac.
- [Insomnia REST Client](http://insomnia.rest/): REST client Chrome app.
- [MockBin](https://mockbin.com/): Generate mock HTTP endpoints.
- [JSON Generator](http://www.json-generator.com/): Generate and host mock JSON data.
- [RequestBin](http://requestb.in/): Inspect and debug webhook POST requests.
- [Hurl.it](https://www.hurl.it/): Web-based HTTP client.

## API Design Guides
- [PayPal API Style Guide](https://github.com/paypal/api-standards/blob/master/api-style-guide.md)
- [Heroku Platform HTTP API Design Guide](https://github.com/interagent/http-api-design)
- [Haufe API Style Guide](http://haufe-lexware.github.io/api-style-guide/)

## API Publishing
- [Mashape](https://www.mashape.com/): API Marketplace.

## API Gateways
- [AWS API Gateway](https://aws.amazon.com/api-gateway/). Traffic management, authorization and access control, monitoring, and API version management.
- [API Umbrella](http://apiumbrella.io/):  Proxy that sits in front of your APIs.
- [APIAxle](https://github.com/apiaxle/apiaxle/): Proxy that sits in front of your APIs.
- [APIGrove](http://apigrove.github.io/apigrove/): API manager built in Java on top of Fuse ESB.
- [APIUmbrella](https://github.com/NREL/api-umbrella):  API management platform
- [Apigee127](https://github.com/apigee-127/a127-documentation/wiki/What-is-Apigee-127): nodejs based API Gateway
- [Pushpin](http://pushpin.org): Proxy for both request/response or streaming (long poll) of responses
- [Strongloop](https://github.com/strongloop/loopback-gateway): nodejs based API Gateway
- [Fusio](http://www.fusio-project.org/): PHP based open source API management platform
- [Camel](http://camel.apache.org/) - Empowers you to define routing and mediation rules in a variety of domain-specific languages, including a Java-based fluent API, Spring or Blueprint XML configuration files, and a Scala DSL.
- [HAProxy](http://www.haproxy.org/) - Reliable, high Performance TCP/HTTP load balancer.
- [OpenResty](http://openresty.org/) - Fast web application server built on top of Nginx.
- [Tengine](http://tengine.taobao.org/) - A distribution of Nginx with some advanced features.
- [Tyk](https://tyk.io/) - Open-source, fast and scalable API gateway, portal and API management platform.
- [Vulcand](https://github.com/mailgun/vulcand) - Programmatic load balancer backed by Etcd.
- [Zuul](https://github.com/Netflix/zuul) - An edge service that provides dynamic routing, monitoring, resiliency, security, and more.
- [Kong](https://getkong.org/) - An open-source management layer for APIs, delivering high performance and reliability.


## API Monitoring
- [Runscope](https://www.runscope.com/): API Performance Monitoring.
- [Galileo](https://www.apianalytics.com/): API Monitoring Platform.
- [Ping-API](https://ping-api.com/): Automated API Testing.

## JSON Format Standards
- [HAL](http://stateless.co/hal_specification.html)
- [JSONAPI](http://jsonapi.org/faq/)
- [JSON Schema](http://json-schema.org/)

## Learning Resources
- [Choosing an HTTP Status Code](http://racksburg.com/choosing-an-http-status-code/)
- [REST in Practice](http://shop.oreilly.com/product/9780596805838.do)
- [Roy Fielding's dissertation on REST](http://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)
- [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
- [How to Design a REST API](http://blog.octo.com/en/design-a-rest-api/)
- [Automated API Development](http://yosriady.com/2016/04/27/automated-api-development/)
- [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md)

## Blogs
- [API Evangelist](http://apievangelist.com/blog/)

## References
- [HTTP Status Codes Reference](http://httpstatus.es/)

## Contributing

[Pull Requests](https://github.com/Leventhan/api-development-tools/pulls) are most welcome!

Please write a brief one-sentence summary when adding a new resource.

## Thanks

**api-development-tools** © 2016+, Yos Riady. Released under the [MIT] License.<br>
Authored and maintained by Yos Riady with help from contributors ([list][contributors]).

> [yos.io](http://yos.io) &nbsp;&middot;&nbsp;
> GitHub [@yosriady](https://github.com/yosriady)

[MIT]: http://mit-license.org/
[contributors]: http://github.com/yosriady/api-development-tools/contributors
