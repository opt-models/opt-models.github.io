---
title: "Building the LEGO® Opt App"
description: "The LEGO® Opt App video and code series overview page, listing all installments in the series and summarizing the project-based learnings the aim to convey."

editURL: "https://github.com/opt-models/opt-models.github.io/tree/main/content/compendium/dev-creature-comforts/index.md"

date: "2024-03-13"
lastmod: "2024-03-25"
---

We build a real-time optimization app for LEGO® enthusiasts that finds multiple sets buildable concurrently from a given user's part inventory.

To give users solutions in real-time using the (great!) open source solver HiGHS, many performance bottlenecks needed love: laggy data import, shrinking problems prior to solving, constraint reformulations, and more. 

## Thank You Rebrickable.com

... for sharing your LEGO® [data and database schema](https://rebrickable.com/downloads/) with the world, without which this project would not be possible. You guys are absolute rockstars and everybody should check out the awesome community at [Rebrickable.com](https://rebrickable.com/home/) ❤️.

## App Code Repo

{{< github repo="opt-models/opt-lego" >}}

## Chapters