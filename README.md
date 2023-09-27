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
- Visibility - We need to get more visibility for ApiGear. We need to get more people to know about ApiGear and what it can do for them. We need to get more people to use ApiGear and give us feedback. We need to get more people to contribute to ApiGear and help us to make it better.
- IPC Optimization - We need to ensure we can support out of the bow a world movement simulation. This means we need to optimize our IPC solution to be fast enough to simulate world movement. We need to ensure we can support UE, C++, Go for UE OEM customers and our tooling. We need to ensure we can support a reference server to validate interoperability between language and performance tests to validate our speed.

We will probably not work on all of these topics in 2024. We will focus on the most important ones and try to get as much done as possible.

## Feature Discussion

- [feat001 js-filters ](features/feat001_js_filters.md): Add abilities for template writers to add own custom JS template filters.
