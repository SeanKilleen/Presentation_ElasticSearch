---
marp: true
title: "Stretching .NET: An Introduction to ElasticSearch"
theme: uncover
paginate: false
footer: "An Introduction to ElasticSearch | :earth_americas: [SeanKilleen.com](https://SeanKilleen.com) | :bird: [@sjkilleen](https://twitter.com/sjkilleen)"
class: invert
---
# Stretching .NET

#### An Introduction to ElasticSearch

[elasticsearch.seankilleen.com](https://elasticsearch.seankilleen.com)

---

# Modernizing

# To .NET Core

[netcore-workshop.seankilleen.com](https://netcore-workshop.seankilleen.com/)

---

![bg contain](./assets/images/excella2.jpg)

---

<!-- _footer: "" -->

![bg contain](./assets/images/dotNetFoundation.png)

---

<style scoped>
  ul {
    padding: 0;
    list-style: none;
  }
</style>
<!-- _footer: "" -->
![bg left 60%](./assets/images/me.png)

# <!--fit--> Hi! :wave: I'm Sean

- :bird: [sjkilleen](https://twitter.com/sjkilleen)
- :earth_americas: [SeanKilleen.com](https://seankilleen.com)
- :briefcase: [Excella](https://excella.com)

---
<!-- _footer: "" -->

![bg](./assets/images/clowns-everywhere.gif)

---

# Ground Rules

---
<!-- _footer: "" -->

![bg contain](./assets/images/danger-zone.jpg)

<!-- 
- Content might not be for you
- Some parts might be rough
- Your feedback is going to be really important
-->

---
<!-- _footer: "" -->

![bg contain](./assets/images/amateur-hour.gif)

---

## Agenda for the Day

<!-- 
- Presentation Overview
- Assessing sample project
- Converting step-by-step
- Adding some new goodies
-->

---

## Logistics

- Breaks
- Catching Up
- Questions / Parking Lot
- Choose your Own Adventure

---

# Note: Interaction

---
<!-- _footer: "" -->

![bg contain](./assets/images/csi-explosion.gif)

---

## Why Update to .NET Core?

---

#### Why .NET Core?

# Performance

---

![bg contain](./assets/images/techempower-round18.png)

---
<!-- _footer: "" -->
![bg contain](./assets/images/techempower-16-graph.png)

---
<!-- _footer: "" -->
![bg contain](./assets/images/bing-news.png)

---

#### Why .NET Core?

# Platforms

---

![bg contain](./assets/images/core3-platform-support.png)

---

#### Why .NET Core?

# Community

---

![bg contain](./assets/images/contributors.png)

---

#### Why .NET Core?

# Other Goodies

---

#### Other Goodies

# Kestrel

---

#### Other Goodies

# HTTP/2

<!-- 
Came from SPDY
Reduce latency by enabling full request and response multiplexing
Minimize protocol overhead via efficient compression of HTTP header fields
add support for request prioritization
add support for server push
-->

---

#### Other Goodies

# Single .exes

---

#### Other Goodies

# Built-in DI

---

#### Other Goodies

# Health Checks

---

#### Other Goodies

# Razor Pages

---

#### Other Goodies

# Razor components

---

#### Other Goodies

# Blazor

---

#### Other Goodies

# Websockets

# &amp; signalR

---

#### Other Goodies

# Self-hosted apps

---

#### Other Goodies

# Containerization

---

# .NET 5

---
<!-- _footer: "" -->

![bg](./assets/images/matrix-inevitability.gif)

---

#### Why _Not_ Upgrade?

![](./assets/images/this-broke-me.gif)

---

#### Why _Not_ Upgrade?

## Webforms / WCF

<!--
  - Still has a WCF Client
-->

---

#### Why _Not_ Upgrade?

## Not a 1:1

---

#### Why _Not_ Upgrade?

## Monoliths

---

## Challenge

## Vs

## Opportunity

---

![bg](./assets/images/ship-launch-fail.gif)

<!-- I'm new at this -- will do my best to answer questions -->

---

## Introducing

## The Sample App

---

[https://github.com/SeanKilleen](https://github.com/SeanKilleen/netcoreworkshop-mvcmovie-sample)

[/netcoreworkshop-mvcmovie-sample](https://github.com/SeanKilleen/netcoreworkshop-mvcmovie-sample)

---

<style scoped>
  ul {
    padding: 0;
    list-style: none;
  }
</style>
<!-- _footer: "" -->
![bg left 60%](./assets/images/me.png)

# <!--fit--> Thanks

- :bird: [sjkilleen](https://twitter.com/sjkilleen)
- :earth_americas: [SeanKilleen.com](https://seankilleen.com)
- :briefcase: [Excella](https://excella.com)
