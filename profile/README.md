
# Welcome to Nova Studios Ltd!

Where Nova meets Studios and becomes Limited.

Currently we are working on Orbit!

## Orbit

Orbit is a messaging platform designed from the ground up to be fully private, customizable and secure.

Its main goal is anonymity: everything is stored in a manner that doesn't allow it to be viewed after it has been stored in our database.

### What You Gonna Do With My Data?

The only things we store outside of the messages themselves are:

- your email, which is stored as a SHA-512 hash and is only used to verify your identity.
- your username, which is displayed publicly (so don't use your real name if you don't want people to know it)
- your apple pie recipes (because pie)

### What about messages and files?

They are fully encrypted using a public/private RSA key pair generate by your client when you first sign up. The private key is the encrypted with your password and stored on our server for you to be able to access anywhere. 

All encryption happens on your device. The server simply stores this encrypted data so that it can send it to your recipients and allow you to access your data on any device. The server cannot read your data.

### Where Can I Get It?

As of now there is a offical Desktop and Web client. Later down the line there will be support for mobile, but priority right now is optimizing the Web/Desktop client to run well on all devices

Offical Web Client: [https://orbit.novastudios.uk](https://orbit.novastudios.uk)
