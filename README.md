# ApiGear Roadmap

This is a high-level site for planning roadmap and features. We use issue tracking in the projects to track issues for the tooling (cli, hub, studio) and templates.

The information here does not always reflect the same state of thinking.

/ ApiGear Team

## Roadmap Discussion

We worked a lot in 2023 to make all different ApiGear features more stable and easier to work with. At the same time we invested quit a lot into the whole IPC story. For 2024 we will focus more on designer value (e.g. visual editing, better simulation, record-replay) and product visibility (e.g. events, cloud hub, meetups). We still will work in better IPC integration and optimizing performance (change ipc encoder, use ids as symbols).

### 2024 Focus

- Designer Value - We believe our customers are mainly Designers and Managers. They need to find an solution which solves their problem. How to get data into UE, how to simulate backends when they are not there yet, how to record an interaction session and replay it again and again.
- Manager Value - For managers it will be important to have team sharing, to see API host-spots (e.g. most used APIs), general API usage, etc. This will give them data points when discussing project progress.
- Project Value - Having an out of the box IPC solution which works for 90% of all use cases and it's fast enough to simulate world movement needs to be the target at some point. With a reference server to validate interoperability between language and performance tests to validate our speed. The most important targets are UE, C++, Go for UE OEM customers.

## Feature Discussion

- [feat001 js-filters ](features/feat001_js_filters.md): Add abilities for template writers to add own custom JS template filters.
