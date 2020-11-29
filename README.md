# docker-nats-library

This is an npm module for listening and publishing to various events in the app.

## Supported events
1. post:created
2. post:deleted
3. feed:created
4. feed:updated
5. feed:deleted
6. vote:created
7. vote:updated

Each event should have a **Subject** and **data**.
