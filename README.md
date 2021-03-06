<img src="https://remoteconfigs.com/app/images/logo.svg" style="display: block; margin-left: auto; margin-right: auto; height: 80px; color: #BF2026;"/>
<div align="center">
  Take the pain out of managing all your app configurations that are scattered all over the Internet. With RemoteConfigs, you can manage all your app configurations from a central dashboard and reference them in your applications using our simple REST API.
</div>

<br />

<div align="center">
  <h3>
    <a href="https://remoteconfigs.com">
      Website
    </a>
  </h3>
</div>

<div align="center">
  <sub>RemoteConfigs, Inc. is a <a href="http://redrubyit.co.za">Red Ruby IT (Pty) Ltd.</a> company.</sub>
</div>

<br>

![Build status](https://redrubyit.visualstudio.com/RemoteConfigs/_apis/build/status/RemoteConfigs%20-%20Staging%20-%20CI)
![Deployment status](https://redrubyit.vsrm.visualstudio.com/_apis/public/Release/badge/5bf414cb-f023-4c36-aba0-c3af1dc61ea1/2/2)

# Table of Contents
* [API](#api)
    * [Authentication](#authentication)
    * [Testing and Available Endpoints](#testing-and-available-endpoints)
* [General](#general)
    * [Account](#account)
        * [Sign Up](#sign-up)
        * [Sign In](#sign-in)
        * [Forgot Password](#forgot-password)
        * [Billing](#billing)
        * [Profile](#profile)
        * [Close Account](#close-account)
    * [Configurations](#configurations)
        * [Create and Manage Configs](#create-and-manage-configs)

# Contact Us
There are numerous ways for you to get in contact with us. Below are suggested contact methods given the nature of your query:

1. 📧 Sending an Email to <a href="mailto: support@remoteconfigs.com">support@remoteconfigs.com</a>
    * We're pretty fast on email support 😉
2. 💬 <a href="https://remoteconfigs.com">Live Chat</a>
    * If you prefer a live chat with someone from our team, feel free to send us a message from the live chat found in the bottom-right corner of the home page of RemoteConfigs. Live chat is not available 24/7.

# API
Our API documentation can be found at: <a href="https://api.remoteconfigs.com" target="_blank">https://api.remoteconfigs.com</a>.
From there you are able to test the API endpoints with your API key.

The base API URL is:
```
api.remoteconfigs.com
```
## Authentication
In order to use your app configurations in RemoteConfigs, you will need to generate an API key. The API key is used to authenticate your requests.
**The API key is sent in the header of your request with the key `apikey`**

e.g. `"apikey" : "RC_a16eff3197f678ad543c55c99b9a5eb71926c7ca"`

To generate an API key, go to the **API Keys** page from your Dashboard, after signing in.

## Testing and Available Endpoints
The <a href="https://api.remoteconfigs.com">API Testing Page</a> allows users to test the requests and responses of the RemoteConfigs API endpoints.

Here is an example of the endpoint that will get all your configurations and their settings:

![Get All Configurations Endpoint](https://raw.githubusercontent.com/RemoteConfigsInc/Documentation/master/Images/ApiSwaggerGetAllConfigs.png "Get All Configurations")

Clicking on the `/Configuration` row will expand to show more details about the endpoint.

# General
## Account
### Sign Up
To sign up with RemoteConfigs is a very simple process. _We'll even give you 5 settings for free and you don't have to provide any credit card details when you sign up._

Follow these steps to get started with RemoteConfigs for the first time:
1. Go to the <a href="https://remoteconfigs.com/Home/Signup">Sign Up Page</a>.
2. Complete the form, remember your password, and make sure to read and accept the Terms of Use and Privacy Policy.
3. Click the **Sign Up** button.
4. Check your mailbox for the verification email and click the **Activate Account** button or link in the email.
5. You will now be redirected to a form where you will have to enter the password you chose earlier.
6. Click the **Verify Email Address** button.
7. Great! Your email address has been verified and you are now able to sign into RemoteConfigs.

See [Sign In](#sign-in) for more details.

### Sign In
Signing into RemoteConfigs is easy, all you need is the email address you used to sign up with and your password. If for any reason you are unable to sign in, please [Contact Us](#contact-us).

### Forgot Password
If, for some mysterious reason, you are unable to remember your password and would like to reset it, all you need to do is follow these steps:

1. Go to the <a href="https://remoteconfigs.com/Home/ForgotPassword">Forgot Password Page</a> or on the Sign In page, click the **Forgot your Password?** link at the bottom of the form.
2. On the Forgot Password page, enter your email address and click the **Send Reset Email** button.
3. Check your mailbox for an email from RemoteConfigs.
4. Follow the link in the email and enter a new password.
5. Click the **Reset Password** button.

Your password has now been changed and can be used to sign in.

### Billing
To view your billing information, go to **Settings**, then click on the Billing tab.
Under the **Payment Methods** section you'll see your credit and debit cards as well as which card is your default. You are also able to add and remove cards.

Under the **Billing History** section you'll see a list of invoices along with their statuses. You are also able to view and download your invoices from there.

### Profile
If you would like to make changes to your profile, click on the cog in the top-right corner of the page after you have signed in, then click on **Settings**.
By default, you will be on the Profile tab, from there you are currently only able to make the following changes:

* Change your First and Last names
* Change your password
* Deactivate your RemoteConfigs account

### Close Account
**WARNING** **_Only close your account when you are certain that there are no applications that make use of your RemoteConfigs configurations. You will lose your API keys and all information associated with your account._**

To close your account, first go to Settings by clicking on the cog in the top-right corner of any page after you have signed in.
When you are on the Settings page, you can close your account by clicking the **Close Account** button and confirming that you want to close your account.

## Configurations
### Create and Manage Configs
There are two ways to create and manage your configs.

1. From the Dashboard
2. Using the API
  * All CRUD operations are available through the API. See the [API](#api) section for more information.
  
