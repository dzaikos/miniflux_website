---
title: Matrix Integration
url: /docs/matrix.html
---

Miniflux can send notifications to any [Matrix](https://matrix.org/) server.

To enable this integration, go to **Settings > Integrations > Matrix Bot** and enter the relevant information.

![Matrix Configuration](/images/matrix.png)

It is recommended to create a specific user for the Miniflux integration:

- The Matrix username uses this format: `@username:homeserver.tld`, for example: `@example:matrix.org`.
- The Matrix URL is the base URL of your Matrix server. For example: `https://matrix.org`.
- The Matrix Room ID can be found using a client like [Element](https://element.io/): **Room Settings > Advanced > Internal Room ID**. The format is `!localid:homeserver.tld`, for example: `!RXRwLGkDQJzA:matrix.org`.

At the time of writing this document, Matrix notifications look like this when using the [Element](https://element.io/) client:

![Matrix Notification](/images/matrix_notification.png)
