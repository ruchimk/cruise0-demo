# Cruise0 Modernization Demo

Sample customer walk through for their SPA React modernization project to show how they can log users via social logins, verified emails and save user demographics (country and photo) to the user_metadata.

## Key Features

This demo is meant to demonstrate how Auth0 can support the Cruise0 app modenization on ReactJS (this demo is built using Auth0's SPA SDK)

* It demonstrates how a new customer can sign up, and how an existing customer can sign in with email/password, and a social login (Google).
* Demonstrates how to link accounts with the same email (i.e. database and social accounts for the same user) with Auth0 via our account linking feature
* Will show you how to show errors if the customer’s email address is not verified. 
* Profile page shows profile photo and country flag are displayed without prompting users to input directly (using rules and IP address of current user)
* If the photo and country of the customer are known, make sure this information is passed back to the application and shown after the user authenticates.

## How to Deploy and user this Example Application

1. Clone the repository
2. Run following command in cloned repository: npm install && npm start
3. Turn on the "Force email verification" rule in Auth0's Manage Dashboard
4. Turn on the "Add country to the user profile" rule in Auth0's Manage Dashboard
5. Login to the Demo Cruise0 application
6. Verify your email by clicking on the link
7. Login and see your Primary account profile in the /profile page 
8. Link your secondary account with the same email (Google or Database) via "Link Account button"
9. Check your Auth0's Manage Dashboard and see the profile photo and country being saved in user_metadata for the user you are testing with

## Resources

* [User Initiated Account Linking within a Single Page Application Sample](https://github.com/auth0-samples/auth0-link-accounts-sample/tree/master/SPA)
* [Client side Account Linking](https://auth0.com/docs/users/user-account-linking/user-initiated-account-linking-client-side-implementation)
* [Social Identity Providers](https://auth0.com/docs/connections/social)
* [Force email verification Rule](https://auth0.com/rules/email-verified)
* [Add country to the user profile](https://auth0.com/rules/add-country)

