🚀 Leads Tracker App
A simple web application to save and manage your favorite leads (URLs) using Firebase Realtime Database.

📂 Project Structure
index.html → Frontend structure

index.css → Styling (optional if created)

index.js → Application logic using Firebase

🔥 Features
Save any URL into a database.

Display the saved URLs dynamically.

Delete all saved URLs with a single click.

Real-time data updates from Firebase.

🛠️ Technologies Used
HTML5, CSS3, JavaScript (ES6)

Firebase Realtime Database

Firebase v11.6.0 Modules

🔧 Setup Instructions
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/leads-tracker.git
cd leads-tracker
Open index.html in your browser. (Ensure a live server or compatible browser setup.)

Firebase Setup

Go to Firebase Console.

Create a new project → Realtime Database → Start in test mode.

Update the firebaseConfig in index.js with your own database URL.

Run the app!

🧠 How it Works
Enter a URL → Click SAVE INPUT → URL is pushed to Firebase DB.

All saved URLs are shown as clickable links.

Click DELETE ALL → Removes all entries from the database.

