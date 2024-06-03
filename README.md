# server-load-testing


## Requirements

### Retrieve and store data in different DB

- Retrieve and store data in Postgresql DB
- Retrieve and store data in Mongo DB
- Retrieve and store data in Redis

### Cache

- There will be a cache (in-memory) in the server which will use map to retrieve and store data

### Load Testing

#### Asynchronous

- 1000 request in the server and see the response time of different databases

#### Synchronous

- 1000 request in the server and see the response time of different databases

### Endpoints

- GET, POST endpoints for each database and cache
- One endpoint for seed data
