# payu-gpay-mob v1.3.8


This library uses to integrate Google Pay.
We are offering 2 types of Google Pay transactions.
In-App Flow:
Where the user device has Google Pay application installed. We invoke the Installed Google Pay application to do the payment transaction. User will see the Bottom-sheet(In-app) like UI on the checkout screen.

If the installed app doesn't support In-app, then payment will be making via Intent flow(Full Screen UI).

Web Flow:
If the user device doesn't have Google Pay application installed, we will show the Web UI to do the payment. It is basically a collect flow, where the Google Pay application on the other device will get the notification to do the transaction. NPCIs call it PULL flow: Requesting money.

Integration Doc:
https://payumobile.gitbook.io/sdk-integration/android/google-pay
