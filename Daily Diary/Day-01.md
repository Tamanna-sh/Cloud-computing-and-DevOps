# Day 1 (31/06/26)

today we started with cloud computing and devops training, got intro about the three main cloud platforms which are AWS, GCP and AZURE, these are the major cloud providers everyone uses for hosting and running applications on cloud instead of buying own servers.

then learned about the advantages of cloud like autoscaling, this means the resources automatically increase or decrease depending on how much traffic or load is coming, so we dont have to manually add servers when load increases. also pay per use which means we only pay for whatever resources we actually use, no need to invest in big hardware upfront like in traditional systems.

after that discussed the difference between standalone, client server, distributed and cloud computing:
- standalone is when one single computer does all the processing alone, no network needed
- client server is when client sends request and server gives response, like browser requesting a website
- distributed is when multiple computers work together as one system to share the load and processing
- cloud is basically on demand computing resources given by a third party company over internet, mostly built on top of distributed systems only

also covered a diagram of how cloud application works:

user → internet → cloud → application → database

so basically user sends request through internet, it goes to cloud, cloud forwards it to application, application talks to database and gets the data back and shows to user.

overall day 1 was about basics, getting to know what cloud computing actually is and why everyone is shifting to cloud instead of normal servers, next classes probably will go deeper into AWS GCP AZURE individually and then devops tools like docker, kubernetes, ci/cd etc.
