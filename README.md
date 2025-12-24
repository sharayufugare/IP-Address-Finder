# IP-Address-Finder

This is a basic desktop application developed using Java Swing that allows users to find the IP address of a given website URL.
The application uses Java’s built-in networking classes to resolve a domain name into its corresponding IP address.

📌 Features

User-friendly graphical interface (GUI)
Accepts a website URL or domain name as input
Displays the resolved IP address
Handles invalid URLs with error messages
Simple and lightweight desktop application

🛠 Technologies Used

Java
Java Swing (GUI)
Java Networking (java.net.InetAddress)

⚙️ How It Works

User enters a website URL (e.g., google.com) in the input field.
Clicks on Get IP Address button.
The application uses InetAddress.getByName() to fetch the IP address.
The IP address is displayed using a dialog box.
If an invalid URL is entered, an error message is shown.

🚀 How to Run

Clone or download the project.
Open the project in NetBeans / IntelliJ / Eclipse.
Run the ipfinder.java file.
Enter a valid URL and click Get IP Address

