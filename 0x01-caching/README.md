What Is Caching?
Cache (pronounced “cash”) is a type of computing memory used to improve the speed at which we access frequently requested data. Caching improves performance, efficiency and the user experience.
What Is Caching?
In computing, the term “caching” refers to storing frequently accessed data temporarily in a faster memory or storage. This process improves performance by reducing the time and resources needed to fetch data from its main source. When data is cached, users can access the data faster than if it needed to come from slower storage, such as a disk or over the network.

When a program needs to access particular data, it first checks the cache to see if the data is available. If yes, then we call that a cache hit, otherwise it’s a cache miss. In the case of a cache hit, the data is returned to the user from the cache. Otherwise, the program fetches the data from the main source, which typically takes longer.

How Does Caching Work?
When a program needs data, it first checks the cache memory. If the program finds the data there, it retrieves the data quickly since cache is designed for fast access. If the data is not there, then it fetches the data from the main storage, such as a file or a webpage. Finally, the program sends a request to the server to retrieve that data and stores a copy in the cache for future use.

Cache has limited space. If there is no room for the new data the program uses cache replacement policy to remove older data from the cache to make room for the new data. For example, least recently accessed or least frequently used data may be removed. In some cases, cached data may need to be invalidated if it’s no longer relevant to ensure cache accuracy.
Types of Caching
There are several different types of cache used in computer systems. Here are some examples.

Disk Cache
This buffer cache is used in hard drives and solid-state drives to temporarily store recently accessed data from the disk while also improving read and write performance.

Browser Cache
Web browsers store images, scripts and style sheets locally to speed up page load time on subsequent visits.

DNS Cache 
Domain Name System, or DNS, servers maintain cache of domain name to IP addresses mapping. For example, if the domain name is Dropbox.com, it’s translated to an IP address like 162.125.1.18. This mapping from domainname<>ipaddress gets stored in DNS cache. When the next hit comes, the program won’t need to go to the main server to find the IP address for a domain.
Application Cache
Some applications, such as database systems and web servers, implement custom caching to store frequently accessed data or query results to improve application responsiveness.

CPU Cache
Caching was initially invented to speed up code and data access by the CPU, or computer processing unit. The L1 cache, located on the CPU chip, is useful for frequently used code instructions and data to stop programs constantly fetching from the slower memory. The larger L2 cache serves as secondary storage, and is located closer to the CPU than the main memory. Finally, an even larger L3 cache can be shared among multiple CPU cores for frequently accessed data across those cores.

Benefits of Caching
Faster Data Access: Caching can significantly reduce response time to access frequently requested data. 
Improved Performance: Lower data access latency improves overall computing performance by allowing applications to execute tasks quickly. 
Resource Usage and Scalability: By reducing the load on the main data source, caching helps reduce resource usage, including lower CPU usage, disk I/O and network traffic. This makes the system more efficient and scalable.
Offline Access: In some cases, caching allows users to access data or content offline, such as cached web page elements. This improves user experience for those with limited connectivity.
Cost Savings: Due to lower resource usage and higher scalability, caching saves the cost of maintaining the main data source.
 
Caching Use Cases
Besides the types of caching described above, there are many other use cases that demonstrate the benefits of caching.
CDNs
Content Delivery Networks, or CDNs, cache static content such as images, videos and installation files across distributed edge servers located closer to users. This process reduces latency, improves speed and saves on costs for data access across geographically distributed audiences.
Session Caching
Session caching stores session data, including user authentication tokens during user sessions. This speeds up user interactions in web applications.
Operating Systems
Operating systems and file systems use caching to store recently accessed files or file metadata. This accelerates file read/write performance and reduces disk access to improve speed.
Search Engines
Search engines cache search results and indexed web pages to deliver faster search query responses.