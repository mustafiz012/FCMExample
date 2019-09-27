# FCMExample
Using FCM (Firebase Cloud Messaging), here I'm trying to demonstrate the "Push Notification" integration in Android application and Firebase messaging tuorial is followed for this.
Link: https://github.com/firebase/quickstart-android/tree/a1074212f0ec271d57bdf91f851f5e8e1be4b09c/messaging

// [START_EXCLUDE]

#There are two types of messages data messages and notification messages.

1. Data messages are handled here in onMessageReceived whether the app is in the foreground or background. Data messages are the type traditionally used with GCM/FCM.

2. Notification messages are only received here in onMessageReceived when the app is in the foreground. When the app is in the backgroun an automatically generated notification is displayed.

#When the user taps on the notification they are returned to the app. Messages containing both notification and data payloads are treated as notification messages. The Firebase console always sends notification messages.

#For more see: https://firebase.google.com/docs/cloud-messaging/concept-options

// [END_EXCLUDE]
