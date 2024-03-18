# HTTP API Development Tools

## Introduction
This is a collection of useful resources for building RESTful HTTP+JSON APIs. There are a lot of good tools and entire ecosystems out there! It can be overwhelming not knowing what options are available, so you can use this as a reference starting point.

Contributions are most welcome. Categories are also open to suggestions!

## Table of Contents
*  [API Specification Languages](#api-specification-languages)
*  [API Specification Tools](#api-specification-tools)
*  [API Specifications](#api-specifications)
*  [API Frameworks](#api-frameworks)
*  [API Client Development Tools](#api-client-development-tools)
*  [API Documentation](#api-documentation)
*  [API Clients](#api-clients)
*  [API Debugging and Mocking](#api-debugging-and-mocking)
*  [API Design Guides](#api-design-guides)
*  [API Publishing](#api-publishing)
*  [API Gateways](#api-gateways)
*  [API Security](#api-security)
*  [API Monitoring](#api-monitoring)
*  [API Testing](#api-testing)
*  [API Developer Portal](#api-developer-portal)
*  [JSON Format Standards](#json-format-standards)
*  [Learning Resources](#learning-resources)
*  [Blogs](#blogs)
*  [References](#references)

## API Specification Languages
- [OpenAPI (formerly known as Swagger)](https://github.com/OAI/OpenAPI-Specification)
- [API Blueprint](https://github.com/apiaryio/api-blueprint)
- [JSON Schema](http://json-schema.org/)
- [RAML](https://raml.org/)

## API Specification Tools
- [Swagger Inspector](https://swagger.io/tools/swagger-inspector/): Test and auto-generate OpenAPI documentation for any API.
- [Swagger Editor](http://editor.swagger.io/): An editor for designing Swagger specifications.
- [Swagger Tools and Integrations](https://swagger.io/open-source-integrations/): A list of libraries and frameworks serving the Swagger ecosystem.
- [OpenAPI extension for VS Code](https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi):  Visual Studio Code (VS Code) extension that provides support for the OpenAPI Specification.
- [OpenAPI plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/14837-openapi-swagger-editor): Jetbrains plugin that provides support for the OpenAPI Specification.
- [Dredd](https://github.com/apiaryio/dredd): Validate API documentation written in API Blueprint against its backend implementation.
- [API Spec Converter](https://lucybot-inc.github.io/api-spec-converter/): Convert between different API spec formats.
- [Apimatic](https://www.apimatic.io/): Supports API description formats including Swagger, OAI format, RAML, API Blueprint, IO Docs, WADL, Postman Collections and HAR 1.4 and more
- [OpenAPI Definition Designer](https://openapidesigner.com): Free visual OpenAPI3 definition creation and editing tool.
- [Stoplight Studio](https://stoplight.io/studio/): Create, prototype, and share OpenAPI descriptions and JSON Schemas using a visual editor.
- [Spectral](https://github.com/stoplightio/spectral): Define rulesets to lint YAML or JSON, including OpenAPI 2.x, 3.x and AsyncAPI
- [Optic](https://www.useoptic.com/docs/openapi/generate-from-traffic): Verify the accuracy of your OpenAPI 3.x spec using real traffic, and automatically apply patches that keep it up-to-date

## API Specifications
- [API Commons](http://apicommons.org/): A repository of language-agnostic API specifications / Data Models.
- [APIS.guru](https://apis.guru/openapi-directory/): Directory of API specs in OpenAPI(aka Swagger) 2.0 format.
- [AnyAPI](https://any-api.com/): Documentation and Test Consoles for Public APIs.

## API Frameworks

### Ruby
- [rails-api](https://github.com/rails-api/rails-api): Rails for API only applications.
- [pliny](https://github.com/interagent/pliny): Opinionated template Sinatra app for writing APIs in Ruby.
- [grape](https://github.com/ruby-grape/grape): An opinionated micro-framework for creating REST-like APIs in Ruby.
- [ActiveModel::Serializer](https://github.com/rails-api/active_model_serializers): Brings convention over configuration to your JSON generation.
- [rabl](https://github.com/nesquena/rabl): Generate JSON and XML from any ruby object.
- [jbuilder](https://github.com/rails/jbuilder): Create JSON structures via a Builder-style DSL.
- [roar](https://github.com/trailblazer/roar): Parse and render REST API documents using representers.

### Python
- [Django REST framework](http://www.django-rest-framework.org/): Toolkit that makes it easy to build Web APIs.
- [Tastypie](https://github.com/django-tastypie/django-tastypie): Webservice API framework for Django.
- [restless](https://github.com/toastdriven/restless): A lightweight REST miniframework for Python.
- [flask-restful](https://github.com/flask-restful/flask-restful): Simple framework for creating REST APIs.
- [Falcon](https://github.com/falconry/falcon): Falcon is a low-level, high-performance Python framework for building HTTP APIs, app backends, and higher-level frameworks.
- [Connexion](https://github.com/zalando/connexion): Swagger/OpenAPI First framework for Python on top of Flask with automatic endpoint validation and OAuth2 support
- [apistar](https://github.com/encode/apistar): A smart Web API framework, designed for Python3.
- [sanic](https://github.com/channelcat/sanic): Sanic is a Flask-like Python 3.5+ web server that's written to go fast.
- [hug](https://github.com/timothycrosley/hug): hug aims to make developing Python driven APIs as simple as possible, but no simpler.
- [FastAPI](https://github.com/tiangolo/fastapi): FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints. 

### Javascript
- [hapi.js](https://hapijs.com/): Web and services application framework for Node.js.
- [Restify](https://github.com/restify/node-restify): Node.js REST framework specifically meant for web service APIs.
- [Express](https://expressjs.com/): Fast, unopinionated, minimalist web framework for Node.js.
- [sailsjs](http://sailsjs.org/): Realtime MVC Framework for Node.js.
- [Actionhero](https://www.actionherojs.com/): Multi-transport Node.js API server with integrated cluster capabilities and delayed tasks.
- [Baucis](https://github.com/wprl/baucis): To build
- [Koa](http://koajs.com/): Next generation web framework for Node.js
- [Loopback](http://loopback.io/): Node.js framework for creating APIs and easily connecting to backend data sources.
- [Seneca](http://senecajs.org/): A microservices toolkit for Node.js.
- [Feathers](https://feathersjs.com/): Build RESTful and real-time APIs through Socket.io or Primus.
- [Deployd](https://github.com/deployd/deployd): Deployd is the simplest way to build realtime APIs for web and mobile apps
- [Nest](https://github.com/kamilmysliwiec/nest): A modern node.js framework for efficient and scalable web applications built on top of TypeScript

### Go
- [Go-Json-Rest](https://github.com/ant0ine/go-json-rest): Thin layer on top of `net/http` that helps building RESTful APIs easily
- [gocrud](https://github.com/manishrjain/gocrud): Go library to simplify creating, updating and deleting arbitrary depth structured data — to make building REST services fast and easy.
- [sleepy](https://github.com/dougblack/sleepy): RESTful micro-framework written in Go.
- [restit](https://github.com/go-restit/restit): Go micro framework to help writing RESTful API integration test.
- [go-relax](https://github.com/codehack/go-relax): Framework of pluggable components to build RESTful API's.
- [go-rest](https://github.com/ungerik/go-rest): Small and evil REST framework for Go.
- [go-restful](https://github.com/emicklei/go-restful): A declarative highly readable framework for building restful API's.
- [Goat](https://github.com/bahlo/goat): Minimalistic REST API server in Go.
- [Resoursea](https://github.com/resoursea/api): REST framework for quickly writing resource based services.
- [Zerver](https://github.com/cosiner/zerver): Zerver is a expressive, modular, feature completed RESTful framework.
- [Fiber](https://github.com/gofiber/fiber): :zap:Fiber is an Express inspired web framework written in Go with :coffee: .

### Scala
- [Colossus](https://github.com/tumblr/colossus): I/O and microservice library for Scala.
- [Finatra](https://twitter.github.io/finatra/): Fast, testable, Scala HTTP services built on Twitter-Server and Finagle.
- [Play](https://www.playframework.com/): The high velocity web framework for Java and Scala.
- [Scalatra](http://www.scalatra.org/): Simple, accessible and free web micro-framework.
- [Skinny Micro](https://github.com/skinny-framework/skinny-micro): Micro-web framework to build servlet applications in Scala.
- [Spray](http://spray.io/): Open-source toolkit for building REST/HTTP-based integration layers on top of Scala and Akka.
- [Akka HTTP](https://github.com/akka/akka-http): The Akka HTTP modules implement a full server- and client-side HTTP stack on top of akka-actor and akka-stream.
- [Swagger Akka HTTP](https://github.com/swagger-akka-http/swagger-akka-http): Swagger-Akka-Http brings Swagger support for Akka-Http Apis.

### Java
- [Rest.li](http://rest.li/): REST framework using type-safe bindings and asynchronous, non-blocking IO.
- [Dropwizard](https://www.dropwizard.io/en/latest/): Framework for developing ops-friendly, high-performance, RESTful web services.
- [Jersey](https://jersey.java.net/): RESTful web services in Java.
- [Spring Boot](https://projects.spring.io/spring-boot/): RESTful Web Service using Spring, high-performance and little configuration needed.
- [Metamug Mason](https://github.com/metamug/mason): Create REST APIs with JSP tags and SQL. Edit and hot deploy REST resources on the server.

### Haskell
- [Scotty](https://github.com/scotty-web/scotty): Micro web framework inspired by Ruby's Sinatra, using WAI and Warp.
- [Spock](https://github.com/agrafix/Spock): Another Haskell web framework for rapid development.
- [Servant](https://github.com/haskell-servant/servant): A Type-Level Web DSL.
- [Yesod](https://github.com/yesodweb/yesod): The Haskell RESTful web framework.

### Elixir
- [Phoenix](http://phoenixframework.org/): Framework for building HTML5 apps, API backends and distributed systems.
- [Plug](https://github.com/elixir-plug/plug): A specification and conveniences for composable modules between web applications.

### Erlang
- [Cowboy](https://github.com/ninenines/cowboy): Small, fast, modular HTTP server written in Erlang.
- [Gen Microservice](https://github.com/videlalvaro/gen_microservice): This library solves the problem of implementing microservices with Erlang.
- [Mochiweb](https://github.com/mochi/mochiweb): Erlang library for building lightweight HTTP servers.

### Postgres
- [PostgREST](https://github.com/begriffs/postgrest): Serve a RESTful API from any existing PostgreSQL database.
- [pREST](https://github.com/prest/prest): pREST is a way to serve a RESTful API from any databases written in Go.

### MySQL
- [xmysql](https://github.com/o1lab/xmysql): Generate REST APIs for any MySQL Database.

### PHP
- [API Platform](https://github.com/api-platform/api-platform): API framework on top of Symfony with JSON-LD, Schema.org and Hydra support
- [Dingo API](https://github.com/dingo/api): A RESTful API package for the Laravel and Lumen frameworks
- [Fractal](https://github.com/thephpleague/fractal): Fractal provides a presentation and transformation layer for complex data output, the like found in RESTful APIs, and works really well with JSON
- [Yii2 Framework](https://github.com/yiisoft/yii2): Provides a whole set of tools to simplify the task of implementing RESTful Web Service APIs

### R
- [Plumber](https://www.rplumber.io/): API Framework to build APIs for simple R Functions

### C#
- [ASP.NET Web APIs](https://dotnet.microsoft.com/en-us/apps/aspnet/apis): Build secure REST APIs on any platform with C#

### Miscellaneous
- [Dream Factory](https://github.com/dreamfactorysoftware/dreamfactory): Turn any database into an API platform.

## API Client Development Tools

### General
- [Swagger CodeGen](https://github.com/swagger-api/swagger-codegen): Generate client libraries automatically from a Swagger-compliant server.
- [AutoRest](https://github.com/Azure/autorest): Generate client libraries for RESTful web services
- [OpenAPI Generator](https://github.com/openapitools/openapi-generator): A community fork of Swagger Codegen to automatically generate API clients, server stubs and documentation for REST APIs given an OpenAPI/Swagger spec.
- [at-your-service](https://atyourservice.awalsh.io/): A developer tool for API observability on the browser. Generate OpenAPI specifications and code from network traffic.

### Ruby
- [Net::HTTP](https://apidock.com/ruby/Net/HTTP): An HTTP client API for Ruby.
- [faraday](https://github.com/lostisland/faraday): Simple, but flexible HTTP client library, with support for multiple backends.
- [rest-client](https://github.com/rest-client/rest-client): Simple HTTP and REST client for Ruby
- [heroics](https://github.com/interagent/heroics): Ruby HTTP client for APIs represented with JSON schema.
- [blanket](https://github.com/inf0rmer/blanket): A Ruby API wrapper.
- [nestful](https://github.com/maccman/nestful): Ruby HTTP/REST client.

### Java
- [Retrofit](https://square.github.io/retrofit/): A type-safe HTTP client for Android and Java.

### Javascript
- [Restangular](https://github.com/mgonto/restangular): Restangular is an AngularJS service that simplifies common GET, POST, DELETE, and UPDATE requests with a minimum of client code

### .NET
- [Refit](https://github.com/paulcbetts/refit): The automatic type-safe REST library for .NET Core, Xamarin and .NET
- [WebAnchor](https://github.com/mattiasnordqvist/Web-Anchor): Web Anchor provides type-safe, testable and flexible access to web resources.

### .Dart
- [Frog](https://dartfrog.vgv.dev/docs/overview): Dart Frog is built on top of shelf and mason and is inspired by many tools including remix.run, next.js, and express.js. 
- [Serverpod](https://github.com/serverpod/serverpod): Serverpod is a next-generation app and web server, built for the Flutter community. It allows you to write your server-side code in Dart, automatically generate your APIs, and hook up your database with minimal effort. Serverpod is open-source, and you can host your server anywhere.


## API Documentation
- [ReDoc](https://github.com/Rebilly/ReDoc): OpenAPI/Swagger-generated API Reference Documentation.
- [Swagger UI](https://github.com/swagger-api/swagger-ui): Dynamically generate documentation from a Swagger-compliant API.
- [Slate](https://github.com/lord/slate): Static site generated documentation for your API.
- [DeveloperHub](https://developerhub.io/): Documentation tool to write, publish, review, analyse and collect feedback on personalised customer-facing API docs.
- [prmd](https://github.com/interagent/prmd): JSON Schema tooling: scaffold, verify, and generate documentation from JSON Schema documents.
- [Aglio](https://github.com/danielgtaylor/aglio): An API Blueprint renderer with theme support that outputs static HTML.
- [Apiary](https://apiary.io/): Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.
- [Readme](https://readme.io/): API Documentation Hosting.
- [API Docs](https://api-docs.io/): Hosted public API documentation for OAS (Swagger) and RAML specs.
- [Docbox](https://github.com/tmcw/docbox): REST API documentation generator, using Markdown.
- [widdershins](https://github.com/Mermade/widdershins): REST API documentation generator from OpenAPI 3.0 / Swagger 2.0 / AsyncAPI 1.x / Semoasa 0.1.0 definition
- [Elements](https://github.com/stoplightio/elements): Web Components-based API documentation for OpenAPI 3.x/2.x

## API Clients

### Open Source
- [Hoppscotch](https://github.com/hoppscotch/hoppscotch): API client for REST, GraphQL, Websocket, SSE, Socket.IO and MQTT
- [Hurl](https://github.com/Orange-OpenSource/hurl): Hurl makes it easy to work with HTML content, REST / SOAP / GraphQL APIs, or any other XML / JSON based APIs.

### Hosted
- [JSON Generator](http://www.json-generator.com/): Generate and host mock JSON data.

### Desktop
- [Postman](https://www.getpostman.com): Desktop API testing tool.
- [Firecamp](https://firecamp.app): API Studio for WebSocket, Rest API and GraphQL.
- [HTTPie](https://httpie.org/): Command line HTTP client.
- [Paw](https://paw.cloud/): REST client for Mac.
- [Insomnia](https://insomnia.rest/): REST API client for Mac, Windows, and Linux.
- [httpy](https://github.com/knid/httpy): Programmable Command line HTTP client.

## API Debugging and Mocking

### Hosted
- [Beeceptor](https://beeceptor.com): An HTTP-proxy for rest APIs - inspect and build mock APIs.
- [MockBin](https://mockbin.com/): Generate mock HTTP endpoints.
- [httpbin](http://httpbin.org): Templated responses for testing various scenarios for HTTP requests.
- [Prism](https://github.com/stoplightio/prism): a set of packages for API mocking and contract testing with OpenAPI v2 (formerly known as Swagger) and OpenAPI v3.x, including mock servers and a validation proxy.
- [MockingCloud](https://mockingcloud.com): Generate full mock REST APIs with just OpenAPI yaml/json spec files.
- [Svix Play](https://www.svix.com/play/): Easily inspect, test, and debug incoming webhooks.

### Desktop 
- [Postman](https://www.getpostman.com/docs/postman/mock_servers/setting_up_mock): Desktop API client and mocking tool.
- [Json-Server](https://github.com/typicode/json-server) Full fake REST API with zero coding.
- [Mockoon](https://mockoon.com): Desktop API mocking tool.

## API Design Guides
- [Google API Design Guide](https://cloud.google.com/apis/design/)
- [PayPal API Style Guide](https://github.com/paypal/api-standards/blob/master/api-style-guide.md)
- [Heroku Platform HTTP API Design Guide](https://github.com/interagent/http-api-design)
- [Haufe API Style Guide](http://work.haufegroup.io/api-style-guide/)
- [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md)
- [18F API Standards](https://github.com/18f/api-standards)
- [The RESTed NARWHL](https://www.narwhl.com/)
- [White House Web API Standards](https://github.com/whitehouse/api-standards)
- [Zalando REST API Guidelines](https://zalando.github.io/restful-api-guidelines/)
- [API Stylebook Design Guidelines](http://apistylebook.com/design/guidelines/)
- [API Stylebook Design Topics](http://apistylebook.com/design/topics/)
- [Adidas-group API Design Guide](https://github.com/adidas-group/api-guidelines)
- [Azure API Design](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## API Publishing
- [Mashape](https://www.mashape.com/): API Marketplace.

## API Gateways
- [AWS API Gateway](https://aws.amazon.com/api-gateway/): Traffic management, authorization and access control, monitoring, and API version management.
- [Ambassador API Gateway](https://www.getambassador.io/): Ambassador is a specialized control plane that translates Kubernetes annotations to Envoy configuration. All traffic is directly handled by the high-performance Envoy Proxy.
- [APIGrove](https://apigrove.github.io/apigrove/): API manager built in Java on top of Fuse ESB.
- [Apigee127](https://github.com/apigee-127/a127-documentation/wiki/What-is-Apigee-127): nodejs based API Gateway
- [Pushpin](http://pushpin.org): Proxy for both request/response or streaming (long poll) of responses
- [Strongloop](https://github.com/strongloop/microgateway): nodejs based API Gateway
- [Fusio](http://www.fusio-project.org/): PHP based open source API management platform
- [Camel](https://camel.apache.org/): Empowers you to define routing and mediation rules in a variety of domain-specific languages, including a Java-based fluent API, Spring or Blueprint XML configuration files, and a Scala DSL.
- [HAProxy](http://www.haproxy.org/): Reliable, high Performance TCP/HTTP load balancer.
- [OpenResty](https://openresty.org/): Fast web application server built on top of Nginx.
- [Tengine](http://tengine.taobao.org/): A distribution of Nginx with some advanced features.
- [Tyk](https://tyk.io/): Open-source, fast and scalable API gateway, portal and API management platform.
- [Vulcand](https://github.com/vulcand/vulcand): Programmatic load balancer backed by Etcd.
- [Zuul](https://github.com/Netflix/zuul): An edge service that provides dynamic routing, monitoring, resiliency, security, and more.
- [Kong](https://getkong.org/): An open-source management layer for APIs, delivering high performance and reliability.
- [Janus](https://github.com/hellofresh/janus): A lightweight API Gateway written in Go by [Hello Fresh](https://engineering.hellofresh.com).
- [fabio](https://github.com/fabiolb/fabio): A fast, modern, zero-conf load balancing HTTP(S) router for deploying microservices managed by [consul](https://www.consul.io) by eBay.
- [Traefik](https://github.com/containous/traefik): Træfik (pronounced like traffic) is a modern HTTP reverse proxy and load balancer written in Go.
- [Oathkeeper](https://github.com/ory/oathkeeper): OIdentity & Access Proxy (IAP) that authorizes HTTP requests based on sets of rules. Integrates with ORY Hydra. 

## API Security
- [Online OpenAPI/Swagger File Security Audit](https://apisecurity.io/tools/audit/): Free online static analysis of API contract files. Upload the file and get the report.
- [API Security checklist](https://github.com/shieldfy/API-Security-Checklist): Checklist of the most important security countermeasures when designing, testing, and releasing your API.
- [Ory Hydra](https://github.com/ory/hydra): OAuth2 server with OpenID Connect written in Go.

## API Web Scanners
- [Cherrybomb](https://github.com/blst-security/cherrybomb): Stop half-done API specifications! Cherrybomb is a CLI tool that helps you avoid undefined user behaviour by validating your API specifications.

## API Monitoring
- [Runscope](https://www.runscope.com/): API Performance Monitoring.
- [Ping-API](https://ping-api.com/): Automated API Testing.
- [Streamdal](https://streamdal.com): A tool to embed privacy controls in your application code to detect PII as it enters and leaves your systems, preventing it from reaching unintended APIs, databases, data streams, or pipelines.

## API Testing
- [Assertible](https://assertible.com): Continuously test and monitor your APIs after deployments and across environments.
- [Hurl](https://github.com/Orange-OpenSource/hurl): Hurl makes it easy to test HTML content, REST / SOAP / GraphQL APIs, or any other XML / JSON based APIs.
- [Pyresttest](https://github.com/svanoort/pyresttest): YAML based REST testing and API microbenchmarking tool
- [OWASP Zaproxy](https://github.com/zaproxy/zaproxy): A tool to test your API for known security vulnerabilities, with a great CI integration.
- [RestQA](https://github.com/restqa/restqa): Microservice API Testing tool focused on providing a great developer experience.
- [Optic CI](https://www.useoptic.com/docs/diff-openapi): Test for breaking API changes in CI Pipelines

## API Developer Portal
- [Tyk](https://tyk.io/features): API Developer Portal on top of API gateway, make your API gateway easier to be used by developers.
- [APIMATIC](https://apimatic.io/developer-experience-portal): Instantly build an API Portal with SDKs, Live Code Samples, Test Cases, API Transformation and language specific Docs & Reference - tailored for your API.
- [Optic Docs](https://www.useoptic.com): Share verified-accurate OpenAPI documentation with your consumers. With Optic they can subscribe to your API and get notified when it changes. 


## JSON Format Standards
- [HAL](http://stateless.co/hal_specification.html)
- [JSONAPI](http://jsonapi.org/faq/)
- [JSON Schema](http://json-schema.org/)
- [Hydra](http://www.hydra-cg.com/)
- [Ion](https://github.com/ionwg/ion-doc)
- [JSON-LD](https://json-ld.org/)

## Learning Resources
- [REST in Practice](http://shop.oreilly.com/product/9780596805838.do)
- [Roy Fielding's dissertation on REST](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)
- [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
- [How to Design a REST API](https://blog.octo.com/en/design-a-rest-api/)
- [Automated API Development](https://yos.io/2016/04/27/automated-api-development/)
- [Nordic APIs](http://nordicapis.com/)
- [Undisturbed REST](https://www.mulesoft.com/sites/default/files/resource-assets/ebook-UndisturbedREST_v1.pdf)
- [Build APIs You Won't Hate](https://leanpub.com/build-apis-you-wont-hate)
- [Irresistible APIs](https://www.manning.com/books/irresistible-apis)
- [How to build an API](https://apiary.io/how-to-build-api)
- [API University](https://www.programmableweb.com/api-university)
- [RESTful Web Services](http://shop.oreilly.com/product/9780596529260.do)
- [RESTful Web APIs](http://shop.oreilly.com/product/0636920028468.do)
- [The Ten Essentials for Good API Documentation](https://alistapart.com/article/the-ten-essentials-for-good-api-documentation)
- [APIsecurity.io weekly newsletter](https://apisecurity.io)
- [Testing Web APIs](https://www.manning.com/books/testing-web-apis)
- [The Design of Web APIs, Second Edition](https://www.manning.com/books/the-design-of-web-apis-second-edition)

## Blogs
- [API Evangelist](http://apievangelist.com/blog/)

## References
- [HTTP Status Codes Reference](https://httpstatuses.com/)

## Contributing
[Pull Requests](https://github.com/yosriady/api-development-tools/pulls) are most welcome!

Please write a brief one-sentence summary when adding a new resource.

## Thanks
**api-development-tools** © 2016+, Yos Riady. Released under the [MIT] License.<br>
Authored and maintained by Yos Riady with help from contributors ([list][contributors]).

> [yos.io](https://yos.io) &nbsp;&middot;&nbsp;
> GitHub [@yosriady](https://github.com/yosriady)

[MIT]: https://mit-license.org/
[contributors]: https://github.com/yosriady/api-development-tools/contributors
