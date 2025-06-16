# Group-Sync
User authentication (login and sign-up) Play music from in a Group Songs will be played according to the highest to lowest votes song in queue Responsive design Toast notifications
Features
User authentication (login and sign-up)
Play music from in a Group
Songs will be played according to the highest to lowest votes song in queue
Responsive design
Toast notifications
Technologies Used
Frontend
React
Vite
Tailwind CSS
Axios
React Router
React Toastify
Backend
Spring Boot
Spring Data JPA
MySQL
Jsoup
WebSockets
Getting Started
Prerequisites
Node.js (v14 or higher)
npm or yarn
Java 21
Maven
Installation
Frontend
Clone the repository:

git clone https://github.com/your-username/music-player.git
cd music-player
Install dependencies:

npm install
# or
yarn install
Create a .env file in the root directory and add your API URL:

VITE_API_URL=https://your-api-url.com
Backend
Navigate to the backend directory:

cd backend
Create a .env file in the backend directory and add your database and frontend URL configurations:

DATASOURCE_URL=""
DATASOURCE_USER=""
DATASOURCE_PASSWORD=""
FRONTEND_URL=""
Install dependencies and build the project:

mvn clean install
Running the Application
Frontend
Start the development server:

npm run dev
# or
yarn dev
Open your browser and navigate to http://localhost:5173.

Backend
Start the Spring Boot application:

mvn spring-boot:run
Building for Production
Frontend
Build the application:

npm run build
# or
yarn build
Preview the production build:

npm run preview
# or
yarn preview
Backend
Build the Spring Boot application:

mvn clean package
The built JAR file will be located in the target directory.

Deployment
Deploy the application to your preferred hosting service.

For Frontend - Vercel

For Backend - Railway
