# About this project
This project utilizes [EvenSim](https://github.com/Interana/eventsim), an open-source tool, to generate user events and subsequently send them to Kafka. EvenSim allows for the creation of simulated user events for analysis and data processing purposes.

Once the user events are generated, the project sends them to Apache Kafka, a distributed event streaming platform. Kafka facilitates the reception and storage of events within a distributed and high-performance system.

Next, the project leverages ksqldb, a real-time stream processing database, to process the data streams from Kafka. Ksqldb provides powerful tools for real-time stream processing and extracting meaningful insights from the data.

The processed data is then stored in ClickHouse, a distributed database designed for data analytics. ClickHouse supports high-speed data storage and querying, making it an ideal choice for applications requiring large-scale and real-time data processing.

Finally, to visualize and explore the data, the project utilizes Grafana, an open-source tool for data visualization and customizable dashboards. Grafana offers flexible charts, graphs, and dashboards to display the data from ClickHouse in a visual and understandable manner.

For deployment and management of the entire system, the project relies on Docker, a container-based virtualization platform. Docker enables lightweight packaging and deployment of applications while ensuring consistency and ease of scaling the system.