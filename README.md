Typing Speed Test GUI with Password Authentication Using Python

This Python code is a Graphical User Interface (GUI) for a typing speed test with password authentication. It presents users with a simple yet interactive interface to test their typing speed and accuracy while requiring them to enter a username and password for authentication.

Features:

1. Typing Speed Test:
	1.1. The GUI displays a random sentence from a collection of sentences stored in the "sentences.txt" file.
	1.2. Users are required to type the displayed sentence in the input box provided on the screen.
	1.3. The application tracks the time taken to complete the sentence, calculates the accuracy of the user's typing, and displays the words per minute (WPM) achieved by the user.

2. Password Authentication:
	2.1. Before accessing the typing speed test, users are prompted to enter a username and password for authentication.
	2.2. The username is not case-sensitive, but the password is case-sensitive.
	2.3. In the provided code, the username "om" and password "om" are hardcoded for demonstration purposes. You can modify these credentials to suit your needs or implement a more secure authentication system.

3. Password Hashing:
	3.1. To enhance password security, the provided password is combined with a salt (a random string) and then hashed using MD5 encryption before being stored for comparison during authentication.
	3.2. The password is not stored in plain text, which improves the security of the authentication process.

4. Graphical User Interface:
	4.1. The application uses the pygame library to create a simple graphical user interface for the typing speed test and authentication.
	4.2. The GUI displays the typing prompt, the user's input, and the results (time taken, accuracy, and WPM) after completing the typing test.

5. How to Use the Code:
	5.1. Clone the repository and ensure you have Python and pygame installed on your system.
	5.2. Run the Python script containing the provided code.
	5.3. The GUI will prompt you to enter a username and password for authentication. In this version, use the username "om" and password "om" (case-sensitive) for demonstration purposes.
	5.4. Upon successful authentication, the typing speed test will start.
	5.5. A random sentence will be displayed, and you need to type it accurately in the input box.
	5.6. Press "Enter" when you finish typing the sentence.
	5.7. The GUI will then display your results, including the time taken, accuracy percentage, and words per minute (WPM).
	5.8. To reset the test and take it again, click on the "Reset" button.

Please note that this code is for educational and demonstrational purposes and does not provide robust security. In a production environment, consider implementing more secure password authentication mechanisms and avoiding hardcoding passwords.

Feel free to explore and modify the code to add more features or enhance security as needed. Enjoy testing your typing speed and accuracy!
