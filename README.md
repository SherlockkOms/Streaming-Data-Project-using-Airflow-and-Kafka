# Real-Time Streaming Project using Airflow, Kafka, and Docker

## Table of Contents
- [Introduction](#introduction)
- [System Architecture](#system-architecture)
- [Technologies Used and Learnings](#technologies-used-and-learnings)
- [Prerequisites](#prerequisites)
- [Installation and Setup](#installation-and-setup)
- [Usage and Workflow](#usage-and-workflow)
- [Contributing](#contributing)
- [Resources and Acknowledgments](#resources-and-acknowledgments)
- [Watch the Video Tutorial](#watch-the-video-tutorial)

## Introduction

This project is a deep dive into building an end-to-end data engineering pipeline, exploring each phase from data ingestion, through processing, to storage. It leverages a powerful tech stack including Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, Cassandra, all within a Dockerized environment for streamlined deployment and scalability.

## System Architecture

![System Architecture](Images/Architecture%20Diagram.png)

## Technology Stack and System Insights

The project integrates a robust suite of technologies, each playing a vital role in the data pipeline:

- **Apache Airflow & PostgreSQL**: Orchestrates the data pipeline and manages data storage. Airflow's scheduling and workflow automation capabilities are central to the project.
- **Apache Kafka & Zookeeper**: Kafka streams data in real-time, with Zookeeper ensuring distributed coordination, offering insights into high-throughput data pipelines and system synchronization.
- **Apache Spark**: Handles complex data processing tasks, showcasing distributed computing and large-scale data processing.
- **Cassandra**: Used for storing processed data, highlighting NoSQL database management and scalability.
- **Python**: Facilitates scripting and data manipulation, underscoring its versatility in various data engineering tasks.
- **Docker**: Containerizes the setup, providing a hands-on experience with deployment and orchestration.

The system's architecture, encompassing these technologies, ensures efficient data flow from the `randomuser.me` API through processing stages to final storage in Cassandra.


## Resources and Acknowledgments
- Inspired by CodeWithYu's insightful project video, available [here](https://www.youtube.com/watch?v=GqAcTrqKcrY).
