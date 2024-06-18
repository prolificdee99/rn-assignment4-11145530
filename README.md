React Native Assignment 4


#Overview
This project is a mobile application built using React Native. The app consists of a login screen (LoginScreen) and a homepage (HomeScreen). The login screen allows users to enter their email and name to log in, while the homepage displays featured and popular job listings.


#Features
Log In Screen
Email and Name input fields: Allows users to input their credentials.
Log In button: Navigates to the homepage upon logging in.
Options for third-party login: Continue with Google, Apple, or other services.
Register link: Redirects users without an account to a registration page.

#Home Page
User Information: Displays the logged-in user's email and name.
Featured and Popular Job Listings: Showcases job opportunities with details such as company name, location, and salary.
Search Bar: Enables users to search for specific jobs.

#Installation
To run this project locally, follow these steps:
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/rn-assignment4-ID.git
cd rn-assignment4-ID
Install dependencies:
npm install
Start the application:
expo start


#File Structure
The project has the following file structure:
LoginScreen.js: Contains the LoginScreen component which renders the login screen.
HomeScreen.js: Contains the HomeScreen component which renders the home page after login.
assets/: Directory containing images used in the application (e.g., Google, Apple, icons).


#Components
LoginScreen.js
The LoginScreen component is a functional React component that renders the login screen. Key elements include:
TextInput fields for email and name.
TouchableOpacity button for logging in.
Links to register and continue with other services.
Various styles to ensure a responsive and visually appealing UI.
HomeScreen.js
The HomeScreen component renders the main screen after logging in. Key features include:
Displaying user information (email and name).
Lists of featured and popular jobs.
Search functionality.
Job listings with detailed information.
Styling
The styles are defined using StyleSheet.create and are tailored to ensure responsiveness across different screen sizes using react-native-responsive-screen. The styles include layout configurations, typography settings, colors, and other design elements to provide a cohesive user experience.

#Screenshots
<!-- Include screenshots of the application here -->


#Navigation
Navigation between screens is managed using React Navigation. In LoginScreen.js, the onPress event handler for the login button uses navigation.navigate('Home') to switch to the homepage.
