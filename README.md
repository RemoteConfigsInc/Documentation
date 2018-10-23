<img src="https://remoteconfigs.com/src/img/Remoteconfig_final.svg" style="display: block; margin-left: auto; margin-right: auto; height: 80px; color: #BF2026;">
<div align="center">
  Take the pain out of managing your app configurations scattered all over the Internet. With RemoteConfigs, you can manage all your app configurations from a central portal and reference them in your applications using our simple REST API or any of our available libraries.
</div>

<br />

<div align="center">
  <h3>
    <a href="https://remoteconfigs.com">
      Website
    </a>
    <span> | </span>
    <a href="https://forum.remoteconfigs.com">
      Forum
    </a>
  </h3>
</div>

<div align="center">
  <sub>RemoteConfigs, Inc., a subsidiary of 
  <a href="http://redrubyit.co.za">Red Ruby IT (Pty) Ltd.</a>.
</div>

# Table of Contents
* [API](#api)
    * [Authentication](#authentication)
    * [Testing and Available Endpoints](#testing-and-available-endpoints)
* [General](#general)
    * [Account](#account)
        * [Sign Up](#sign-up)
        * [Sign Ip](#sign-in)
        * [Forgot Password](#forgot-password)
        * [Billing](#billing)
        * [Profile](#profile)
        * [Deactivate Account](#deactivate-account)
    * [Configurations](#configurations)
        * [Creating a Config](#creating-a-config)
        * [Managing a Config](#managing-a-config)

# API
## Authentication
In order to use the of RemoteConfigs, you will need to generate an API key. The API key is used to authenticate your requests.
**The API key is sent in the header of your request with the key `apikey`**

e.g. `"apikey" : "RC_9e0bbb4cada16f688da56506b561d1e5928e0c6c"`

To generate an API key, go to the **API Keys** page from your Dashboard (you will need to be signed into RemoteConfigs).

![API Keys Page](/Images/ApiKeysPage.png "ApiKeysPage")

## Testing and Available Endpoints
The <a href="https://api.remoteconfigs.com">API Testing Page</a> allows users to test the requests and responses of the RemoteConfigs API endpoints.

Here is an example of the endpoint that will get all your configurations and their settings:

![Get All Configurations Endpoint](/Images/ApiSwaggerGetAllConfigs.png "Get All Configurations")

Clicking on the `/Configuration` row will expand to show more details about the endpoint.

# General
## Account
### Sign Up
To sign up with RemoteConfigs is a very simple process. We'll even give you 5 settings for free and you don't have to provide any credit card details when you sign up.

Follow these steps to get started with RemoteConfigs for the first time:
1. Go to the <a href="https://remoteconfigs.com/Home/Signup">Sign Up Page</a>.
2. Complete the form and make sure to read and accept the Terms of Use and Privacy Policy.
3. Click the `Sign Up` button.
4. Check your mailbox for the verification email and click the `Activate Account` button or link in the email.
5. You will now be redirected to a form where you will have to enter the password you chose earlier.
6. Click the `Verify Email Address` button.
7. Great! Your email account has not been verified and you are able to sin into RemoteConfigs.

See [Sign In](#sign-in) for more details.

### Sign In

### Forgot Password

### Billing

### Profile

### Deactivate Account

## Configurations
### Creating a Config

### Managing a Config
