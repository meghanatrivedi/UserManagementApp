# UserManagementApp

--->User Management App

This is a simple User Management iOS app built using SwiftUI, SwiftData, and MVVM architecture.
The app is created based on the given UI designs and demonstrates basic CRUD operations, navigation, and clean code structure.


--->What This App Does

* Shows a splash screen when the app starts
* Allows user to log in using a mobile number
* Displays a list of users on the home screen
* Allows adding new users
* Allows updating existing users
* Shows a simple profile screen
* Saves data locally using SwiftData

--->Screens Included

* Splash Screen
* Login Screen (mobile number input)
* Home Screen (user list with search)
* Add User Screen
* Update User Screen
* My Profile Screen


---> Tech Stack Used

* SwiftUI – for UI
* SwiftData – for local data storage
* MVVM – for clean architecture
* NavigationStack – for navigation


--->App Architecture (MVVM)

* Model
    ->Stores user data using SwiftData (@Model)
* View
    ->SwiftUI screens and reusable UI components
*ViewModel
    ->Handles validation, business logic, and data operations
    
    
--->SwiftData Features

* Add new users
* Fetch users using @Query
* Update user details
* Delete users (swipe to delete)
* Uses ModelContainer and ModelContext


---> SwiftUI Concepts Used

* @State
* @Binding
* @Environment
* @Query
* @Observable
* Lists and Forms
* Reusable Views
* Search functionality
* Animations
* Dark Mode support


---> Extra Features

* Real-time search
* Form validation
* Swipe to delete users
* Clean and simple UI
* Supports Dark Mode

---> How to Run the App

* Open the project in Xcode
* Select an iOS 17+ simulator
* Run the app (Cmd + R)


--->Requirements

* Xcode 15 or later
* iOS 17 or later


---> Notes
This project is meant to show:
* Proper SwiftUI structure
* Clean MVVM architecture
* Usage of SwiftData for CRUD operations
* Simple and readable code
