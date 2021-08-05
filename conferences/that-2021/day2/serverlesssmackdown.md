### Serverless Smackdown: Azure Functions, AWS Lambda, GCP
* Serverless computing
 * Does not mean "no" server, just someones else's server
 * Server resources are abstracted and less resources are used
  * Cloud provider takes care of creating and managing all resources
  * Charges for actual usage rather than the underlying infrastructure
* Uses event-based architecture
 * Execution of the code/app is triggered by an event (event consumer)
 * Examples of events
  * HTTP requests
  * File upload
  * Timed event
  * Database event
  * Streaming event
* Service categories
 * IaaS
 * PaaS
 * FaaS
 * SaaS
* PaaS vs FaaS
 * FaaS is similar to PaaS
 * FaaS uses fewer resources when compared to PaaS
  * An app on PaaS is running on at least 1 server
  * FaaS only runs when triggered
* Event-driven architecture
 * Producer -> Event processing hub -> Consumer
* Why not serverless computing
 * Pros
  * Reduces costs
  * Automatic scaling
  * Quick deployments
  * More resource efficiency
  * Reduced latency
 * Cons
  * Ramp-up time
  * Vendor lock-in
  * Debugging
  * Not for long running processes
  * Security?
    * Sharing servers, sharing network, etc
* Providers
 * AWS Lambda
 * Azure Functions
 * GCP Serverless
* Serverless computing statistics
 * [DZone](https://dzone.com/articles/the-state-of-serverless-computing-2021)
 * Runtimes
  * Node.js
  * Python
  * Go
  * Java
  * .NET
 * Serverless computing drivers
  * Scaling flexibility
  * Speed of development
  * Quicker software release
  * Performance
  * Event-driven architecture
  * Decreased system administration
  * Cost
