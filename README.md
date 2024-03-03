# oauth-example

UNH IT666 lab to investigate the user experience with multiple OAuth providers
Based on Google Firebase Auth example code

App has been registered with Google, Twitter, Facebook and GitHub and can use any identity from those providers.

### You nust implement your own providers
Even if you reuse the code provided.  

*Caveat*: Firebase creates two domains
- https://<YOUR-APP>.web.app
- https://<YOUR-APP>.firebaseapp.com  
*Pick one and stick to it for configuring your providers.*

Website: https://<YOUR-APP>.firebaseapp.com
Callback URL: https://<YOUR-APP>.firebaseapp.com/__/auth/handler

Go to the developer portal for your specific provider(s).
- Create an web application.
- Set the the website and callback URLs
- Copy the client-id and client-secret back into the Firebase app for the that provider.
  - https://console.firebase.google.com/project/<YOUR-APP>/authentication/providers

