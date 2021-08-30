# AWS: API, Dynamo and Lambda

### Review, Research, and Discussion

1. **What are serverless functions?**

Conventionally, serverless functions are single-purpose, programmatic functions that are hosted on managed infrastructure. These functions, which are invoked through the Internet, are hosted and maintained by cloud computing companies.

2. **If you were to create a system that emulated Lambda functions, how would you do it?**

* Open the Functions page on the Lambda console.

* Choose Create function.

* Under Basic information, do the following:

    * For Function name, enter my-function.

    * For Runtime, confirm that Node.js 14.x is selected. Note that Lambda provides runtimes for .NET (PowerShell, C#), Go, Java, Node.js, Python, and Ruby.

* Choose Create function.

3. **Describe how a CDN works**

To minimize the distance between the visitors and your website’s server, a CDN stores a cached version of its content in multiple geographical locations (a.k.a., points of presence, or PoPs). Each PoP contains a number of caching servers responsible for content delivery to visitors within its proximity.

In essence, CDN puts your content in many places at once, providing superior coverage to your users. For example, when someone in London accesses your US-hosted website, it is done through a local UK PoP. This is much quicker than having the visitor’s requests, and your responses, travel the full width of the Atlantic and back.

This is how a CDN works in a nutshell. Of course, as we thought we needed an entire guide to explain the inner workings of content delivery networks, the rabbit hole goes deeper.

****

# Document the following Vocabulary Terms

* **Serverless Functions**

                A serverless function is a programmatic function written by a software developer for a single purpose. It's then hosted and maintained on infrastructure by cloud computing companies. These companies take care of code maintenance and execution so that developers can deploy new code faster and easier.

* **Cloud Storage**

        Cloud storage is a way for businesses and consumers to save data securely online so that it can be accessed anytime from any location and easily shared with those who are granted permission.

* **CDN**

            A content delivery network, or content distribution network (CDN), is a geographically distributed network of proxy servers and their data centers. The goal is to provide high availability and performance by distributing the service spatially relative to end users.