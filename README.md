# Groupie - A Group Chat Application

## Prominent Features

1. **User Authentication:** Utilizes Flutter's Firebase Authentication plugin for secure email/password sign-up and login.

2. **Group Creation and Joining:** Implements CRUD operations on Firebase Firestore for creating and managing public and private groups.

3. **Group Search:** Allows users to search for groups in real-time using Flutter's StreamBuilder widget.

4. **Group Details:** Users can view group details, including members and messages, with a mix of CRUD operations and StreamBuilders.

5. **User Profile:** Displays user profile using Flutter's shared_preferences package for local data storage.

6. **Leaving Group:** Enables users to leave groups, updating the Firebase Firestore database in real-time.

## Flutter Concepts Applied

Groupie extensively employs various Flutter concepts, including email/password authentication, CRUD operations, StreamBuilders, error handling, Shared Preferences, state management, custom widgets, asynchronous programming, dialogs/alerts, and SHA-1/SHA-256 encryption.

## Architecture

Groupie follows a Service-Oriented Architecture (SOA) with distinct services:

1. **AuthService:** Manages user authentication using Firebase, handling sign-up, login, and logout operations.

2. **DatabaseService:** Handles CRUD operations with Firestore, encapsulating group creation, message sending, and other database tasks.

SOA benefits include separation of concerns, reusability, parallel development, and easier debugging/testing.

## Future Considerations

While not currently using the BLoC pattern, Groupie could incorporate it for more organized state management, separating business logic from the UI.

## App Screenshots
![Sign In](https://imageupload.io/ib/QnRv5acjekpRSwc_1697467936.png)
![Sign up](https://imageupload.io/ib/SW6YorTW4UZgs9o_1697468097.png)
![Create a group](https://imageupload.io/ib/4FYMROOgeeTzffZ_1697468129.png)
![Show all groups](https://imageupload.io/ib/lF9lgaO9m45rMZ4_1697468160.png)
![Group info](https://imageupload.io/ib/pfp7yoByuvqDIxZ_1697468209.png)
![Profile](https://imageupload.io/ib/1pgGbcJSjBxyqZl_1697468244.png)
![Logout](https://imageupload.io/ib/9way7GtUcgWAIeA_1697468272.png)
## Flow diagram
![Flow diagram](https://imageupload.io/ib/WY95OhH8iL2NDdG_1697468295.png)
