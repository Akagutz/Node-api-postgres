# swamp-events
> A nodejs bot that listens to event notifications on the database with Postgres
> event triggers and stream events to the frontend using the SSE api

## About
- Postgres event triggers with LISTEN/NOTIFY
- It only allows data reception from the server(unidirectional)
- The bot sends events by responding to the clients with the MIME type text/event-stream.
- The event stream is a simple stream of text data encoded in UTF-8


## npm libraries
- pg
