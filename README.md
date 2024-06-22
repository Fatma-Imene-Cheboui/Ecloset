Ecloset
Overview
Ecloset is a mobile application designed to provide a user-friendly platform for buyers and sellers of various items. The app integrates features for user authentication, profile management, item listing, and more, all supported by a robust backend architecture.

Team
CHEBOUI Fatma Imene (Leader)
BAKHOUCHE Rachel
DJAID Douaa
AFRA Hana
Contents
UI/UX Design
Software Architecture
Use Case Diagram
Architecture Overview
Software Components
UI/UX Design
App Icon

Registration (Sign-up/ Login)
Screenshots and description of the registration and login process.

Password Reset
Screenshots and description of the password reset process.

Home Page + Filter Search
Screenshots and description of the home page and filter search functionality.

User Profile
Screenshots and description of the user profile, editing profile info, and managing favorite items.

Seller Profile
Screenshots and description of the seller profile, procedure for adding an item for sale, and its user-facing presentation.

Logout
Screenshots and description of the logout process.

Software Architecture
Use Case Diagram

Architecture Overview

Software Components
Mobile Frontend (Client Side)

Objective: Provide a user-friendly interface for buyers and sellers on mobile devices.
Technology/Framework: Flutter for iOS and Android
Backend Services

Objective: Manage business logic, database interactions, and serve data to the mobile app.
Technology/Framework: Python (Server), Firebase Realtime Database (Database)
APIs (Application Programming Interfaces)

Objective: Enable communication between the mobile app and backend services.
Technology/Framework: RESTful APIs, returning data in XML format using standard HTTP methods (GET, POST, PUT, DELETE) for CRUD operations.
User Authentication & Authorization

Objective: Secure user logins, registrations, and access control.
Technology/Framework: Firebase Authentication
Push Notification Service

Objective: Send notifications for wish-listed items, updates, etc.
Technology/Framework: Firebase Cloud Messaging (FCM)
Image & Content Storage

Objective: Store images, descriptions, and user-related content.
Technology/Framework: Firebase Cloud Storage
Local Data Storage

Objective: Store temporary app data and user preferences locally.
Technology/Framework: SQLite
Geolocation Services

Objective: Enable location-based features within the app.
Technology/Framework: Use packages for geolocation in Flutter like ‘geolocator’
Installation
Prerequisites
Flutter SDK
Python
Firebase account
Setup
Clone the repository:

sh
Copy code
git clone https://github.com/Fatma-Imene-Cheboui/HARTH_ML_Prediction.git
cd HARTH_ML_Prediction
Install dependencies for Flutter app:

sh
Copy code
flutter pub get
Configure Firebase:

Add google-services.json for Android in android/app.
Add GoogleService-Info.plist for iOS in ios/Runner.
Run the app:

sh
Copy code
flutter run
Usage
Registration:

Open the app and navigate to the registration page.
Fill in the required details and sign up.
Login:

Enter your credentials and log in.
Explore Items:

Use the home page and filter search to explore items.
View item details and add them to your favorites.
Sell Items:

Navigate to the seller profile and follow the procedure to list a new item for sale.
Notifications:

Stay updated with push notifications for wish-listed items and other updates.
Contribution
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
License
Distributed under the MIT License. See LICENSE for more information.

Contact
CHEBOUI Fatma Imene - GitHub
BAKHOUCHE Rachel
DJAID Douaa
AFRA Hana
Acknowledgements
Thanks to all contributors and collaborators who made this project possible.
Special thanks to the instructors and mentors guiding us through the project.
This README provides a detailed overview of the Ecloset project, including the UI/UX design, software architecture, installation steps, and usage instructions. You can adjust the paths to the images and diagrams as needed.
