---
layout: ../../layouts/patent.astro
title: Integration of fragment modules in user interfaces
publishDate: 2020-03-02 00:00:00
img: https://images.unsplash.com/photo-1547234935-80c7145ec969?fit=crop&w=1400&h=700&q=75
description: |
  Patent for quick actions using a micro-frontend library written by me and Titus Woo at PayPal
tags:
  - web
  - micro-frontend
  - patent
patentlink: https://patents.google.com/patent/US11385911B2/en?inventor=Arseniy+Kotov
---

Methods and systems are presented for providing a framework to integrate independent fragment modules into an integrated user interface. The fragment modules can be simultaneously rendered on a user interface page or sequentially rendered across multiple user interface pages. The fragment modules are configured to interact with a user via the user interface. The interactions with the user may trigger an event. When an event associated with a fragment module occurs, the fragment module is configured to broadcast the event. An orchestrator is configured to monitor events associated with different fragment modules. The orchestrator may include an event handler for performing one or more action in response to an event. The action may include configuring another fragment module to modify a presentation and/or perform a transaction based on the event.
