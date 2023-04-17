# Creating a New App

To get started with your identity and access management platform, you can create a new app. This app will allow you to manage authentication, authorization, and user access for your application.

To create a new app, follow these steps:

1. Log in to your account and navigate to the "Apps" section of the dashboard.
2. Click on the "Create New App" button.
3. Enter a name for your app in the "Name" field. This name should be unique and descriptive of the purpose of the app.
4. (Optional) Enter a description for your app in the "Description" field. This can help you and other users better understand the purpose of the app.
5. Click on the "Create App" button to create the new app.

That's it! You have now created a new app in your identity and access management platform. You can now configure the app settings, manage users, and set up authentication and authorization for your application.

## Creating an AuthFlow

Once you have created an app, you can move on to configuring the authentication flow (AuthFlow) for your app. The AuthFlow defines how end users will authenticate into the app. To create an AuthFlow, follow these steps:

1. Navigate to the AuthFlows section of your app dashboard.
2. Click on the "Create New AuthFlow" button.
3. Enter a name for your AuthFlow in the "Name" field. This should be descriptive of the authentication method being used (e.g. Email and Password).
4. (Optional) Enter a description for your AuthFlow in the "Description" field. This can help you and other users better understand the purpose of the AuthFlow.
5. Click on the "Create AuthFlow" button to create the new AuthFlow.

Once you have created an AuthFlow, you can configure its settings. In the AuthFlow settings, you can choose the authentication method and set the token expiration. You can also disable registration and require a username at registration.

### Authentication Method

In the AuthFlow settings, you can choose from several authentication methods:

- Email and Password
- Email and Email Code
- Email and SMS Code
- Passwordless Email

### Token Expiration

The token expiration setting determines how long the end user's token will remain valid. You can set this value to any number of seconds, minutes, hours, or days.

### Disable Registration

If you want to prevent new users from registering for your app, you can check the "Disable Registration" checkbox in the AuthFlow settings.

### Require Username

If you want to require users to provide a username when they register for your app, you can check the "Require Username" checkbox in the AuthFlow settings. You can also set the minimum and maximum length for the username.

### Password Policy

In the AuthFlow settings, you can choose a password policy to enforce for your app's users. The available options are:

- None
- Weak
- Average
- Strong

Each password policy has its own specific requirements to make the user's password more secure.
