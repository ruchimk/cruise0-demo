# Cruise0 Modernization Demo

Sample customer walk through for their SPA React modernization project to show how they can log users via social logins, verified emails and user demographics

## Key Features

This demo is meant to demonstrage how Auth0 can support the Cruise0 app modernization on ReactJS (this demo is built using Auth0's SPA SDK)

* It demonstrates how a new customer can sign up, and how an existing customer can sign in with email/password, and a social login (Google).
* Demonstrates how you can link accounts with the same email (i.e. database and social accounts for the same user) with Auth0 via our account linking feature
* Will show you howyou can show errors if the customer’s email address is not verified. 
* Profile page shows photo and country flag are displayed without prompting users to input directly (using rules and IP address of current user)
* If the photo and country of the customer are known, make sure this information is passed back to the application and shown after the user authenticates.

* [Suggested Account Linking within a Regular Web Application](/RegularWebApp)

## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, amont others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
* Add authentication through more traditional **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
* Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)** with the same user.
* Support for generating signed [Json Web Tokens](https://docs.auth0.com/jwt) to call your APIs and **flow the user identity** securely.
* Analytics of how, when and where users are logging in.
* Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).

## Create a free Auth0 Account

1. Go to [Auth0](https://auth0.com) and click Sign Up.
2. Use Google, GitHub or Microsoft Account to login.

## Resources

* [User Initiated Account Linking within a Single Page Application Sample](https://github.com/auth0-samples/auth0-link-accounts-sample/tree/master/SPA)
* [Auth0 Rules](https://auth0.com/docs/rules)


If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author
[Auth0](auth0.com)
