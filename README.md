<img src="https://remoteconfigs.com/src/img/Remoteconfig_final.svg" style="display: block; margin-left: auto; margin-right: auto; height: 80px; color: #BF2026;"/>
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
  <a href="http://redrubyit.co.za">Red Ruby IT (Pty) Ltd.</a></sub>
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

# Contact Us
There are numerous ways for you to get in contact with us. Below are suggested contact methods given the nature of your query:

1. 🗫 <a href="https://forum.remoteconfigs.com">RemoteConfigs Forum</a>
    * Our forum is a great place to submit ideas, provide feedback, ask questions or to get assistance from other users.
2. 📧 Sending an Email to <a href="mailto: support@remoteconfigs.com">support@remoteconfigs.com</a>
    * We're pretty fast on email support 😉
3. 💬 <a href="https://remoteconfigs.com">Live Chat</a>
    * If you prefer a live chat with someone from our team, feel free to send us a message from the live chat found in the bottom-right corner of the home page of RemoteConfigs. Live chat is not available 24/7.

# API
The base API URL is:
```
api.remoteconfigs.com
```
## Authentication
In order to use the of RemoteConfigs, you will need to generate an API key. The API key is used to authenticate your requests.
**The API key is sent in the header of your request with the key `apikey`**

e.g. `"apikey" : "RC_9e0bbb4cada16f688da56506b561d1e5928e0c6c"`

To generate an API key, go to the **API Keys** page from your Dashboard (you will need to be signed into RemoteConfigs).

![API Keys Page](https://raw.githubusercontent.com/RemoteConfigsInc/Documentation/master/Images/ApiKeysPage.png "ApiKeysPage")

## Testing and Available Endpoints
The <a href="https://api.remoteconfigs.com">API Testing Page</a> allows users to test the requests and responses of the RemoteConfigs API endpoints.

Here is an example of the endpoint that will get all your configurations and their settings:

![Get All Configurations Endpoint](https://raw.githubusercontent.com/RemoteConfigsInc/Documentation/master/Images/ApiSwaggerGetAllConfigs.png "Get All Configurations")

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
Signing into RemoteConfigs is easy, all you need is the email address you used to sign up with and your password. If for any reason you are unable to sign in, please [Contact Us](#contact-us).

### Forgot Password
If, for some mysterious reason, you are unable to remember your password and would like to reset it, all you need to do is follow these steps:

1. Go to the <a href="https://remoteconfigs.com/Home/ForgotPassword">Forgot Password Page</a> or on the Sign In page, click the `Forgot your Password?` link at the bottom of the form.
2. On the Forgot Password page, enter your email address and click the `Send Reset Email` button.
3. Check your mailbox for an email from RemoteConfigs.
4. Follow the link in the email and enter a new password.
5. Click the `Reset Password` button.

Your password has now been changed and can be used to sign in.

### Billing

### Profile
If you would like to make changes to your profile, click on the cog in the top-right corner of the page after you have signed in, then click on `Settings`.
By default, you will be on the Profile tab, from there you are currently only able to make the following changes:

* Change your First and Last names
* Change your password
* Deactivate your RemoteConfigs account

### Close Account
**WARNING** **_Only  deactivate your account when you or any of your applications make use of RemoteConfigs. You will lose your API keys and all information associated with your account._**

To close your account, first go to Settings by clicking on the cof in the top-right corner of any page after you have signed in.
When you are on the Settings page, you can close your account by clicking the `Close Account` button and confirming that you want to close your account.

## Configurations
### Creating a Config
There are 2 ways to create a config:

1. From the Dashboard
    1.1 Click the `Create` button on the **New Configuration** card.
    1.2 Give your config a name and short description.
    1.3 Add the settings for your config. A config's settings is a list of key-value pairs.
    1.4 Once you are done adding settings to the config, click the `Create Configuration` button. 

2. Using the API
    * see the [API](#api) docs for more information on authenticating and the available endpoints.

### Managing a Config
To manage a config, click on the `Manage Configuration` button for the config you want to manage, on the Dashboard.
You will now be able to make changes to the configuration.