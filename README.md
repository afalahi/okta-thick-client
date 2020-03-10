# okta-thick-client
Demonstrate Okta OIDC from a windows thick (native) client application

This sample shows how to do an OAuth 2.0 Authorization flow from a Windows Desktop application. It is one of a series of OAuth samples for Windows. The original work was forked from a google example and converted to use Okta values.

## Introduction
When doing an OAuth 2.0 Authorization flow in a native application, it is important to follow best practices, which require using the browser (and not an embedded browser).

This sample demonstrates how you can open the user's browser with your OAuth 2.0 authorization request (where they might already be logged in!), have them complete the consent, receive the Authorization Code using a local loopback socket, and exchanging that code for authorization tokens.

## Okta Documentation
The protocols referenced in this sample are documented here:

OAuth 2.0
Using OAuth 2.0 for Mobile and Desktop Applications
Getting Started
Open the solution file: OAuthDesktopApp.sln
Run the app.
When the app starts, tap "Sign in with Google" and go through the flow.
Using your own credentials
The Sample comes backed with some demo client credentials, which are fine for testing, but make sure you use your own credentials before releasing any app, or sharing it with friends.

Visit the Credentials page of the Developers Console
Create a new OAuth 2.0 client, select Other
Copy the client id and client secret, and replace the values supplied in this sample.
Support
If you have a question related to these samples, or Google OAuth in general, please ask on Stack Overflow with the google-oauth tag https://stackoverflow.com/questions/tagged/google-oauth

If you've found an error in this sample, please file an issue: https://github.com/googlesamples/oauth-apps-for-windows/issues

Patches are encouraged, and may be submitted by forking this project and submitting a pull request through GitHub.

Advanced Reading
The protocols and best practices used and implemented in these samples are defined by RFCs. These expert-level documents detail how the protocols work, and explain the reasoning behind many decisions, such as why we send a code_challenge on the Authorization Request for a native app.

Internet-Draft: OAuth 2.0 for Native Apps BCP
RFC6749: OAuth 2.0
RFC6750: OAuth 2.0 Bearer Token Usage
RFC6819: OAuth 2.0 Threat Model and Security Considerations
RFC7636: OAuth 2.0 PKCE
License
Copyright 2016 Google Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
