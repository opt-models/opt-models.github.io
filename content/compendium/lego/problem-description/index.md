---
title: "The Problem Description"
description: "An introduction to the community in which the opportunity to build a real-time optimization arises and a description of the 'Multi-Build' search it performs for LEGO enthusiasts, finding multiple LEGO sets that can be built concurrently from parts in a given person's part inventory."
date: "2024-03-27"
lastmod: "2024-03-28"

tags: ["Problem Description","Use Case","Objectives","AMPL","HiGHS"]
series: ["LEGO"]
series_order: 1
---

{{< youtubeLite id="HCJ7cVceJ9s" label="LEGO® Opt App - PART 01: The Problem Description" >}}

### SERIES INTRO! 

This is the first of eighteen videos over which we build an app for the awesome [Rebrickable®](https://rebrickable.com/home/) community, which finds multiple [LEGO®](https://www.lego.com/en-us) sets buildable concurrently from a user's part inventory.

### The App is made of...

... a [Streamlit](https://streamlit.io/) user interface (eventually) under which is a fast [Mixed-Integer Linear Program](https://en.wikipedia.org/wiki/Integer_programming) (MILP) written in the [AMPL](https://ampl.com/) algebraic modeling language, and solving problems with the open source linear solver [HiGHS](https://highs.dev/). We containerize the whole lot before deploying it all to some nifty hardware that is especially good for fast optimization workloads.

### This series is about...

...the pursuit of speed of execution in large-scale optimization applications. More broadly, it's about welcoming the interested outsider to the beautiful thing that is optimization programming, as it is in its natural habitat: the wilds of industry. 

Most of all, this is about having some fun with a bit of LEGO, coffee and friends. Let's build something! ❤️