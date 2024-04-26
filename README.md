# Understanding URLs and HTTP Basics

This repository aims to provide a beginner-friendly explanation of fundamental concepts related to URLs and HTTP.

## Table of Contents

1. [What is a URL?](#what-is-a-url)
2. [What is HTTP?](#what-is-http)
3. [How to Read a URL](#how-to-read-a-url)
4. [Understanding the Components of an HTTP URL](#understanding-the-components-of-an-http-url)
5. [What is a Domain Name?](#what-is-a-domain-name)
6. [What is a Sub-Domain?](#what-is-a-sub-domain)
7. [Defining Port Numbers in a URL](#defining-port-numbers-in-a-url)
8. [Understanding Query Strings](#understanding-query-strings)
9. [What is an HTTP Request?](#what-is-an-http-request)
10. [What is an HTTP Response?](#what-is-an-http-response)
11. [Understanding HTTP Headers](#understanding-http-headers)
12. [The HTTP Message Body](#the-http-message-body)
13. [HTTP Request Methods](#http-request-methods)
14. [HTTP Response Status Codes](#http-response-status-codes)
15. [What is an HTTP Cookie?](#what-is-an-http-cookie)
16. [Making Requests with cURL](#making-requests-with-curl)
17. [Application Level: What Happens When You Type google.com in Your Browser](#application-level-what-happens-when-you-type-googlecom-in-your-browser)

## What is a URL?

A URL (Uniform Resource Locator) is a reference to a web resource that specifies its location on the internet. It typically consists of several components, including the protocol, domain name, path, and optional query parameters.

## What is HTTP?

HTTP (Hypertext Transfer Protocol) is the underlying protocol used for communication on the World Wide Web. It governs how web clients (such as browsers) request resources from web servers and how servers respond to those requests.

## How to Read a URL

Reading a URL involves understanding its various components, such as the protocol (e.g., HTTP or HTTPS), domain name, path, query parameters, and fragment identifier.

## Understanding the Components of an HTTP URL

An HTTP URL comprises several components, including the scheme (HTTP or HTTPS), domain name, optional port number, path, query parameters, and fragment identifier.

## What is a Domain Name?

A domain name is a human-readable label that represents the numerical IP address of a web server. It allows users to access websites using easily memorable names instead of numeric IP addresses.

## What is a Sub-Domain?

A sub-domain is a subset of a larger domain, typically used to organize and navigate a website's content or services. It precedes the main domain name in a URL and is separated by a dot.

## Defining Port Numbers in a URL

Port numbers in a URL specify the endpoint through which communication occurs on a web server. They are separated from the domain name by a colon and are optional if using default ports (e.g., 80 for HTTP, 443 for HTTPS).

## Understanding Query Strings

A query string is a part of a URL that contains data to be passed to the server as key-value pairs. It follows the path component and is preceded by a question mark.

## What is an HTTP Request?

An HTTP request is a message sent by a client (e.g., a web browser) to a server, requesting a specific action or resource.

## What is an HTTP Response?

An HTTP response is a message sent by a server to a client in response to an HTTP request. It contains the requested resource along with additional metadata.

## Understanding HTTP Headers

HTTP headers are additional pieces of information sent along with an HTTP request or response. They provide details about the message, such as the content type, encoding, and authentication credentials.

## The HTTP Message Body

The HTTP message body contains the data being sent in an HTTP request or response. It can include HTML content, file attachments, or other types of data.

## HTTP Request Methods

HTTP request methods specify the type of action to be performed on a resource. Common methods include GET, POST, PUT, DELETE, and PATCH.

## HTTP Response Status Codes

HTTP response status codes indicate the outcome of an HTTP request. They range from informational codes (1xx) to success (2xx), redirection (3xx), client errors (4xx), and server errors (5xx).

## What is an HTTP Cookie?

An HTTP cookie is a small piece of data sent from a website and stored on the user's device by the web browser. It is commonly used for session management, user authentication, and personalization.

## Making Requests with cURL

cURL is a command-line tool for transferring data using various protocols, including HTTP. It allows users to make HTTP requests from the terminal and inspect the responses.

## Application Level: What Happens When You Type google.com in Your Browser

When you type "google.com" in your browser, the browser initiates an HTTP request to the Google web server, requesting the homepage. The server responds with an HTTP response containing the HTML content of the homepage, which the browser then renders for the user to see.
