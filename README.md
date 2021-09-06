# AMZN

An Amazon Clone Built With Next.js

## View The Live Deployment [Here](https://amzn.jackjona.live)

## Disclaimer

This is **not** an official Amazon website (*not affiliated with Amazon*) and should not be considered or used as such; this is just a **clone**. This is not meant and should **not** be used for phishing or other malicious purposes.

### AMZN Log In Screen

This can be customized to use various authentication providers since it is all handled through Firebase.

Originally, it was intended to also clone the sign-in/login page of Amazon, but this was not implemented due to the way that it could possibly used mailiciously. Such as for phishing or credential harvesting of Amazon users. In the end, a simple "Sign In With Google" page was created.

### Payment Implementaion

Payment functionality is not implemented in order to avoid misleading visitors to imput their payment details. However, this can be very easliy done with Stripe or an alternative payment provider if desired.

### Software & Resources:

- Next.js
- Tailwind CSS
- Redux
- Fake Store API
- Firebase
- React
- Next-Auth
- Stripe
- @heroicons

#### To Develop Locally:

To Install Project Dependencies:

1) ```npm install```

Setup Firebase:

2) Create A [Firebase](https://firebase.google.com) Project & Paste Your Config Into ```firebase.js``` Found In The Project Root:

Setup Environmental Variables For The Project:

3) Rename ```env.template``` to ```env.local``` & Fill In Your Firebase Google Sign-In Web SDK Keys. (This is found in Authentication > Google > Web SDK Configuration)

To Start The Local Development Server:

4) ```npm run dev```

Develop 🎉:

5) Navigate to [http://localhost:3000](http://localhost:3000)