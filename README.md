✨ ChitiChat: Your Intelligent Conversational AI
Live Demo: https://chitichat.netlify.app/
Welcome to ChitiChat, a modern, full-stack chatbot application designed to provide intelligent and seamless conversations. Built with cutting-edge technologies, ChitiChat offers a dynamic user experience, powered by Google's Generative AI, secure authentication, and robust data persistence.
🚀 Key Features
Intelligent AI Conversations: Powered by Google Generative AI (Gemini 1.5 Flash), offering natural and context-aware responses.
Secure User Authentication: Robust user registration and login system with bcrypt.js for password hashing and JWT for secure session management.
Persistent Chat History: All your conversations are securely saved and retrieved from MongoDB, ensuring you never lose track of your discussions.
Rich Media Support: Seamlessly upload and display images within your chats using ImageKit.io, enhancing your conversational experience.
Responsive & Intuitive UI: A sleek and modern user interface built with React.js, ensuring a smooth experience across all devices.
Real-time Interaction: Enjoy a dynamic chat experience with streaming AI responses and auto-scrolling to the latest messages.
Full-Stack Architecture: A powerful backend built with Node.js and Express.js handles all API requests, data management, and AI integrations.
📸 Screenshots & Demos
(Consider adding actual screenshots of your deployed application here for maximum impact!)
Homepage: A captivating landing page (as seen with homepage.css) inviting users to get started.
Sign-Up/Sign-In: Secure and visually appealing authentication forms.
Dashboard: A clean dashboard (dashboardPage.css) to start new conversations.
Chat Interface: Dynamic chat bubbles for user and bot messages, featuring avatars (like human1.jpg and bot.png) and image display. The input area includes send (arrow.png) and attachment (attachment.png) icons.
🛠️ Technologies Used
Frontend:
React.js: A declarative, component-based JavaScript library for building user interfaces.
React Router DOM: For declarative routing in React applications.
@tanstack/react-query: For efficient data fetching, caching, and synchronization.
ImageKit.io React SDK: For seamless image uploads and delivery.
React Markdown: For rendering Markdown content in chat responses.
Vite: A fast build tool for modern web projects.
CSS3: For styling and animations, creating a modern dark theme.
Backend:
Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine.
Express.js: A fast, unopinionated, minimalist web framework for Node.js.
MongoDB: A NoSQL document database for flexible and scalable data storage.
Mongoose: An elegant MongoDB object modeling for Node.js.
bcrypt.js: For hashing passwords securely.
jsonwebtoken (JWT): For creating and verifying authentication tokens.
ImageKit.io Node.js SDK: For backend integration with ImageKit.io.
dotenv: For loading environment variables from .env files.
AI & Cloud:
Google Generative AI (Gemini 1.5 Flash): The core AI model for conversational capabilities.
ImageKit.io: Cloud-based media management and optimization.
Netlify: For seamless frontend deployment.
⚙️ Getting Started
To get a local copy up and running, follow these simple steps.
Prerequisites
Node.js (v18 or higher recommended)
MongoDB Atlas account (or local MongoDB instance)
Google Cloud Project with Generative AI API enabled
ImageKit.io account
Installation
Clone the repository:
git clone <your-repo-link>
cd ChatBot


Backend Setup:
cd backend
npm install

Create a .env file in the backend directory with your credentials:
MONGO=<Your MongoDB Connection String>
JWT_SECRET=<A strong, random secret key for JWT>
IMAGE_KIT_ENDPOINT=<Your ImageKit URL Endpoint>
IMAGE_KIT_PUBLIC_KEY=<Your ImageKit Public Key>
IMAGE_KIT_PRIVATE_KEY=<Your ImageKit Private Key>
CLIENT_URL=http://localhost:3000 # or your deployed frontend URL
PORT=3001

Start the backend server:
npm start


Frontend Setup:
cd ../client
npm install

Create a .env file in the client directory with your credentials:
VITE_API_URL=http://localhost:3001/api # or your deployed backend API URL
VITE_GEMINI_PUBLIC_KEY=<Your Google Gemini API Key>
VITE_IMAGE_KIT_ENDPOINT=<Your ImageKit URL Endpoint>
VITE_IMAGE_KIT_PUBLIC_KEY=<Your ImageKit Public Key>

Start the frontend development server:
npm run dev


The application should now be running locally, with the frontend typically on http://localhost:3000 and the backend on http://localhost:3001.
🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.
If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'feat: Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
📄 License
Distributed under the MIT License. See LICENSE for more information.
📞 Contact
Sarthak Porwal - [Your LinkedIn/GitHub Profile Link]
Project Link: https://github.com/sarthakporwal/chatbot
