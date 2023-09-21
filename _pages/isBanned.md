---
title: "isBanned"
layout: default
parent: API usecases
permalink: /isbanned/
---
There are some keywords you cannot use in the prompt. You can check your prompt by using this endpoint.

# Checking whether a keyword is banned.

Send a POST request to **https://api.midj.app/api/isBanned** with your API token for the Authorization key in the header. In the body you have to specify the prompt you want to check in jason format.
You will get a response in json format containing whether the prompt is banned or not.

### Using the API with "postman"
Create a POST request to **https://api.midj.app/api/isBanned**.
In the request header specify the Authorization key with the value of your API token.

Then in the body of the request, select raw body and json file format. Then specify your prompt as below and send the request.
![request body](/../_images/isBanned request body.png "request body")


Then you will get a response like below.
![request body](/../_images/isBanned response.png "request body")


{% include swagger.html url='/api/isBanned.yml' %}
