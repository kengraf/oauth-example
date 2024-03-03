Firebase Auth Quickstart
=============================

The Firebase auth quickstart demonstrates several methods for signing in.

This repo implements: anonymous, email/password, Google, Facebook, Github, and Twitter signins.  

Introduction
------------

- [Read more about Firebase Auth](https://firebase.google.com/docs/auth/)

Getting Started
---------------

- Set up your project on the [Firebase Console](https://console.firebase.google.com).
- Enable the authentication method you want to use in the Auth section > SIGN IN METHOD tab - you don't need to enable custom auth.
- In the [Google Developer Console](https://console.developers.google.com), access the project you created in the Firebase Console. 
- For Custom Auth, also create a new Service Account in your project [Developers Console](https://console.developers.google.com/apis/credentials/serviceaccountkey?project=_), and download the JSON representation.
- Edit the `.html` for the authentication method you want to try and copy the initialization snippet from the Firebase Console **Overview > Add Firebase to your web app** into the `<head>` section of `.html`.
- Run `firebase serve` using the Firebase CLI tool to launch a local server and open the sample `.html` in a web browser.

Support
-------

https://firebase.google.com/support/

License
-------

© Google, 2016. Licensed under an [Apache-2](../LICENSE) license.
