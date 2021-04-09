# API Exposure check policy

If you are using the API management solution primarily for an API-centric architecture, then it makes sense to place the API management solution on the internal network. 
Nevertheless, there is very often the requirement that some of the APIs must be made securely available on the Internet as a public API. 
For this you can build an API security layer based on API gateways. This layer is the edge defense for all incoming Internet API traffic.
The following architecture represents this concept.

![Two-Layer Architecture](imgs/two-layer-architeture.png)
