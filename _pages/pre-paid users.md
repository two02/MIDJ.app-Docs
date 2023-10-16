---
title: "Pre-paid Users"
layout: default
permalink: /pre-paid/
nav_order: 3
---

# For Pre-paid Users

### Pregenerate(prompt)
Generate content based on a provided prompt:

```midj.Pregenerate('Hello, world!').then(console.log);```

### PregenerateVariation(index, trigger_id, msg_hash)
Generate a variation of content:

```midj.PregenerateVariation(0, trigger_id_here, 'msg_hash_here').then(console.log);```

### PreupscaleImage(index, trigger_id, msg_hash)
Upscale an image:

```midj.PreupscaleImage(0, trigger_id_here, 'msg_hash_here').then(console.log);```