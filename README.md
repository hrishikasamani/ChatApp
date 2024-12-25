## Chat Application

This project builds a one-on-one chat application using Firebase. Users can register, log in, and communicate with other authenticated users in real-time.

## **Features**

### **Authentication**
- **Register:**
  - Create an account by providing your name, email, password, and confirming your password.
  - Validation ensures the email format is correct and passwords match.

- **Login:**
  - Log in securely using your registered email and password.
  - Validation checks for incorrect credentials or non-existent accounts.

- **Logout:**
  - Securely log out of the application.

### **Messenger/Chat**
- **Chat List:**
  - The main screen displays a list of authenticated users (your friends).
  - Tap on a user to start a one-on-one chat.

- **One-on-One Chat:**
  - Exchange real-time messages with friends.
  - Past chats are retained and displayed in the chat view.
  - Messages are styled to differentiate between your messages and your friend's messages:
    - **Your messages:** Right-aligned with a distinct background color.
    - **Friend's messages:** Left-aligned with a different background color.

- **Message Details:**
  - Each chat message includes:
    - Sender's name
    - Message text
    - Date and time of sending

- **Auto-Scroll:**
  - The chat view automatically scrolls to the latest message, ensuring a seamless messaging experience.

## **Getting Started**

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/hrishikasamani/ChatApp
   ```
   
2. **Install Dependencies: (If using CocoaPods):**

   ```bash
   pod install
   ```
   
   If not using CocoaPods, you'll need to manually integrate the Firebase libraries manually through *Package Dependencies*.
   
3. **Run the App:**
   
   Open the project in Xcode and run it on your simulator or device.


## **Usage**

### **Launch the App**
- Upon launching, the app displays the login screen.

### **Register**
1. Enter your name, email, password, and confirm your password.
2. Ensure the password fields match to proceed.

### **Login**
- Use your registered email and password to log in.

### **Chat List**
- View a list of all authenticated users as your friends.
- Select a user from the list to start chatting.

### **Chat Screen**
- Send and receive text messages in real-time.
- The chat screen retains past messages and displays:
  - Sender information
  - Message text
  - Timestamp for each message

### **Logout**
- Use the logout option to exit your account securely.


## **Firebase Integration**

### **Authentication**
- Firebase Authentication is used to securely manage user accounts.

### **Database**
- Firebase Firestore stores:
  - Chat messages
  - User data
- Provides real-time updates for seamless communication.

## **Optional Enhancements**

### **Custom Chat Cells**
- Design distinct table view cells for:
  - Sent messages
  - Received messages
- Improves user experience with visual distinction.

### **Persistent Login**
- Use `UserDefaults` to retain the logged-in state for returning users.

## **Resources**
- **[Auto-Scroll in UITableView](https://medium.com/@casseykeating/scroll-to-bottom-of-uitableview-f46d809e48d9)**
- **[Date and Time in Swift](https://auth0.com/blog/introduction-date-time-programming-swift-1/)**

*Incase of any issues, feel free to reach out to me at my [mail](hrishikasamani@gmail.com)*
