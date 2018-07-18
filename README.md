# otp-authenticator-webapp
[![Build Status](https://travis-ci.org/moebel-de/otp-authenticator-webapp.svg?branch=master)](https://travis-ci.org/moebel-de/otp-authenticator-webapp)

A *Google Authenticator* like webapp.

## ☂️ No External Services are used, local JavaScript execution only ☂️

Hosted at github pages: https://moebel-de.github.com/otp-authenticator-webapp/
* branch: [gh-pages](https://github.com/moebel-de/otp-authenticator-webapp/tree/gh-pages)

Or host it on your onw GitHub account 
* just fork this repo and this web app is available at https://\<USERNAME>.github.com/otp-authenticator-webapp/


### Features
* generate totp codes
* show remaining valid seconds for totp code
* parse otpauth URLs in `secret` input field
* generate otpauth URL QR code - click on qr-code image
* accept url hash to pass secret or otpauth url
 * ℹ️ browsers do not send url hash value to server 
 * ⚠️ browsers may keep hash value in history
 * examples
  * otpauth URL - https://moebel-de.github.io/otp-authenticator-webapp/#otpauth://totp/john.doe?secret=N2SJSUOXCKQM5MAX7N7J3NBUQ4WTL66G&issuer=example.org
  * Secret only - https://moebel-de.github.io/otp-authenticator-webapp/#N2SJSUOXCKQM5MAX7N7J3NBUQ4WTL66G
