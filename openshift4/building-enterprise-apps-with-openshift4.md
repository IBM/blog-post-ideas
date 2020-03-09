## RedHat OpenShift 4.3 on IBM Cloud

RedHat OpenShift continues to evolve. As our [history of Kubernetes, and OpenShift](https://developer.ibm.com/blogs/a-brief-history-of-red-hat-openshift/) blogpost concluded, the recent V4 release of OpenShift V4 is _the_ well considered contemporary enterprise platform, for creating apps on today, and for the decade ahead.

We're excited that OpenShift 4.3 is [now available on IBM Cloud]().

In this blog post I highlight some of the new features of OpenShift 4, and introduce a new collection of developer resources here on the IBM Developer website, that explore those features, while digging into considerations for building secure, privacy conscious applications with container technology.

### What's new in OpenShift V4?

IBM Cloud is updating from OpenShift V 3.11 to OpenShift V 4.3. Now, OpenShift is even more packed with enterprise developer features, a few of which I'll highlight below:


![Open Shift 4 Layers](./openshift4.png)


#### Operator Hub

The [Operator Framework](https://github.com/operator-framework) is an open source toolkit to manage Kubernetes native applications, called Operators, in an effective, automated, and scalable way. OpenShift 4 has been re-architected around Operators. Where Kubernetes enabled developers to methodically 'containerize' applications, Operators enable developers to automate the management of related components of an application, for instance databases, or other stateful elements, in a consistent, repeatable and scalable way.

In addition, to Operators becoming part of Kubernetes fabric in OpenShift 4, RedHat have introduced a marketplace for finding Operators that can accellerate development of an application. This new [Operator Hub](https://operatorhub.io/) is also part of OpenShift. You can find out more in our [Operator tutorial]()

#### OpenShift Service Mesh

Service Meshes can instill a consistent development approach, and infuse inter service communication with security among other features. I noticed that it is a choice approach for solving problems of scale, and order in big applications, and across large companies - from presentations at [KubeCon North America last year](https://www.youtube.com/watch?v=Z6aN3Smt-9M). 

OpenShift 4 has adopted [Istio](https://istio.io/), the emerging service mesh of choice for Kubernetes based systems, and based its own service mesh on that technology.

In addition, the lastest version of Istio offers helpful security features.

#### Openshift Serverless

#### OpenShift Pipelines

#### Enhanced Security






### The evolving world of privacy conscious applications



Our['Example Health' series](https://developer.ibm.com/series/systems-example-health-series/) thought about App Modernization. It used a simulated set of health record data and surfaced some micro-services built around it, and looked at a [Source To Image Example](). We shared that example to help show how to get started with OpenShift.

 This time, we wanted to elevate our thinking to some next steps in enterprise development ... by considering privacy and security on cloud and container based solutions.

### Building a customer loyalty app example

We've been working through 

At KubeCon Europe, I was inspired by a talk given by [] on GDPR. I stared
›