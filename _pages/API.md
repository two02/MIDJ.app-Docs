---
title: "API usecases"
layout: default
has_children: true
permalink: /api/
---
<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

There are four main actions in API.
#### [Image Generation](/image-generation/)
Here you can send a POST request to the API with a prompt in its body and generate four sample images.

#### [Upscaling](/upscaling/)
Once you got four sample images, you can select a particular image to upscale. Once you send POST request with relavant index of the image you want you will recieve the upscaled version of the image.

#### [Variation](/variation/)
If your sample image need some more work, you can request variation of the image.

#### [isBanned](/isbanned/)
There are some keywords you cannot use in the prompt. You can check your keywords whether they are banned or not.


{% swagger /api/get.json %}
