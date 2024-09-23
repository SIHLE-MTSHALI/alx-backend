# 0x03. Queuing System in JS

This project implements a queuing system in JavaScript using Redis and Node.js. It covers various concepts including working with Redis, using Node Redis client, queuing with Kue, and building an Express app interacting with Redis server.

## Files

- `0-redis_client.js`: Redis client connection
- `1-redis_op.js`: Redis operations
- `2-redis_op_async.js`: Async Redis operations
- `4-redis_advanced_op.js`: Advanced Redis operations
- `5-subscriber.js`: Redis subscriber
- `5-publisher.js`: Redis publisher
- `6-job_creator.js`: Job creator with Kue
- `6-job_processor.js`: Job processor with Kue
- `7-job_creator.js`: Job creator with array of jobs
- `7-job_processor.js`: Job processor with progress tracking
- `8-job.js`: Job creation function
- `8-job.test.js`: Tests for job creation function
- `9-stock.js`: Express app with Redis for stock management
- `100-seat.js`: Express app with Redis and Kue for seat reservation system

## Setup

1. Install Redis
2. Install Node.js dependencies:

npm install
