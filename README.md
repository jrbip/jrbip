# Glossary of Techical Terms

<hr style="color: blue;"><br>

<span style="font-size: 140%;">Table of Contents</span>

- [Glossary of Techical Terms](#glossary-of-techical-terms)
  - [API: Application Programming Interface](#api-application-programming-interface)
  - [API vs Webhook](#api-vs-webhook)
  - [Composite API](#composite-api)
  - [cURL](#curl)
  - [DOM](#dom)
  - [Internal API (Private API)](#internal-api-private-api)
  - [JSON-RPC](#json-rpc)
  - [Open API (Public API)](#open-api-public-api)
  - [Partner API](#partner-api)
  - [REST API](#rest-api)
  - [SOAP API](#soap-api)
  - [Web API](#web-api)
  - [Webhook](#webhook)
  - [Webhook APIs](#webhook-apis)
  - [Webhook Endpoint](#webhook-endpoint)
  - [Web Service](#web-service)
  - [XML-RPC](#xml-rpc)
## API: Application Programming Interface

<small><i>APIs are application interfaces, meaning that one application is able to interact with another application in a standardized way.</i></small>


1.  An API is a set of definitions and protocols that allow technology products and services to communicate with each other via the internet.
2.  An API allows your application to interact with an external service using a simple set of commands.
3.  An API allows two software programs to communicate with each other. One program can call another program’s API to get access to data or functionality of the other program.


## API vs Webhook

-   Although webhooks and APIs are similar in the sense that they help applications interact and share information, they are not synonymous. Typically, applications communicate and interact in two ways; through APIs and webhooks.

-  An API allows apps to gets data through what is known as polling. This means that for an app to get new information or notification from a server-side app, they must make requests periodically.

-  On the other hand, a webhook allows an app to get data through pushing. This means that the app receives data automatically when an event occurs on the server-side app. this is the reason as to why webhooks are sometimes dubbed “reversed API.

-  In simple terms, an API gets data through periodic requests, while a webhook gets data automatically. Webhooks saves you time by helping you avoid polling for new updates.

## Composite API

1.  These APIs combine different data and service APIs. It is a sequence of tasks that runs synchronously as a result of the execution and not at the request of a task. The main purpose of this type of API is to speed up the process of execution and improve the performance of the listeners in the web interfaces.


## cURL

1.  Curl is object-oriented programing software that is used to transfer data through a vast array of Internet Protocols for a given URL. It is a command-line utility that permits the transfer of files within the URL syntax. Curl is basically a client-side program which boasts commands that are designed in a way that they work to check connectivity to the URLs and facilitate data transfer.
2.  In the word cURL; ‘c’ stands for a client, while ‘URL’ indicates that curl works with URLs. This software supports various protocols including FTP, HTTPS, HTTPS, TELNET and SMT which makes it an ideal candidate for interacting with APIs.


## DOM

> **Document Object Model**

1.  The DOM (Document Object Model) is an API that represents and interacts with any HTML or XML document. The DOM is a document model loaded in the browser and representing the document as a node tree, where each node represents part of the document (e.g. an element, text string, or comment).
2.  The DOM provides the cerebral model for the programming interchange, which can be cultivated in any way the implementation mechanism deems fit. DOM does not mandate over the manner in which the documents shall be implemented.


## Internal API (Private API)

1.  These APIs are usually meant for use within a company and are only exposed by internal systems. A company can use this type of API across different internal teams to be able to improve its products and services.


## JSON-RPC

1.  A common type of web service API. This protocol is similar to XML-RPC, but instead of using an XML format to transfer the data it uses JSON.

## Open API (Public API)

1.  These APIs are publicly available and there are no restrictions to access them.


## Partner API

1.  These APIs are not publicly available, so you need specific rights or licenses to access them.

## REST API

> **Representational State Transfer**

*REST APIs are a standardized architecture for building web APIs using HTTP methods.*


1.  REST is not a protocol like the other web services. Instead, it is a set of architectural principles. The REST service needs to have certain characteristics, including simple interfaces, which are resources identified easily within the request and manipulation of resources using the interface.
2.  Therefore a REST API is an application program interface that is backed by the architectural style of REST. It refers to tools, service or software that is based on the REST architectural principle. Although REST can be used on nearly any protocol, they take advantage of HTTP when used for web APIs. The primary advantage of REST APIs is that they offer more flexibility. In REST APIs, data is not constrained to resources or methods. Therefore, it can make multiple types of calls, return various data formats, and even change structurally with the appropriate implementation of hypermedia.

## SOAP API

> **Simple Object Access Protocol**

1.  This is a protocol that uses XML as a format to transfer data. Its main function is to define the structure of the messages and method of communication. It also uses WSDL (Web Service Definition Language) in a machine-readable document to publish a definition of its interface.
2.  SOAP (Simple Access Protocol) is a standard messaging or communication protocol system that allows processes that utilize various operating systems such as Windows and Linux to interact and communicate through HTTP and its XML. SOAP APIs are designed with the capability to create, update, recover and delete records such as passwords, leads, accounts, and custom objects. While Web API in the time of Web 1.0 was synonymous with SOAP-based web services, today in Web 2.0, the term SOAP is edging towards REST-style web resources.
 
## Web API

1.  Web API is basically an open-source framework that is used to write HTTP APIs. It refers to an API over the web which can be accessed using the HTTP protocol. It is important to note that it is a concept and not a technology. Developers can build Web API using a vast array of technologies such as .NET, and Java, among others. Web API can be RESTful or not. Web API implements protocol specification and thus it incorporates concepts like caching, URIs, versioning, request/response headers, and various content formats in it.


## Webhook

1.  Webhooks are API-like concepts that are being utilized to allow communication between applications.
2.  They can be considered to be automated messages that provide a server-side application with a mechanism to notify the client-side application when a new event occurs on the server. Webhooks allow you to receive real-time data from an app when an event happens. Web services use webhooks to provide other services with real-time information through HTTP POST when something happens.
3.  
## Webhook APIs

1.  
## Webhook Endpoint

1.  For a webhook to be operational, the client-side app must provide the server-side application with a URL. It is this URL that the server-side app calls when an event occurs. However, for the server-side to know to pass a message, the URL provided must contain an endpoint with a parameter that details the kind of event that should trigger an action. This is what is known as a webhook endpoint. It is the parameter in the URL that is provided by the third-party app to determines what type of event the server-side app can act on.

## Web Service

1.  A Web service is a way for two machines to communicate with each other over a network.
2.  Web services are a type of API, which must be accessed through a network connection.
## XML-RPC

1.  A common type of web service API. 
