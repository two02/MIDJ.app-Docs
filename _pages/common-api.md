---
title: "Common Api"
layout: default
permalink: /common-api/
nav_order: 5
---
# Common API
Both pre-paid and subscription users can use this api calls.

### Fetch content by trigger id
Fetch generated content by its trigger ID.

Send a POST request to, **https://api.midj.app/api/getByTrigger** with your API token for the Authorization key in the header. In the body specify the trigger id of the required content in json format.

![getByTrigger](/../_images/common api > getByTrigger.png "Postman common api getByTrigger")
