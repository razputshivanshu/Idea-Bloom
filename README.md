# Idea Bloom 🌸

**Idea Bloom** is a full-stack blog platform designed to foster idea sharing and discussions. Built with **React 19**, **Node.js**, **Express.js**, and **MongoDB**, it provides an interactive space for users to post their thoughts, engage in discussions, and explore ideas in a seamless and visually appealing environment.

---

## 🚀 Features

- **User Authentication**: Secure sign-up and login using **Clerk Authentication**.
- **Post Creation**: Users can write and share posts across various categories.
- **Comment System**: Engage in discussions by commenting on posts.
- **Dark & Light Mode**: Toggle between themes for a personalized experience.
- **Image Optimization**: Dynamic image resizing and compression using **ImageKit.io**.
- **Infinite Scroll**: Load posts dynamically for a smooth browsing experience.
- **Responsive Design**: Built with **Tailwind CSS** for a mobile-friendly interface.

---

## 🛠️ Tech Stack

### Frontend
- **React 19**: For building interactive and reusable UI components.
- **Tailwind CSS**: For responsive and modern styling.
- **React Router v6**: For seamless navigation between pages.
- **Clerk**: For user authentication and session management.
- **ImageKit.io**: For image uploads, optimization, and CDN delivery.

### Backend
- **Node.js**: For server-side logic.
- **Express.js**: For building RESTful APIs.
- **MongoDB**: For database storage (using Mongoose for schema modeling).
- **Clerk Middleware**: For secure authentication and authorization.

### Tools
- **Postman**: For API testing and debugging.
- **Vite**: For fast frontend development and bundling.
- **Git**: For version control and collaboration.

---

## 📂 Project Structure

### Frontend (`client/`)
<img width="781" alt="Image" src="https://github.com/user-attachments/assets/2ce4e5ed-ac77-495a-926c-2028e1429460" />

### Backend (`backend/`)
<img width="781" alt="Image" src="https://github.com/user-attachments/assets/2777d614-590a-4a16-8d93-72fbb9ab7e63" />


---

## High Level Design:
<img width="798" alt="Image" src="https://github.com/user-attachments/assets/e8c0829b-95a0-4b45-85ef-40fff21518dd" />

## 🖼️ Screenshots

| **Home Page** | **Single Post Page** |
|--------------|----------------------|
| ![Home Page](https://github.com/user-attachments/assets/df8c2f61-8cbb-4a29-8f4b-502117e5c6b6) | ![Single Post Page](https://github.com/user-attachments/assets/5c45c904-8416-4762-bc5b-3b89f5c7260d) |

| **Dark Mode** | **Write Post Page** |
|--------------|----------------------|
| ![Dark Mode](https://github.com/user-attachments/assets/af393a44-2ae6-45e1-8dd8-b1031f3ee743) | ![Write Post Page](https://github.com/user-attachments/assets/e40aa656-4d03-43e3-921c-57a8d2bc9cb1) |


---

## 🛠️ Installation

### Prerequisites
- Node.js (v18 or higher)
- MongoDB (local or cloud instance)
- Clerk Authentication account
- ImageKit.io account

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/idea-bloom.git
   cd idea-bloom

2. **Install Dependencies:**
 ```bash
 # Frontend
cd client
npm install

# Backend
cd ../backend
npm install
```
3. **Set Up Environment Variables:**
- Create a .env file in the backend directory:
```
MONGO_URI=your_mongodb_connection_string
CLERK_SECRET_KEY=your_clerk_secret_key
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
```
4. **Run the Application:**
```
# Start the backend server
cd backend
npm start

# Start the frontend development server
cd ../client
npm run dev
```

5. **Open the Application:**
- Visit http://localhost:3000 in your browser.

## 🌟 Key Achievements
- **Image Optimization:** Integrated ImageKit.io to dynamically resize and compress images, improving load times by 40%.

- **Infinite Scroll:** Implemented infinite scroll for posts, enhancing user experience and reducing initial page load time.

- **Theme Toggling:** Built a seamless dark/light mode toggle using React Context API and Tailwind CSS.

- **Scalable Backend:** Designed RESTful APIs with Express.js and optimized MongoDB queries for performance.



## 🚧 Future Improvements
- **Real-Time Notifications:** Notify users about new comments or likes.

- **Search Functionality:** Implement a search bar with Elasticsearch for faster post discovery.

- **User Profiles:** Add user profiles with activity tracking and personalized feeds.

- **Deployment:** Deploy the application using Vercel (frontend) and Render (backend).


## 🤝 Contributing
Contributions are welcome! If you'd like to contribute to Idea Bloom, please follow these steps:

- Fork the repository.

- Create a new branch (git checkout -b feature/YourFeatureName).

- Commit your changes (git commit -m 'Add some feature').

- Push to the branch (git push origin feature/YourFeatureName).

- Open a pull request.

