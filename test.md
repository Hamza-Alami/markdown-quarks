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

## Security Settings

In the Security Settings section of your app dashboard, you can configure additional security features for your app. Here are some of the options available:

### Force Login

The Force Login parameter allows you to set a time period after which the user will be required to login again, even if their token has not yet expired. To configure this option, enter a value in the "Force Login After" field.

### Force Logout

The Force Logout parameter allows you to set a time period after which the user will be automatically logged out of the app. To configure this option, enter a value in the "Force Logout After" field.

### Password Dictionary

The Password Dictionary option allows you to refuse passwords that are among the 10,000 or 100,000 most commonly used passwords. To configure this option, select the desired option from the dropdown list.

By using these security settings, you can help to ensure that your app is secure and protected from unauthorized access.

## Advanced Security

In the Advanced Security section of your app dashboard, you can configure additional security options for your app. Here are some of the options available:

### Allowed Domains

The Allowed Domains option allows you to restrict login to users who have email addresses associated with certain domains. To configure this option, enter the domain names that are allowed in the "Allowed Domains" field.

### Allowed Origins

The Allowed Origins option allows you to whitelist certain URLs that are allowed to make requests to your app. To configure this option, enter the URLs in the "Allowed Origins" field.

### Allowed IP Addresses

The Allowed IP Addresses option allows you to whitelist certain IP addresses that are allowed to access your app. To configure this option, enter the IP addresses in the "Allowed IP Addresses" field.

### Blacklisted IPs

The Blacklisted IPs option allows you to block access to certain IP addresses that you do not want to be able to access your app. To configure this option, enter the IP addresses in the "Blacklisted IPs" field.

### Allowed Countries and Not Allowed Countries

The Allowed Countries and Not Allowed Countries options allow you to restrict access to your app based on the user's country of origin. To configure these options, select the desired countries from the corresponding dropdown lists.

By using these advanced security settings, you can help to ensure that your app is secure and protected from unauthorized access from specific domains, origins, IPs, and countries.

## User Management

The User Management section of your app dashboard allows you to add new users manually by filling in the required fields, including username, email, password, and password confirmation. This section also provides you with an overview of your users, including their email addresses, last login dates, and account status.

## Logs

The Logs section of your app dashboard provides you with detailed information about user activity, including authentication attempts and errors. You can access logs for each individual user, as well as logs for the entire app. The logs provide you with the following details:

- Authflow ID: The ID of the authentication flow that made the call to our API with the user ID
- User ID: The ID of the user who made the authentication attempt
- Email Address: The email address of the user who made the authentication attempt (if the user has already created an account)
- Method: The authentication method used (e.g. email and password, email and email code, etc.)
- Status Code: The status code returned by the authentication attempt (e.g. success, failure, etc.)
- Errors: Any errors that occurred during the authentication attempt

The Logs section also provides information about the devices and operating systems used by the end user to login, as well as the country of origin. This information is displayed in a user-friendly and readable page that includes the address, company, and whether the address is anonymous, a threat, a cloud provider, a bot, or a cloud. Note that while this section is accessible in the free version, it is limited to 7 days of log history.

