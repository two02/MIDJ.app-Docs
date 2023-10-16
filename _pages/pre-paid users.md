---
title: "Pre-paid Users"
layout: default
permalink: /pre-paid-users/
nav_order: 3
---
{% include table-content %}

# For Pre-paid Users

### Generate
Send a POST request to, **https://api.midj.app/pre/generate** with your API token for the Authorization key in the header. In the body specify your prompt in json format.

![preGenerate](/../_images/preGenerate.png "Postman pre-paid generate")


### Variation
You can request a variation of particular image you got as a result. Send a POST request to **https://api.midj.app/pre/variation** with your API token as value for Autharization key in the header.
In the body you have to provide 
- **index** of the preffred image
- **"trigger_id**
- **msg_hash** from the msg you recieved with that image.

![pre paid variation](/../_images/pre paid variation.png "Postman pre-paid variation")


### Upscale
Send a POST request to **https://api.midj.app/pre/upscale** with your API token for the Authorization key in the header. In the body you have to specify the 
- **index** of the image you want to Upscale
- **trigger_id** you recieved to your webhook
- **msg_hash** you recieved to your webhook
in json format.

![pre paid upscale](/../_images/pre paid upscale.png "Postman pre-paid upscale")
