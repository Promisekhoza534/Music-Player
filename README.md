🎵 Music Player (Java Swing)

This is a desktop music player application developed using Java (Swing) in IntelliJ IDEA.

The application allows users to register, log in, and manage their own music playlists with full playback controls.

🚀 Features

🔐 User Authentication

Register new users

Secure login system

SQLite database storage

Password hashing for security

🎶 Music Player

Play, pause, stop songs

Next & previous track

Shuffle mode

Repeat mode

📂 Playlist Management

Add songs from your computer

Remove songs

Save playlist to database

Load playlist per user

🔍 Search Functionality

Search songs by name

Reset playlist view

🔊 Volume Control

Adjustable volume slider

⏱ Extra Features

Song progress bar (seek functionality)

Song time display

Double-click to play songs

🛠 Technologies Used

Java (Swing GUI)

SQLite Database (JDBC)

IntelliJ IDEA

Java Sound API

🗄 Database

The application uses a local SQLite database:

users table → stores login details

playlist table → stores songs per user

📸 Screenshots

<img width="479" height="267" alt="image" src="https://github.com/user-attachments/assets/b08a3b4b-2fef-471b-8bc8-f5f785a70a95" />

<img width="973" height="620" alt="image" src="https://github.com/user-attachments/assets/c5cb04e9-068c-4f87-ab2e-440197fd7083" />

<img width="982" height="619" alt="image" src="https://github.com/user-attachments/assets/aa47dddc-0d21-4101-8b51-67c14b2c66aa" />


▶️ How to Run

Open the project in IntelliJ IDEA

Make sure you have:

Java JDK installed

SQLite JDBC driver added

Run the main class:

LoginFrame.main()

Register a new user and log in

📁 Project Structure

LoginFrame.java → Handles login & registration

MusicPlayer.java → Main music player logic

(Your full player includes playlist, search, and playback features )

⚠️ Notes

Supports mainly WAV audio files

Songs must exist on your local machine

Database file: musicplayer.db will be created automatically

💡 Future Improvements

Support MP3 format

Online music streaming

Dark mode UI

Album artwork display

👨‍💻 Author

Promise Khoza
Student Developer | Java & VB.NET Projects
