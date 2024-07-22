# 🌟 Magic Land Explorer 🌟

## 🎯 Purpose of the Program
The Magic Land Explorer application allows users to interactively explore various destinations within Magic Land. Users can perform operations such as filtering destinations by duration, finding the destination with the longest duration, sorting destinations by name, viewing the top 3 longest duration destinations, and displaying categories with 'Fantasyland' as a shared location.

## 🚀 How to Run the Program
1. **Clone the repository:**
   ```sh
   git clone <repository-url>

## 🕹️ Interacting with the Application
Once the application is running, follow the on-screen instructions:

# Enter a number (1-6) to choose an operation:

Show filtered destinations: Find destinations with a duration less than 100 minutes.
Show longest duration: Display the destination with the longest duration among all categories.
Sort destinations by name: Sort all destinations alphabetically by their name.
Show top 3 longest durations: Find and display the top 3 longest-duration destinations with their names and durations.
Show categories with 'Fantasyland' as a shared location: List all categories where "Fantasyland" is a shared location.
Exit: Close the application.

## 📋 Additional Information or Notes
## 📦 Dependencies
This program requires the .NET SDK to be installed on your system.
The Newtonsoft.Json package is used for JSON data parsing.

## 🗂️ Data Classes
Category Class: Represents a category with properties for CategoryName and a list of Destination objects.
Destination Class: Represents a destination with properties such as Name, Type, Location, Duration, and Description.

## 🔍 LINQ Query Tasks
Filter Destinations: Finds all destinations with a duration less than 100 minutes.
Longest Duration: Finds and displays the name of the destination with the longest duration among all categories.
Sort By Name: Sorts destinations alphabetically by their name.
Top 3 Duration: Finds the top three longest-duration destinations and shows their names and durations.
Shared Location: Lists all categories that have "Fantasyland" as a shared location.

## ⚠️ Error Handling
The program includes basic error handling to ensure valid inputs and operations.
Attempts to select an invalid menu option will result in an error message indicating the valid range of choices.

## 🤝 Feedback and Contributions
Feedback and contributions are welcome! Please feel free to submit issues or pull requests through GitHub.
