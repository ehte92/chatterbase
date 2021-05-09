# ChatterBase

A chat application implemented using React and Firebase.
⚛️🔥 React Firebase stack, including user authentication, firestore, and security rules.

When creating a message, the following security rules ensure that a user…

Is Signed in
Is creating a document with a UID that matches their own.
Is using less than 255 text characters.
Is not trying to modify the timestamp.
Is not banned.

A user is banned if they user abusive words
