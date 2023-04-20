# Authentification and Access Management Platform Documentation

Welcome to the documentation for our authentification and access management platform! This no code tool is designed to make authentification and access management simple, quick, and easy for anyone to use.

## Creating an App

The first step is to create an app, which can be renamed or deleted at any time. When you create an app, you can insert the name and description of the app.

## Authflows

The next step is to set up authflows, which refer to the way end users will authenticate into the app (e.g., email/password, email/code, email/sms/password). You can create an authflow with a name and description, and you will get a unique token for each authflow called a flowtoken. In the authflow settings, you can also set the token expiration, disable registration, and require a username at registration. You can also set a password policy to make the user's password more secure.

## Security Settings

The security settings section allows you to set a force login after a certain amount of time, as well as a force logout parameter. You can also set up a password dictionary to refuse passwords that are from the 10K or 100K most used ones.

## Advanced Security

In the advanced security section, you can set allowed domains, origins, and IP addresses. You can also blacklist certain IPs and set allowed and not allowed countries.

## User Management

In the user management section, you can add new users manually by filling in their name, email, password, and password confirmation.

## Logs

You can access the logs of your app to see details such as authflow ID, user ID, email address, method, status code, errors, device information, and country of origin. This section is user-friendly and readable, but secure, so you cannot see the hidden parts of a user's account, such as their password.

## General Settings

The general settings section allows you to set up the app's name, description, domain, logo, support email, and support URL.

## Integration

To integrate this authentication tool into your website, you need to install the quark auth library and copy your flow token from the interfaces dashboard. Then, anything inside the <quarks-authenticated></quarks-authenticated> tags will only be available to authenticated users.

## Future Updates

We are constantly working to make our platform even more powerful and offer additional features in the near future.

Thank you for using our authentification and access management platform!
