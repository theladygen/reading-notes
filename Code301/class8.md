# Class 8

## Reading

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1.***What does REST stand for?***

REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP. However, most common REST API implementations use HTTP as the application protocol.

2.***REST APIs are designed around a ____.***

REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

3.***What is an identifier of a resource? Give an example.***

An identifier is a URI that uniquely identifies that resource. Ex: `http://randomurl/customers`

4.***What are the most common HTTP verbs?***

`GET`, `POST`, `PUT`, `PATCH`, and `DELETE`

5.***What should the URIs be based on? Give an example of a good URI.***

When possible, resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

6.***What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?***

All web requests impose a load on the web server. The more requests, the bigger the load. Therefore, try to avoid "chatty" web APIs that expose a large number of small resources. A 'chatty' web API is a bad thing.

7.***What status code does a successful GET request return?***

A successful GET method typically returns HTTP status code 200 (OK).

8.***What status code does an unsuccessful GET request return?***

If the resource cannot be found, the method should return 404 (Not Found). If the request was fulfilled but there is no response body included in the HTTP response, then it should return HTTP status code 204 (No Content).

9.***What status code does a successful POST request return?***

If a POST method creates a new resource, it returns HTTP status code 201 (Created).

10.***What status code does a successful DELETE request return?***

If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content).

## Bookmark and Review

[RegExr - Pay particular attention to the cheatsheet](https://regexr.com/)

[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

[Regex 101](https://regex101.com/)

## Things I Want to Know More About

### ***Answers to questions were found researching and using the sources linked above each section***

[CF Reading Journal Home](../README.md)
