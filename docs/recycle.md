---
layout: docs
title: Recycle
description: Reset stores back to original state
permalink: /docs/recycle/
---

# recycle

> (...storeNames: ?string): undefined

If you wish to reset a particular, or all, store's state back to their original initial state you would call `recycle`. Recycle takes a splat of strings which correspond to the store's names you would like reset. If no argument is provided then all stores are reset.

```js
// recycle just MyStore
alt.recycle('MyStore');

// recycle all stores
alt.recycle();
```
