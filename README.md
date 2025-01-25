# TO-DO-Application
This project is a React-based Todo Application with integrated weather information for tasks. It allows users to manage their daily tasks with priority settings and provides weather updates for a specified location.

**Features Implemented
Add Tasks: Users can add tasks with a title, priority (High, Medium, Low), and associated weather data for a specified location.
Mark as Completed: Tasks can be marked as completed or pending.
Weather Updates: Fetches real-time weather data, including temperature, weather condition, and location name, using the WeatherAPI.
Task Priority: Tasks can be categorized into three priority levels.
Local Storage: All tasks are saved in the browser's local storage.
Authentication: Integrated user login/logout functionality.

**Setup and Installation

1)Prerequisites
Ensure you have the following installed on your system:
 -Node.js (version 14 or above)
 -npm or yarn

**Steps to Run

1)Clone this repository:
 -git clone <repository-url>
  cd todo-app

2)Install the dependencies:
 -npm install
 # or
 yarn install

3)Set up your WeatherAPI key:

-Open the TodoApp.jsx file in the src/components directory.
-Replace the placeholder WEATHER_API_KEY with your WeatherAPI key:
-const WEATHER_API_KEY = 'your_weather_api_key_here';
4)Run the application:
 -npm run dev

5)Open your browser and navigate to http://localhost:5173 to view the app.

**Screenshots

-Project Structure

Below is a screenshot showing the project structure:

![Screenshot 2025-01-26 001606](https://github.com/user-attachments/assets/37920b80-ca72-4b2a-a3da-d7d66a3d73a8)
![Screenshot 2025-01-26 001721](https://github.com/user-attachments/assets/b0783e75-b5ba-42cf-94bc-87eb20a4f3ce)
![Screenshot 2025-01-26 001721](https://github.com/user-attachments/assets/90618de3-50fd-4cd1-a9e1-be39e5887994)


-Application UI

1-Task List View

2-Weather Integration

3-Add Task Modal




**Technologies Used

-React.js: For building the user interface.
-Redux Toolkit: For state management.
-Axios: For API requests to WeatherAPI.
-Tailwind CSS: For styling.
-Vite: As the build tool.
-Lucide-react: For icons.

**Future Enhancements

User Authentication with Backend: Extend the current login/logout functionality with backend support.

Task Search and Filtering: Add features for searching and filtering tasks by name or priority.

Enhanced Weather Data: Display additional weather information, such as humidity and wind speed.
