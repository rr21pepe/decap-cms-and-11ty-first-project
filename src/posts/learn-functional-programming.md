---
title: Learn functional programming
description: What's functional programming?
author: Mattheveloper
date: 2023-07-05T08:42:26.804Z
tags:
  - Tags
---
# F﻿unctional programming

```javascript
const pipe = (...fns) =>
  initialValue =>
    fns.reduce((value, fn) => fn(value), initialValue)
```