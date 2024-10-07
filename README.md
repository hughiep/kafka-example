# Kafka example

## Problem

A ride-sharing application needs to process real-time location updates from drivers and passengers to match them efficiently. The system should handle high throughput and low latency to ensure a smooth user experience.

## Solution

We can use Kafka to build a real-time location tracking system. Drivers and passengers can send their location updates to Kafka topics. A Kafka consumer can process these updates and match drivers with passengers in real-time. The system can scale horizontally by adding more Kafka brokers and consumers to handle high throughput.

