---
title: "Variation"
layout: default
parent: API usecases
permalink: /variation/
---
# Variation
You can request a variation of particular image you got as a result. Send a POST request to https://api.midj.app/api/variation with your API token as value for Autharization key in the header.
In the body you have to provide 
- **index** of the preffred image
- **"trigger_id**
- **msg_hash** from the msg you recieved with that image.

Below is a example of using variation with postman.
![Variation body](/../_images/Variation body.png "Variation body")

