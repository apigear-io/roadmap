# Record and replay of API traffic

Being able to record and replay API traffic was already much earlier requested by our customers. The feature allows customers to record API traffic and replay it later. This is useful for testing and simulation.

- Choose time window for recording but also playback.
- Replay speed must be adjustable (e.g. factor x times the natural speed)
- Filter modules and endpoints for recording and playback
- Record and replay must be possible for all supported languages

An initial demo using NATS looks promising. For this we need to create a named stream and then stream the data into the stream. The stream is then stored on drive and we can later playback these events. It is also possible to compute state during recording and by this report the changing state of time, e.g. to display in a dashboard.

Capabilities:

- Record API traffic using named streams (with filter of modules and endpoints)
- List all recorded streams
- View recorded stream data
- Info about recorded stream (e.g. size, time window, etc.)
- Playback recorded stream (e.g. speed, time window, etc.)
- Delete recorded stream (e.g. by name, by time window, etc.)
- Be able to push recorded stream to cloud (e.g. ApiGear Cloud)

## NATS

NASt is a high performance message bus. It can be embedded into applications nd is ca. 14MB in size. It is written in Go and has clients for many languages. It is also possible to use NATS as a service (e.g. NATS Cloud).

See [NATS](https://nats.io/)
