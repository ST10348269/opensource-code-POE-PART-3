# opensource-code-POE-PART-3
An android budgeting and expense tracking application developed as part of the group members Finsta — Open Source 2025 Our yOUtUBE video link : https://youtu.be/fBQqI8xsUGg?si=gjJ6HXk4UOYRYZjF  Finsta is an Android budgeting and expense-tracking application developed as part of the Open Source 2025 Project. The app was created by Group 2 members:

Makhado Makatu (st10345844)
Talifhani Malotsha (st10359475)
Mampotse Ramonyai (st10348269)
Tebogo Ramagoshi (st10396455)
The purpose of the application is to assist users in managing their personal finances by providing an easy-to-use digital tool that allows them to record, track, and analyze their daily income and expenses. The app aims to make financial management simpler, more efficient, and more accessible for users of all ages.

The Finsta Your Money app provides several core features designed to help users take control of their spending habits. These include the ability to add, view, edit, and delete income and expense entries; display real-time financial summaries on a dashboard; group transactions by category; and track spending progress against monthly goals. The application also includes user authentication through email and password, ensuring secure access to personal financial data.

All user data is stored locally using an SQLite database, which allows the app to function even when offline. For authentication, Firebase Authentication API is integrated to handle registration and login securely. The app also uses MPAndroidChart to create visual graphs and charts that display financial data in a way that is clear and easy to interpret.

When a new user opens the app for the first time, they are required to register an account using their email and password. This information is verified using Firebase Authentication. Once logged in, the user is directed to the dashboard, which displays a summary of total income, total expenses, and remaining balance. The dashboard also provides visual insights, such as a pie chart that breaks down expenses by category.

The user can add new transactions by clicking the add button. Each transaction includes details such as the amount, date, category, and whether it is an income or an expense. Users can later update or delete any transaction as needed. The budget tracking feature allows users to set monthly financial goals. The app continuously monitors spending against these goals and provides alerts when the user is close to exceeding their set budget limit.

Data visualization plays a key role in the Finsta app. The analytics section generates charts that show users how their spending patterns change over time. This enables users to make better financial decisions and manage their money more effectively.

The Firebase Authentication API serves as the main API used in this application. It ensures that all login and registration processes are secure and that user credentials are verified correctly. The overall process flow can be summarized as follows: the user interacts with the Smartify Your Money app, which communicates with Firebase Authentication to validate the login information and then returns a secure response that grants the user access to their personalized dashboard.

The project was developed using Android Studio, primarily with Java and XML for the front-end design and SQLite for local data storage. MPAndroidChart was used for creating the graphical representations of user data.

To run the application, a user can clone the repository from GitHub and open it in Android Studio. After allowing Gradle to sync, the app can be launched on either a physical Android device or an emulator. The user can then register using their email, log in, and begin managing their budget.



This project forms part of the OPSC6312 Practical Outcome Evaluation (POE) and demonstrates the use of modern Android development practices including Firebase Authentication, Room database, Data Binding, and MVVM architecture.


App Overview

FinSmart provides an all-in-one platform for users to record their daily expenses, create budgets for different categories, and view a clear summary of their financial progress. The app promotes responsible spending through reminders and visual insights, while offering a personalized experience with user profiles and settings.

It is designed for simplicity and efficiency — ideal for individuals who want to make smarter money decisions every day.

Main Features

1. User Authentication

FinSmart uses Firebase Authentication for secure sign-up, login, email verification, and password reset functionality. This ensures user data protection while making the app accessible across multiple devices.

2. Dashboard & Home Fragment

The home screen provides a quick summary of the user’s financial status — including total income, total expenses, and remaining budget. Visual progress bars and summaries help the user monitor their spending habits at a glance.

3. Expense Management

Users can easily add, edit, and delete expenses. Each expense can be categorized, and the app provides a detailed breakdown by category. This is supported by Room Database, ensuring that all entries are stored locally and persist even when the app is closed.

4. Budgets and Accounts

The Budgets fragment allows users to create monthly budgets for specific categories (e.g., food, transport, entertainment). The Accounts section helps users track multiple income sources or wallets.

5. Monthly Goals

FinSmart encourages users to set
