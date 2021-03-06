---
layout: thing
title: "Next Trains"
description: "Google Assistant Action to fetch British railway departures"
what: "a Google Assistant Action"
to: "to fetch train departures"
image: "profile.jpg"
---


In 2018 I created a Google Assistant Action to fetch British railway departure boards using the wonderful [RealTimeTrains](https://www.realtimetrains.co.uk/) API.

Anyone using the Google Assistant were able to ask queries such as "ask Next Trains about Birmingham Moor Street," to which my Action would reply with the latest departures. Over its 5-year lifespan I've kept adding features, including operator and delay information. Analytics reveal that at its peak, potentially dozens of people were using it every day to find information about their commutes.

Unfortunately, Google is [sunsetting](https://developers.google.com/assistant/ca-sunset) "conversational actions" and requiring developers to incorporate functionality into a companion Android app, which is something I am not interested in doing. As such, Next Trains will cease functioning after June 2023.

Next Trains is written in PHP and you can find it on the [Actions Directory](https://assistant.google.com/services/a/uid/0000002b9e81557d).