# oAuth2
Implements spring oauth2 with JWT token store

The required spring oauth data structure is created as JPA entities. 

How to run
=========================================================================
Simply clone and update database cofig.

Run the import.sql to import client data

Then run OauthServerApplication. 

It will create tables and insert sample data to test the Oauth2 server

# Oauth2 login flow:

Refer to IntegrationTestMain for the login flow.
Document refer to https://auth0.com/docs/get-started/authentication-and-authorization-flow/authorization-code-flow

