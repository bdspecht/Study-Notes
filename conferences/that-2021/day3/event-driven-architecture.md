### Building Event Driven Applications using Azure
* References
 [Slide Deck](https://github.com/DustinEwers/event-driven-arch-azure)
* What is event driven architecture?
* Distributed monolithic-microservices
 * Tightly coupled microservices
* Scenario 2
 * Payment Gateways
 * Binding Insurance Policies
 * Talking to Ancient Backend Systems
 * Reports
 * PDF/Video/Image Conversion
 * Batch Processes
* Scenario 3
 * History tacking is a must
 * Need to reduce conflicts from large numbers of potential users
* Components
 * Consumers
 * Producers
 * Message brokers
 * Events
* What is an event?
 * Defined in business terms
 * Notable thing that happens
 * Lightweight
 * Easily understand
  * Customer updated address
  * Customer submitted payment information
* Event patterns
 * Queues
 * Topics
 * Event sourcing
 * Event streaming
* Scaling with Queues
 * Load leveling
 * Alter processors to control flow rate
* Decoupling Apps with Topics
 * Promote loosely coupled architecture
 * Easy to add consumers later
* How to do it?
 * Azure
  * Azure service bus
   * Topics
   * Queues
  * Azure event grid
   * Orchestrate azure events
   * Pub/sub
 * Others
  * AWS Simple Notification Service
  * Rabbit MQ
 * Service Bus APIS
  * Azure.Messaging.ServiceBus (New)
  * Microsoft.Azure.ServiceBus
  * WindowsAzure.ServiceBus (Old)
* Service Bus Explorer
 * Azure provided tool for browsing messages and testing
* Event sourcing
 * Append only
 * Replay events for state
 * Materialized views
 * Easy to track history
* Event streaming
 * IOT
 * Telemetry
 * How to do it?
  * Azure
   * Azure IOT Hub
   * Azure Event Hub
  * Others
   * AWS Kinesis
   * Google Dataflow
   * Apache Kafka
* Pitfalls
 * Breaking the space-time continuum
  * Consistency problems
  * Event delivery problems
  * Multiple processing of events
 * Logging and tracking events
  * User action -> producer -> message broker -> event processor
 * Thundering Herd Problem
  * Consumers calling the same service for an event at the same time
 * Fallacies of Distributed Computing
  * The network is reliable
  * Latency is zero
  * Bandwidth is infinite
  * The network is secure
  * Topology doesn't change
  * There is one administrator
  * Transport is zero
