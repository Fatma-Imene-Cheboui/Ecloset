# **Ecloset**

## **Overview**

Ecloset is a mobile application designed to provide a user-friendly platform for buyers and sellers of various items. The app integrates features for user authentication, profile management, item listing, and more, all supported by a robust backend architecture.

## **Team**

- **CHEBOUI Fatma Imene (Leader)**
- BAKHOUCHE Rachel
- DJAID Douaa
- AFRA Hana

## **Contents**

- [UI/UX Design](#uiux-design)
- [Software Architecture](#software-architecture)
  - [Use Case Diagram](#use-case-diagram)
  - [Architecture Overview](#architecture-overview)
  - [Software Components](#software-components)

---

## **UI/UX Design**

### **App Icon**

![App Icon](path-to-app-icon-image)

### **Registration (Sign-up/ Login)**

Screenshots and description of the registration and login process.

### **Password Reset**

Screenshots and description of the password reset process.

### **Home Page + Filter Search**

Screenshots and description of the home page and filter search functionality.

### **User Profile**

Screenshots and description of the user profile, editing profile info, and managing favorite items.

### **Seller Profile**

Screenshots and description of the seller profile, procedure for adding an item for sale, and its user-facing presentation.

### **Logout**

Screenshots and description of the logout process.

---

## **Software Architecture**

### **Use Case Diagram**

![Use Case Diagram](path-to-use-case-diagram-image)

### **Architecture Overview**

![Architecture Overview](path-to-architecture-overview-image)

### **Software Components**

1. **Mobile Frontend (Client Side)**
   - **Objective:** Provide a user-friendly interface for buyers and sellers on mobile devices.
   - **Technology/Framework:** Flutter for iOS and Android

2. **Backend Services**
   - **Objective:** Manage business logic, database interactions, and serve data to the mobile app.
   - **Technology/Framework:** Python (Server), Firebase Realtime Database (Database)

3. **APIs (Application Programming Interfaces)**
   - **Objective:** Enable communication between the mobile app and backend services.
   - **Technology/Framework:** RESTful APIs, returning data in XML format using standard HTTP methods (GET, POST, PUT, DELETE) for CRUD operations.

4. **User Authentication & Authorization**
   - **Objective:** Secure user logins, registrations, and access control.
   - **Technology/Framework:** Firebase Authentication

5. **Push Notification Service**
   - **Objective:** Send notifications for wish-listed items, updates, etc.
   - **Technology/Framework:** Firebase Cloud Messaging (FCM)

6. **Image & Content Storage**
   - **Objective:** Store images, descriptions, and user-related content.
   - **Technology/Framework:** Firebase Cloud Storage

7. **Local Data Storage**
   - **Objective:** Store temporary app data and user preferences locally.
   - **Technology/Framework:** SQLite

8. **Geolocation Services**
   - **Objective:** Enable location-based features within the app.
   - **Technology/Framework:** Use packages for geolocation in Flutter like ‘geolocator’

