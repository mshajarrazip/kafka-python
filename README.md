# kafka-python

This repo contains a docker compose setup for a local kafka cluster,
and some artifacts for following the tutorials at
[Getting Started with Apache Kafka and Python](https://developer.confluent.io/get-started/python).

# Starting Up

1. This project runs on either Linux or WSL 2.
1. Initialize the environment & install the dependencies:
    ```
    pip install confluent-kafka
    ```
1. Run `docker compose up` to start the kafka clusters.
1. Run [consumer.py](consumer.py) ( monitor the output ):
    ```
    python consumer.py
    ```
1. Run producer.py:
    ```
    python producer.py
    ```

## References

1. [Getting Started with Apache Kafka and Python](https://developer.confluent.io/get-started/python).
1. [Quick Start for Confluent Platform](https://docs.confluent.io/platform/current/get-started/platform-quickstart.html#quickstart)