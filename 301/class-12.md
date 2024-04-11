## Class 12 Reading Notes:

1. 100s: These are the servers giving the client a status update. 200s: These tell the client that the request has been accepted. 300s: These are the servers telling the client that the information requested is not in the requested location. 400s: These are the servers telling the client that the request is invalid. 500s: These indicate something went wrong on the server.
2. 202 means the request is valid and processing is in progress.
3. 308: This means the request endpoint is no longer available, and the client needs to be redirected.
4. 204 No Content codes indicate an update that didn’t return data to the client.
5. 308 can be used if a resource used to exist but no longer does.
6. 403 Forbidden means that authorization is not necessary, but the client still does not have permission to access the resource.
7. The MongoDB string needs to be in the .env because we don’t want users to access that information.
8. Middleware is the software that facilitates communication.
9. The "/:id" is simply a placeholder that will be replaced with a variable when the request is made.
10. PUT updates a whole resource, while PATCH only updates part of a resource.
11. You can create a default schema by writing it in your code and then exporting it.
12. A 500 code means something is wrong on the server.
13. 200 indicates a resource returned, and 201 indicates a resource created.



### Things I want to know more about:
Is PATCH more efficient than PUT since it is only a partial update?



