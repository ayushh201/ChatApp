# WeChat

## Where every conversation becomes a moment

WeChat is a feature-rich chat application designed to make your conversations seamless, engaging, and memorable. With a focus on real-time interactions and personalization, WeChat elevates the way you connect with others.

## Features

### 1. Friendship Management
- **Add Friends**: Send friend requests to others and build your social circle.
- **Friend Requests**: Recipients can choose to accept or decline friend requests.
- **Becoming Friends**: Once accepted, both users are added to each other's friends list.

### 2. Real-Time Notifications
Get instant notifications for:
- Friend requests received.
- Friend requests accepted.
- Incoming messages.

### 3. Dynamic Chat Updates
- **Message Reordering**: Chats are dynamically reordered based on the latest message, ensuring that the most recent conversations appear at the top.
- **Seen and Unread Messages**: Easily track the number of unread messages for each chat.

### 4. Profile Customization
- **Avatar Management**: Update your profile with high-quality avatars or upload a custom photo.
- **Themes**: Choose from a variety of themes to personalize your app experience.

### 5. Full-Responsive UI
- **Real-Time Communication**: Enjoy smooth, real-time conversations with friends.

## How It Works

### Adding and Messaging Friends
1. Send a friend request to a user.
2. The recipient can accept or decline the request.
3. Once accepted, start messaging your new friend.
4. Receive real-time notifications for new messages and friend activity.

### Chat Features
- Messages are displayed in real-time.
- Conversations are reordered based on the latest activity.
- Track unread messages for each chat.

### Personalization
- Update your profile with avatars or custom photos.
- Apply a theme of your choice to enhance your user experience.

## Installation and Setup

### Prerequisites
- Node.js
- MongoDB
- Any modern web browser

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/ayush/WeChat.git
   ```
2. Navigate to the frontend directory:
   ```sh
   cd frontend
   ```
3. Install dependencies:
   ```sh
   npm i
   ```
4. Navigate to the backend directory:
   ```sh
   cd ..
   cd backend
   ```
5. Install dependencies:
   ```sh
   npm i
   ```
6. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     PORT=5001
     DATABASE_URL=yourmongodbconnecionstring
     JWT_SECRET=anything

     // Cloudinary
     CLOUD_NAME=
     API_KEY=
     API_SECRET=

     // Home URL
     VITE_SITE_URL="http://localhost:frontendport"
     ```
7. Start the backend and frontend servers in two different terminals:
   ```sh
   cd frontend
   npm run dev
   ```
   ```sh
   cd backend
   npm run dev
   ```
8. Open your browser and navigate to:
   ```
   http://localhost:5173
   ```

## Technologies Used
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-Time Updates**: Socket.IO

## Contact
For any inquiries or support, please contact:

- **Email**: ayushsharma131719@gmail.com

Thank you for choosing WeChat! Enjoy connecting with your friends and exploring intelligent features.

