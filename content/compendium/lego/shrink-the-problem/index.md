---
title: "Shrink the Problem"
description: "With constraints in place ensuring that selected LEGO® sets are complete, we now implement constraints limiting the search space to sets the user desires. We then observe that, while functional, this 'problem shrinking' is much faster if done via set manipulation rather than constraint imposition."
date: "2024-03-19"
lastmod: "2024-03-28"

tags: ["Speed","Set Work","Memory Efficiency","AMPL"]
series: ["LEGO"]
series_order: 9
---

With constraints in place which ensure that selected LEGO® sets are complete, we now implement constraints limiting the search space to sets that the user desires. We then observe that, while functional, a faster-computing way to implement such 'problem shrinking' is via set manipulation rather than constraint imposition.
