# Issue for Firebase Tools issue 6120

### Steps to reproduce

1. Run `firebase emulators:start --project demo-project`
2. Open "localhost:5000" on your web browser
3. Click the "Google sign-in using Popup" link or navigate to "http://localhost:5000/google-popup.html"
4. Click the "SIGN IN WITH GOOGLE" and log in
   1. Sign in as expected
5. Click the "SIGN OUT" button
6. Navigate to "http://localhost:5000/google-redirect.html"
7. Click the "SIGN IN WITH GOOGLE" and log in
   1. Sign in as expected
8. Click the "SIGN OUT" button
