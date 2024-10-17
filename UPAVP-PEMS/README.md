# UPAVP-PEMS    &nbsp;&nbsp;&nbsp;&nbsp;[APP LINK](https://github.com/imthiyasalamdev/Android-Projects-Archive/releases/tag/%40github%2Frelease-drafter-action)

# Uttar Pradesh Awas Vikas Parishad - Property Estate Management System

This Android application was developed for EMO officers under the **Avas Vikas Yojna** in Lucknow, Uttar Pradesh. The app allows officers to track properties created by the UP Government, upload property images, and capture the property's location using GPS. The application provides different features for **Admin** and **EMO** users, ensuring smooth data management and property tracking.

## Project Overview

### Purpose:
The app is designed to enable **EMO officers** to:
- Visit properties created under government schemes.
- Track property details using GPS (current location) and upload images.
- Manage and monitor properties efficiently through a user-friendly interface.

The app consists of **two modules**:
1. **Admin Module**: Admin users have access to all district data and can monitor the properties uploaded by EMO officers.
2. **EMO Module**: EMO users can upload property data, including images and location information, based on their assigned districts and schemes.

### Features:
- **Admin Login**:
  - View uploaded property images and locations.
  - Access property data across all districts.
  - Monitor property status and uploads by EMO officers.

- **EMO Login**:
  - Select district, scheme, and property category.
  - Upload property images and locations using GPS coordinates.
  - View uploaded property data.

### APIs Integrated:
The following APIs were integrated into the application:
1. **Login API**: For both Admin and EMO login.
2. **District List API**: Fetches the list of districts.
3. **EMO List API**: Fetches EMO officers related to specific districts.
4. **Scheme API**: Fetches schemes available in the district.
5. **Property Search API**: Allows searching for properties based on parameters (district, scheme, EMO, etc.).
6. **Upload API**: Uploads property images and location details.
7. **Display API**: Displays uploaded property images and locations.

### Technical Stack:
- **Android**: Java, Retrofit for API integration, RecyclerView for data display.
- **Backend**: Communicates with the backend via RESTful APIs.
- **Data Management**: Data is managed through backend APIs, and files are uploaded with size validation (maximum 1MB).

## Key Challenges:
1. **Handling Large Datasets**: Initially faced ANR issues due to large property datasets. Resolved by implementing pagination for smooth performance.
2. **API Format Issues**: Some APIs were initially sent with incorrect HTTP methods and parameters in the body. Worked with the API team to ensure the correct format (POST instead of GET).
3. **File Uploads**: Implemented validation to restrict file size and number of files uploaded.

## Key Features Delivered:
- Case-insensitive login for Admin and EMO users.
- Pagination for large datasets in property search.
- Searchable dropdowns for district, EMO, and scheme selection.
- Validation for file uploads (1MB max per file).
- Restricted input fields (Latitude and Longitude non-editable during property uploads).
  
## Final Delivery:
The project was delivered on **September 27, 2024**, after implementing the final set of client-requested changes, which included search validation, non-case-sensitive login, and proper file validation.

## Learnings:
- API integration and handling HTTP methods.
- Implementing pagination for large datasets.
- Debugging using Logcat and resolving app crashes (ANR).
- Effective communication with API teams to resolve format and request issues.

---

## Technologies Used

```plaintext

- Android SDK
- Java
- XML for Layout Design
- Material Design
- Postman
- Shared Preference
- SQLite
- Retrofit
- API
- Google Maps API
- Git for Version Control

```

> **Note**: Due to client confidentiality, the project code is not shared in this repository. This repository only contains documentation related to the project.

 
