# Edge Computing

Defenition : Simply we can say method of optimising cloud computing systems by performing data processing at the edge of the network, near the source of the data.

Depending on the implementation, time-sensitive data in an edge computing architecture may be processed at the point of origin by an intelligent device or  sent to an intermediary server located in close geographical proximity to the client.  Data that is less time sensitive is sent to the cloud for historical analysis, big data analytics and long-term storage.

Transmitting massive amounts of raw data over a network puts tremendous load on network resources. In some cases, it is much more efficient to process data near its source and send only the data that has value over the network to a remote data center. Instead of continually broadcasting data about the oil level in a car's engine, for example, an automotive sensor might simply send summary data to a remote server on a periodic basis. Or a smart thermostat might only transmit data if the temperature rises or falls outside acceptable limits. Or an intelligent Wi-Fi security camera aimed at an elevator door might use edge analytics and only transmit data when a certain percentage of pixels significantly change between two consecutive images, indicating motion.

Edge computing can also benefit remote office/branch office (ROBO) environments and organizations that have a geographically dispersed user base. In such a scenario, intermediary micro data centers or high-performance servers can be installed at remote locations to replicate cloud services locally, improving performance and the ability for a device to act upon perishable data in fractions of a second. Depending upon the vendor and technical implementation, the intermediary may be referred to by one of several names including edge gateway, base station, hub, cloudlet or aggregator.

A major benefit of edge computing is that it improves time to action and reduces response time down to milliseconds, while also conserving network resources. The concept of edge computing is not expected to replace cloud computing, however. Despite its ability to reduce latency and network bottlenecks, edge computing can pose significant security, licensing and configuration challenges.

![image](https://user-images.githubusercontent.com/22645009/27769534-46e18600-5f2c-11e7-9cfd-77a438825b57.png)


Security challenges: Edge computing's distributed architecture increases the number of attack vectors. The more intelligence an edge client has, the more vulnerable it becomes to malware infections and security exploits.

Licensing challenges: Smart clients can have hidden licensing costs. While the base version of an edge client might initially have a low ticket price, additional functionalities may be licensed separately and drive the price up.

Configuration challenges: Unless device management is centralized and robust, administrators may inadvertently create security holes by failing to change the default password on each edge device or neglecting to update firmware in a consistent manner, causing configuration drift.

The name "edge" in edge computing is derived from network diagrams; typically, the edge in a network diagram signifies the point at which traffic enters or exits the network. The edge is also the point at which the underlying protocol for transporting data may change. For example, a smart sensor might use a low-latency protocol like MQTT to transmit data to a message broker located on the network edge, and the broker would use the hypertext transfer protocol (HTTP) to transmit valuable data from the sensor to a remote server over the Internet.

The OpenFog consortium uses the term fog computing to describe edge computing. The word "fog" is meant to convey the idea that the advantages of cloud computing should be brought closer to the data source. (In meteorology, fog is simply a cloud that is close to the ground)


