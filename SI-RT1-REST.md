# Reading Task 1: REST

## 1. What exactly is REST? How does the context of it fits to the title of the dissertation?

REpresentational State Transfer is a hybrid architectural style for distributed hypermedia systems derived from several of the network-based architectural styles.

**Client-Server**: separation of concerns is the principle behind the client-server constraint. By separating the user interface from the data storage, we improve the portability of the user interface across multiple platforms and scalability by simplifying the server components. Significant for the Web, the separation allows the components to evolve independantly and therefore supports the internet-scale requirement of muliple organizational domains.  
**Stateless**: communication must be stateless, such that each request from client to server must contain all of the information necessary to understand the request and can't take advantage of any stored contex on the server, session state is therefore kept entirely on the client. This constraint induces the properties of visibility, reliability and scalability. Visibility is improved becasue a monitoring system doesn't have to look beyond a single request in order to determine the request. Reliability is improved because it eases the task of recovering from partial faliures. Scalability is improved by not having to store state between requests, which allows the server component to quickly free resources and further simplifies implementation beacuse the server doesn't have to manage resource usage across requests. The disadvantages is that it may decrease network performance by increasing the repetitive data with each request since that data can't be left on the server in a shared context. In addition, placing the application state on the client-side reduces the server's control over consistent application behavior since the application becomes dependant on the correct implemantaion of semantics across muliple client versions.
**Cache**: 

## 2. Why is the dissertation considered so important for the software-architectural world?

## 3. Which is the most valuable outcome you personally get from it?

## 4. How could you implement it in your own practice as a software developer?
