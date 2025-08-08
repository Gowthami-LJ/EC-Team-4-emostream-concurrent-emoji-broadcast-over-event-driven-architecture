# EC-Team-4-emostream-concurrent-emoji-broadcast-over-event-driven-architecture

 EmoStream is a real-time system that captures, processes, and broadcasts billions of emoji reactions during live sporting events. It enhances viewer engagement by reflecting crowd sentiment instantly — for example, showing surges of cheering or celebration emojis when a player hits a boundary or takes a wicket.

The system uses Apache Kafka for high-throughput messaging and Apache Spark Streaming for real-time data processing in 2-second micro-batches. Incoming emoji data is aggregated to reduce noise (e.g., 1000 similar emojis count as 1) and is then delivered to connected clients using a Publisher-Subscriber model. This architecture ensures low latency, high concurrency, and scalability for large audiences.

Designed for platforms like Hotstar, EmoStream ensures seamless user interaction even with millions of concurrent connections, making real-time audience sentiment visualization both scalable and efficient.

## Architecture

![Architecture Diagram] (https://github.com/Gowthami-LJ/EC-Team-4-emostream-concurrent-emoji-broadcast-over-event-driven-architecture/blob/main/Architecture%20Diagram.png?raw=true)
