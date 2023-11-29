#!/bin/bash

# Queueing System In JavaScript

# This project involves creating a queueing system in JavaScript for learning purposes.

## Task 0: Install a Redis instance

# Download, extract, and compile the latest stable Redis version (higher than 5.0.7).
wget http://download.redis.io/releases/redis-6.0.10.tar.gz
tar xzf redis-6.0.10.tar.gz
cd redis-6.0.10
make MALLOC=libc # for Linux systems
# make MALLOC=jemalloc # for Mac OS X systems

# Start Redis in the background with src/redis-server.
# Ensure server is working with a ping src/redis-cli ping.
# Use Redis client to set the value School for the key Holberton.

# Copy dump.rdb from redis-6.0.10 directory into the root of this project.

## Task 1: Node Redis Client

# - Install node_redis using yarn or npm.
# - Write a script 0-redis_client.js that connects to the Redis server and logs connection status.

## Task 2: Node Redis client and basic operations

# - Create 1-redis_op.js based on 0-redis_client.js.
# - Add setNewSchool and displaySchoolValue functions as described.
# - Call the functions as specified at the end of the file.

## Task 3: Node Redis client and async operations

# - Create 2-redis_op_async.js based on 1-redis_op.js.
# - Modify displaySchoolValue function to use async/await with promisify.

## Task 4: Node Redis client and advanced operations

# - Create 4-redis_advanced_op.js.
# - Store hash values using hset and display the stored object using hgetall.

## Task 5: Node Redis client publisher and subscriber

# - Create 5-subscriber.js and 5-publisher.js.
# - Subscriber listens to a channel and logs received messages.
# - Publisher sends messages to the same channel.

# Continue with tasks 6 to 13 in a similar manner as per project specifications.
# Ensure to use appropriate Redis client commands and node operations for each task.
# Tasks involve creating jobs, queues, and handling various scenarios using Kue and Redis.

# Modify each file with the specified functionality, ensuring proper logging and error handling.

# End of README

