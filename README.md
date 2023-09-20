
# Chats

End-to-End Encrypted Chat Application
Overview
This project is an end-to-end encrypted chat application that prioritizes security and privacy. It uses Advanced Encryption Standard (AES) encryption to secure text messages and leverages Firebase for authentication, authorization (via JSON Web Tokens or JWTs), and as a database.

Features
1. AES Encryption
AES encryption is employed to secure text messages exchanged within the application. This encryption ensures that messages are only accessible to the intended recipients, providing a high level of confidentiality.

2. Firebase Authentication and Authorization
Firebase is utilized for both authentication and authorization. Users can securely sign up, log in, and manage their accounts. JWTs are employed to verify and grant access permissions, ensuring that only authorized users can interact with the chat application.

3. Firebase Realtime Database
Firebase serves as the application's database, enabling real-time communication between users. Messages are stored securely in the Firebase Realtime Database, ensuring reliability and seamless message retrieval.

Usage
To use the application, follow these steps:

Sign Up: Create an account using your email and a secure password.

Log In: Log in with your credentials to access the chat interface.

Start Chatting: Begin secure conversations with other users by entering their usernames or email addresses.

Encrypted Messaging: Enjoy the peace of mind that comes with AES encryption, knowing that your messages are protected from unauthorized access.

Security Considerations
End-to-End Encryption: All messages are encrypted using AES encryption, ensuring that only the intended recipients can decrypt and read the messages.

JWT Authorization: JWTs are used for authorization, providing a secure mechanism to control user access and protect sensitive data.

Firebase Security Rules: Firebase security rules are implemented to ensure that only authenticated users can read and write data, enhancing the overall security of the application.


## Tech Stack

**Client:** Kotlin, Firebase.

**Server:** Firebase
