---
title: " v1.0.0"
language_tabs:
  - javascript--nodejs: Node.JS
  - javascript: JavaScript
  - ruby: Ruby
  - python: Python
  - java: Java
  - go: Go
headingLevel: 3
toc_footers: []
includes: []
search: false
highlight_theme: darkula

---

# Ping Service v1.0.0

> Scroll down for code samples, example headers and payloads. Select a language for code samples from the tabs above or the mobile navigation menu.

Ping Pong message exchange

Base URLs:

# Schemas

## PingPayload

<a name="schemapingpayload"></a>

```json
{
  "sender": "string",
  "createdAt": "2019-08-24T14:15:22Z"
}

```

<h3 id="pingpayload-properties">Properties</h3>

|Name|Type|Required|Description|
|---|---|---|---|
|» sender|string|false|Sender of the ping message|
|» createdAt|string(date-time)|false|No description|

## PongPayload

<a name="schemapongpayload"></a>

```json
{
  "receiver": "string",
  "receivedAt": "2019-08-24T14:15:22Z"
}

```

<h3 id="pongpayload-properties">Properties</h3>

|Name|Type|Required|Description|
|---|---|---|---|
|» receiver|string|false|Receiver of the pong message|
|» receivedAt|string(date-time)|false|No description|

