---
title: "Getting Statrted"
layout: home
nav_order: 1

---
{% include table-content %}
# What is MIDJ.app?

MIDJ is an API that allows you to generate high quality images using text prompts as the input.

# Getting Started

### Sign Up and Login

Head over to SignUp/LogIn page and select a prefered way to sign up.

![SignUp/LogIn](/../_images/signup-login.png "SignUp/Login")

**Note:** You can sign up with either Google or Github. The same gmail account can create two seperate accounts with google account and github account.


### Subscribing to a Plan.
Once you Loged into your account you can select a subscription plan.

Goto pricing page and select a prefered plan. That will redirect you to Dashboard. Or you can directly head over to the Dashboard and click on **Upgrade to Premium** which will also take you to the Manage Payment tab. There you can select the Subscription plan you want using the drop down menu. Then click on Upgrade to premium button.

![Upgrade to premium](/../_images/Upgrade to premium.png "Upgrade to premium")

You will be redirect to stripe API to manage your payment records. Once you done that you can come back to MIDJ.app and 

### Generating a API token
Head over to Dashboard > API TOKEN tab.
Click on the Create New Token button. A dialog box will pop up and you'll ask to enter a webhook url. You can use a free webhook service like [webhook.site](https://webhook.site/).
Copy and paste your webhook url to the dialog box and click enter.

![Webhook](/../_images/create API > webhook.png "Webhookurl")

You can create as many tokens as you like. 
![API tokens](/../_images/API tokens.png "API tokens")

Now you are ready to use the API.

[using API](/api/)