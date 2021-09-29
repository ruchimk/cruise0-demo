# Cruise0 Modernization Demo

Sample customer walk through for their SPA React modernization project to show how they can log users via social logins, verified emails and save user demographics (country and photo) to the user_metadata.

## Key Features

This demo is meant to demonstrate how Auth0 can support the Cruise0 app modenization on ReactJS (this demo is built using Auth0's SPA SDK)

* It demonstrates how a new customer can sign up, and how an existing customer can sign in with email/password, and a social login (Google).
* Demonstrates how you can link accounts with the same email (i.e. database and social accounts for the same user) with Auth0 via our account linking feature
* Will show you howyou can show errors if the customer’s email address is not verified. 
* Profile page shows profile photo and country flag are displayed without prompting users to input directly (using rules and IP address of current user)
* If the photo and country of the customer are known, make sure this information is passed back to the application and shown after the user authenticates.

## How to Deploy and user this Example Application

1. Clone the repo
2. npm install && npm start
3. Turn on the "Force email verification" rule in Auth0's Manage Dashboard
4. Turn on the "Add country to the user profile" rule in Auth0's Manage Dashboard
5. Login to the Demo Cruise0 application
6. Verify your email by clicking on the link
7. Login and see your Primary profile 
8. Link your secondary account with the same email (Google or Database) via "Link Account button"
9. Check your Auth0's Manage Dashboard and see the profile photo and country being saved in user_metadata for the user you are testing with

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
* [Client side Account Linking](https://auth0.com/docs/users/user-account-linking/user-initiated-account-linking-client-side-implementation)
* [Social Identity Providers](https://auth0.com/docs/connections/social)
* [Force email verification Rule](https://auth0.com/rules/email-verified)
* [Add country to the user profile](https://auth0.com/rules/add-country)

