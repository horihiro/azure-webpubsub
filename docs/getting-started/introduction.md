---
layout: docs
group: getting-started
redirect_from:
  - "/getting-started/"
toc: true
---

# Azure Web PubSub
## Overview

Azure Web PubSub enables you to build real-time messaging web applications using WebSockets and the publish-subscribe pattern. Any platform supporting WebSocket APIs can connect to the service easily, e.g. web pages, mobile applications, edge devices, etc. The service manages the WebSocket connections for you and allows up to 100K **concurrent* connections. It provides powerful APIs for you to manage these clients and deliver real-time messages.

## Scenarios

Any scenario that requires real-time publish-subscribe messaging between server and clients or among clients, can use Azure Web PubSub service. Traditional real-time features that often require polling from server or submitting HTTP requests, can also use Azure Web PubSub service.

We list some examples that are good to use Azure Web PubSub service:

* **High frequency data updates:** gaming, voting, polling, auction.
* **Live dashboards and monitoring:** company dashboard, financial market data, instant sales update, multi-player game leader board, and IoT monitoring.
* **Cross-platform live chat:** live chat room, chat bot, on-line customer support, real-time shopping assistant, messenger, in-game chat, and so on.
* **Real-time location on map:** logistic tracking, delivery status tracking, transportation status updates, GPS apps.
* **Real-time targeted ads:** personalized real-time push ads and offers, interactive ads.
* **Collaborative apps:** coauthoring, whiteboard apps and team meeting software.
* **Push instant notifications:** social network, email, game, travel alert.
* **Real-time broadcasting:** live audio/video broadcasting, live captioning, translating, events/news broadcasting.
* **IoT and connected devices:** real-time IoT metrics, remote control, real-time status, and location tracking.
* **Automation:** real-time trigger from upstream events.

## Create Your First Instance

Go to Azure Portal and search **Web PubSub** Service. Create your service with several clicks.
Get your connection string under the "Keys" blade.

## Try A Live Demo
A client-side chat sample

## Getting Started

- Publish messages to WebSocket connections 
    - [JavaScript](./js-publish-message)
    - [C#](./csharp-publish-message)
- Using PubSub WebSocket subprotocol
    - [JavaScript](./js-work-with-subprotocols)
- Create a chat app
    - [JavaScript](./js-handle-events)

## Integrate with Azure Function
- [Work with Azure Function](./work-with-azure-function)
- [Function bindings](./../references/functions-bindings)

## References
- [Establish WebSocket connections to the service](./../references/websocket-clients)
- [WebSocket PubSub Subprotocol in detail](./../references/pubsub-websocket-subprotocol)
- [Web PubSub CloudEvents in detail](./../references/protocol-cloudevents)