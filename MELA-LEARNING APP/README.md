# Madarasa Education Learning App (MELA) &nbsp;&nbsp;&nbsp;&nbsp;[APP LINK](https://play.google.com/store/apps/details?id=com.azad.e_learningmadarsha)


## Screenshots

![App Screenshot 1](https://play-lh.googleusercontent.com/xfQXnwnLa8rPATW1ACaX4Mw87BqrtpykWEf7VfMVSFYlSPm9eOk86VVQwjwN1Gt15Q=w1052-h592-rw)
![App Screenshot 2](https://play-lh.googleusercontent.com/OpvtD9klpEVcingTJNt7VdAttNQaUzmaMTgDHBbyPeB_VK437rkUvn1sUBCouP68eKLD=w1052-h592-rw)
![App Screenshot 3](https://play-lh.googleusercontent.com/RoCzMidlUjWWCxYsqdtHEOcZnI6Z_YZyHauC4DLBvYxO6OBOxXkWxNCKcTg99Y4xkvk=w1052-h592-rw)
![App Screenshot 4](https://play-lh.googleusercontent.com/clI80wf7lugEBVDrA8K5H-ah0bxNfRq9R8_8p7BnlWDskrfRXRQ5P07d_1LSTNj9OMI=w1052-h592-rw)
![App Screenshot 5](https://play-lh.googleusercontent.com/8WhtPc0AW_GYpkU9-BrFtZOojhyD9dKHGUGPawiY1i-cVT3mP-P977C1M6RpMDXeQ6c=w1052-h592-rw)
![App Screenshot 6](https://play-lh.googleusercontent.com/hXko074uYgtf8xOrKCNJCtqVR9Y0g5xk4E-dXUnpNrO2yTC1IZI78gbDB-tB1xfHhKWv=w1052-h592-rw)
![App Screenshot 7](https://play-lh.googleusercontent.com/d9LGq2uPeJVTX7zhoh-IIZ2-8cuq2w3tl7T89WRKN2jcbRC8yCFOSpehaTgdqsSy0FI=w1052-h592-rw)
![App Screenshot 8](https://play-lh.googleusercontent.com/8RE39oW0kuUct11KXldnrpXF-G599OKMfi3Ymoqd4C-g1h4FFqpnUk8wskjIeuLOoIk=w1052-h592-rw)
![App Screenshot 9](https://play-lh.googleusercontent.com/hiaiWjfQjfFd1pdy6-ujCfGKN-7ix0HNqfC2XNzJS5PJOVB-rD75P5ljXoeVISnYJdU=w1052-h592-rw)
![App Screenshot 10](https://play-lh.googleusercontent.com/cNsgMPKy6gkhyaFbtNjU9_PTXv0qUqKxa_rOkvH6Wa6-_GIVGdlkTTmJVL_K4ekJFRmc=w1052-h592-rw)


## Overview

**Madarasa Education Learning App (MELA)** is an e-learning platform designed for the Madarasa students of Uttar Pradesh. The app aims to provide accessible and structured learning resources for students, teachers, institutions, and administrators, making education more engaging and inclusive. Originally deployed on the Google Play Store in 2022, I joined as an intern in 2024 and enhanced the app by improving the user interface (UI) design and expanding its functionalities.

## Key Features

### General Features:
- **Splash Screen**: Welcomes users with an engaging splash screen containing the app's logo and name.
- **Multi-language Support**: Users can select their preferred language among Hindi, English, and Urdu.
- **Role-Based Login**: Custom login experiences tailored for:
  - Students
  - Teachers
  - Institutions
  - DMWO (District Minority Welfare Officer)
  - Registrar

### Student Features:
- **Home Page**: Displays notifications, live events, and a subject list (e.g., Hindi, English, Math) where students can download PDFs of study materials by units.
- **Board Circulars**: Access to board and DMWO circulars.
- **Useful Links**: Provides quick access to additional educational resources.
- **Navigation Drawer**: Includes:
  - **Live Classes**: Access live sessions conducted by teachers.
  - **Quizzes**: Participate in quizzes.
  - **General Knowledge (GK)**: Access GK content.
  - **My Profile**: View and manage student details.
  - **Settings**: Change the preferred language.
  - **Logout**: Securely exit the app.
- **Bottom Navigation**:
  - **Home**: Navigate to the home page.
  - **Downloads**: View downloaded PDFs, books, and videos.
  - **Notifications**: Check all recent notifications.

### Teacher Features:
- **Upload PDFs**: Upload study materials and books in PDF format.
- **Upload Videos**: Share lecture videos with students.
- **Live Classes**: Conduct live sessions with students.

### Institution Features:
- **Manage Teachers**: Add or manage teacher accounts.
- **Manage Students**: Add or manage student records.
- **Subject Management**: Upload subjects, videos, and study materials.

### DMWO Features:
- **Manage Circulars**: View and publish new circulars.
- **Manage Institutions**: Add new Madarasa institutions.
- **Upload Videos**: Share educational content with all users.

### Registrar Features:
- **Organize Online Meetings**: Conduct online meetings using Agora for video conferencing.
- **Manage Circulars**: Add and update circulars.
- **Institution Management**: Add and manage Madarasa institutions.

## Technologies Used

- **Java & Kotlin**: For building the core logic and functionalities.
- **Retrofit, OkHttp, and Volley**: For efficient network calls and API integration.
- **Agora SDK**: Integrated for seamless video streaming and real-time communication.
- **Android Jetpack Components**: Leveraged ViewModel, LiveData, and Room for robust architecture.
- **Custom UI Design**: Improved user engagement through optimized layouts and user-friendly interfaces.
- **Backend Integration**: Used various APIs for fetching data related to user login, subjects, notifications, and more.

## Challenges & Solutions

### Understanding the Codebase
- **Challenge**: The app's existing codebase was extensive, making it difficult to understand the data flow.
- **Solution**: I spent time analyzing the code structure, API interactions, and data models, which helped me make informed improvements.

### UI/UX Improvements
- **Challenge**: Enhancing the UI for a better user experience required careful planning and testing.
- **Solution**: I redesigned key screens, ensured responsiveness across devices, and made the app more intuitive for users of different roles.

### Role-Based Navigation
- **Challenge**: Implementing different login panels and dashboards for multiple user roles was complex.
- **Solution**: Created modular fragments and activities, ensuring that each user role had a tailored experience with minimal code duplication.

### API Integration
- **Challenge**: Handling multiple API calls and managing different types of data for various user roles.
- **Solution**: Utilized Retrofit and OkHttp for streamlined API management and implemented error handling to ensure a smooth data flow.

### Video Streaming Integration
- **Challenge**: Implementing Agora SDK for live video sessions and online meetings.
- **Solution**: Researched and integrated Agora's documentation, ensuring low-latency communication and smooth video streaming for live classes and online meetings.

