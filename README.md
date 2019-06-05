# NfcDemo
Example App: NFC Demo for Android with Kotlin

Finished demo app, implements the following NFC features for Android with Kotlin:

- Register for NDEF tags containing a URI / URL record
- Analyze the NDEF tag contents and print these into a list
- Handle NFC tags in app startup (intent delivered through onCreate()) and when the app is already running (onNewIntent())
- Set a pending intent for enabling foreground dispatch to read and analyze all NFC tags tapped while the app is running

Original principles by Andreas Jakl, Re-developed by Adithya Radhakrishnan
