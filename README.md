
# Idea Bloom

Idea Bloom is a full-stack web application designed to foster idea sharing and discussions. Built using React 19, Express.js, Node.js, and MongoDB, it provides an interactive platform where users can post their thoughts and engage with others through comments.

## Features
- User Authentication: Users can easily sign up and log in.
- Post Creation: Users can write and share posts on different categories.
- Comment System: Anyone can comment on posts, fostering discussions.
- Dark & Light Mode: Users can switch between dark and light mode for a better experience.

## Tech Stack
- Frontend: React 19, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: Clerk Authentication
- Tools: Postman (for testing), ImageKit.io (for image uploads)

## Installation & Setup
1. Clone the repository:
```
git clone https://github.com/yourusername/idea-bloom.git
cd idea-bloom
```
2. Install dependencies:

```
cd client 
npm i -f
```
```
cd backend
npm i
```
3. Set up environment variables (create a .env file in the root directory for the backend and in the client directory for the frontend, then add the required variables).

4. Start the backend server:
```
cd backend
npx nodemon index.js
```
5. Start the frontend:
```
cd client
npm run dev
```

## Contributing

If you would like to contribute to Idea Bloom, feel free to fork the repository and submit a pull request.
