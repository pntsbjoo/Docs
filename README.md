# Docs
Documentation

0 Common tasks
	-Set UIs
	-Network Status Check
	-Prepare view transitions

1 Login + Splash
	1.1 Auto Login Check (UserDafaults)
	1.2 Data Verification with Regular Expressions
	1.3 View Transition
	1.4 Request Login to the server
	1.5 Ask for Notification permission
	1.6 Adjust Splash Image

2 SignUp + Organization TableView
	2.1 Data Verification with Regular Expressions
	2.2 Phone Number Authentication
	2.3 Select Organization
	2.4 Agreement of Clauses
	2.5 Retrieve and Display the list of organizations 
		-> Save the list in the local storage to prevent duplicated actions
	2.6 Get and set the types of user 
	2.7 Send the data to the server and receive the result
	2.8 Depending on the result, move to homeVC or Pop the alert up

3 Views for the First user
	3.1 Take the list of Organization and display
	3.2 Request the permission to the user to fetch HealthKit data
	3.3 Set proper UIs based on the data
	3.4 After setting the time up, the result should be stored in the UserDefaults
		-> to get ready for the notification
	3.5 Save, and delete interested Symptoms 
	3.6 Alert time limitation(11:35pm ~ 00:25am)

4 View before getting the test
	4.1Five cases for the view

5 Test View
	5.1 Third-Party library for the timer
	5.2 Send the test result to the server

6 History View
	6.1 CollectionView for the selection of the date
		6.1.1 Flexibly resizing the view (Gradually changed)
		6.1.2 Attach a label under the today’s collectionViewCell
		6.1.3 Setting Colour
		6.1.4 Third-Party library for the Calendar
		6.1.5 Calculate & display the Month, date and day of the week
	6.2 Bar graph
		6.2.1 Pop the informationView up by clicking the button
		6.2.2 Obtain the date for the bar from the server
		6.2.3 Draw the graph
		6.2.4 Present the average line(Dotted line)
	6.3 Additional Test
		6.3.1 Essential data : Number of the selected additional tests and their scores
	6.4 Diary
		6.4.1 Get the data from the server and put it into the textField
	6.5 Log
		6.5 Fetch and display the data based upon received the permissions

7 Settings
	7.1 User Data forwarded from the server
	7.2 Only the phone number should be modified as requested
	7.3 Leave(Move to the Login View) + Logout(Deactivate AutoLogin)

8 Alert
	8.1 Local Notification + Remote Notification(Use Firebase???)
	8.2 TableView+Cell(Fixed Cell height???)
	8.3 PopupVIew

9 Etc.
	9.1 
