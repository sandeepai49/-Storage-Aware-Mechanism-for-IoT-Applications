# Storage Aware Mechanism for IoT Applications

This project implements a Storage Aware Mechanism (SAM) designed to improve data handling in Internet of Things (IoT) environments. It provides dynamic storage management by monitoring device storage conditions and adapting how data is stored, prioritized, or offloaded to edge/cloud systems.

## Overview

In IoT systems with limited local storage, it's essential to manage data efficiently to avoid performance degradation or data loss. This mechanism:

- Monitors available storage in real-time.
- Prioritizes or discards data based on importance and relevance.
- Offloads less critical data to edge or cloud storage when needed.
- Maintains smooth operation under resource constraints.

## Features

- Adaptive data retention based on current storage capacity
- Real-time storage monitoring
- Intelligent prioritization and cleanup of sensor data
- Support for integration with edge and cloud storage systems
- Lightweight implementation suitable for embedded devices

## Use Cases

- Smart homes and smart cities
- Environmental data logging and monitoring
- Industrial IoT systems
- Remote healthcare and wearable devices
- Agricultural sensor networks

## Technology Stack

- Programming Language: Python / C / C++ (customize as needed)
- Hardware: Raspberry Pi, ESP32, Arduino, or similar IoT devices
- Communication Protocols: MQTT, HTTP, or LoRa (as applicable)
- Storage: Local disk, Edge server, Cloud (AWS, Azure, GCP)

## Project Structure


