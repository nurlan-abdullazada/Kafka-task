# Kafka IoT Data Pipeline

End-to-end Kafka pipeline for processing IoT sensor data.

## Features
- 3-node Kafka cluster with Docker Compose
- Python producer generating IoT sensor data
- Python consumer for data processing  
- JSON serialization/deserialization
- Topic with 3 partitions and replication factor 3
- AKHQ web UI for monitoring

## Setup
```bash
docker-compose up -d
python iot_producer.py    # Terminal 1
python iot_consumer.py    # Terminal 2
