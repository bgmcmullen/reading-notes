## Class 08 Reading Notes:

1. What does REST stand for? REST stands for: Representational State Transfer.\
2. REST APIs are designed around resources.\
3. What is an identifier of a resource? Give an example. An identifier is a unique URI that links to that resource. The given example is: “https://adventure-works.com/orders/1”.\
4. What are the most common HTTP verbs? GET, POST, PUT, PATCH, and DELETE.\
5. What should the URIs be based on? Generally, URIs should be based on the resource and not on the operations.\
6. Give an example of a good URI. “https://adventure-works.com/orders”.\
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing? A “chatty” API gives a large number of small resources. This is NOT a good thing as it puts a load on the server.\
o “GET retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.”\
o “POST creates a new resource at the specified URI. The body of the request message provides the details of the new resource. Note that POST can also be used to trigger operations that don't actually create resources.”\
o “PUT either creates or replaces the resource at the specified URI. The body of the request message specifies the resource to be created or updated.”\
o “PATCH performs a partial update of a resource. The request body specifies the set of changes to apply to the resource.”\
o “DELETE removes the resource at the specified URI.”\
###Things I want to know more about:
	What other concerns are important when optimizing the efficiency of a webserver?
###Citation: 
Martinekuan. (n.d.). Web api design best practices - azure architecture center. Web API design best practices - Azure Architecture Center | Microsoft Learn. https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design 


