# mySRM
This project is a JavaFX-based desktop application designed to provide students with quick access to essential campus information — such as dining menus, class timetables, maps, and student details. It integrates a local SQL database and simple UI components to deliver a smooth user experience.

🧰 Technologies Used
Java (JavaFX)
SQL (Database file: APP_PROJECT_DATABASE.sql)
Static Assets: HTML, CSV, and image files
IDE Recommended: IntelliJ IDEA / Eclipse

📁 Project Structure
proj1/
├── APP_PROJECT_DATABASE.sql   # Database structure & data
├── Dining_Menu.jpg            # Dining hall menu image
├── maps_embed.html            # Map embed for campus
├── mySRM_JavaFXApp.java       # Main JavaFX application
├── student_details.csv        # Student data (CSV format)
├── Time_Table.png             # Timetable image
└── README.md                  # Project documentation

⚙️ Installation & Setup
Clone this repository:

git clone https://github.com/Anjaneya2005/proj1.git
cd proj1
Open the project in your IDE (e.g., IntelliJ IDEA or Eclipse) as a JavaFX project.

Configure JavaFX SDK:

Download JavaFX SDK if not already installed.
Add JavaFX libraries to the project’s module path.
Set up the database:

Import APP_PROJECT_DATABASE.sql into your local MySQL server (or the DBMS you’re using).
Update connection details in mySRM_JavaFXApp.java if required (host, port, username, password).
Run the application:

javac mySRM_JavaFXApp.java
java --module-path "PATH_TO_FX" --add-modules javafx.controls,javafx.fxml mySRM_JavaFXApp
(Replace PATH_TO_FX with your JavaFX SDK path)

🚀 Features
Campus Map: Interactive HTML embed of the campus.
Dining Menu Viewer: Displays Dining_Menu.jpg.
Timetable Viewer: Shows Time_Table.png to students.
Student Data Management: Reads data from student_details.csv.
SQL Database Integration: Uses APP_PROJECT_DATABASE.sql for backend support.

📸 Screenshots
![IMG-20251009-WA0008](https://github.com/user-attachments/assets/7b496853-3af5-4e37-9511-fa69378d7a56)
