
# Project Description 📝
StudyNotion is a fully functional ed-tech platform that enables users to create, consume, and rate educational content. <br/>
The platform is built using the **MERN stack**, which includes ReactJS, NodeJS, MongoDB, and ExpressJS.


## StudyNotion Aim 📚 
<br/>
1️⃣ A seamless and interactive learning experience for students, making education more accessible and engaging.<br/>
2️⃣ A platform for instructors to showcase their expertise and connect with learners across the globe.<br/>

<br/>
<br/>


## Tech Stack 💻🔧 

## Frontend 🎨 : 
<code title="React.js"><img height="40" src="https://github.com/gunnermay31/-E-learning-platform_MERN_STACK/blob/main/screenshots/Tech%20stack%20logo/react%20ogo.png"></code>
<code title="Vite"><img height="40" src="https://github.com/gunnermay31/-E-learning-platform_MERN_STACK/blob/main/screenshots/Tech%20stack%20logo/Vitejs-logo.png"></code>
<code title="Redux.js"><img height="35" src="https://github.com/gunnermay31/-E-learning-platform_MERN_STACK/blob/main/screenshots/Tech%20stack%20logo/redux-logo.png"></code>
<code title="css"><img height="40" src="https://github.com/gunnermay31/-E-learning-platform_MERN_STACK/blob/main/screenshots/Tech%20stack%20logo/css%20logo.png"></code>
<code title="Tailwind css"><img height="35" src="https://github.com/gunnermay31/-E-learning-platform_MERN_STACK/blob/main/screenshots/Tech%20stack%20logo/tailwind%20css%20logo.png"></code>


## Backend ⚙️ :
<code title="Nodejs"><img height="50" src="https://github.com/gunnermay31/-E-learning-platform_MERN_STACK/blob/main/screenshots/Tech%20stack%20logo/nodejs-logo.png"></code>
<code title="Express"><img height="70" src="https://github.com/gunnermay31/-E-learning-platform_MERN_STACK/blob/main/screenshots/Tech%20stack%20logo/express%20logo.png"></code>


## Database 🛢️ :
<code title="Mongodb"><img height="40" src="https://github.com/gunnermay31/-E-learning-platform_MERN_STACK/blob/main/screenshots/Tech%20stack%20logo/mongodb%20logo.png"></code>

## Cloudinary Integration ☁️
<code title="Mongodb"><img height="40" src="https://github.com/gunnermay31/-E-learning-platform_MERN_STACK/blob/main/screenshots/Tech%20stack%20logo/cloudinary-logo.jpg"></code>

## NPM packages used ☁️
npm i cors
npm i express
npm i mongoose
npm i cookie-parser
npm i jsonwebtoken
npm i cloudinary
npm i dotenv
npm i nodemon
npm i bcrypt
npm i nodemailer
npm i razorpay
npm i node-schedule
npm i express-fileuploader
npm i otp-generator
npm i crypto
npm i concurrently
npm i react-router-dom
npm i react icons
npm install react-router-dom
npm install react-redux
npm install @reduxjs/toolkit
npm install axios
npm install react-hook-form
npm i react-hot-toast

<hr/>




## System Architecture 🏰
<br/>
☝ The StudyNotion ed-tech platform consists of three main components:  <br/>
The front end, the back end, and the database. The platform follows a client-server architecture, with the front end serving as the client and the back end and database serving as the server.

🎨 Front-end  <br/>
The front end of the platform is built using ReactJS, which is a popular JavaScript library for building user interfaces. ReactJS allows for the creation of dynamic and responsive user interfaces also **Loading Skeleton**, which are critical for providing an engaging learning experience to the students. The front end communicates with the back end using RESTful API calls.

⚙️ Back-end  <br/>
The back end of the platform is built using NodeJS and ExpressJS, which are popular frameworks for building scalable and robust server-side applications. The back end provides APIs for the front end to consume, which include functionalities such as user authentication, course creation, and course consumption. The back end also handles the logic for processing and storing the course content and user data.

🛢️ Database  <br/>
The database for the platform is built using MongoDB, which is a NoSQL database that provides a flexible and scalable data storage solution. MongoDB allows for the storage of unstructured and semi-structured data, which is useful for storing course content such as videos, images, and PDFs. The database stores the course content, user data, and other relevant information related to the platform.



## Architecture Diagram 🏗️
<br/>
Here is a high-level diagram that illustrates the architecture of the StudyNotion ed-tech platform:
<img width='60%' src='https://github.com/gunnermay31/-E-learning-platform_MERN_STACK/blob/main/screenshots/Architecture%20Diagram.png' />


<hr/>

#### The front end of StudyNotion has all the necessary pages that an ed-tech platform should have. Some of these pages are: 

For Students:
- **Homepage 🏠:** A brief introduction to the platform with links to the course list and user details and random background.
- **Course List 📚:** A list of all the courses available on the platform, along with their descriptions and ratings.
- **Wishlist 💡:** Displays all the courses that a student has added to their wishlist.
- **Cart Checkout 🛒 :** Allows the user to complete course purchases.
- **Course Content 🎓:** Presents the course content for a particular course, including videos and related material.
- **User Details 👤:** Provides details about the student's account, including their name, email, and other relevant information.
- **User Edit Details ✏️:** Allows students to edit their account details.

For Instructors:
- **Dashboard 📊:** Offers an overview of the instructor's courses, along with ratings and feedback for each course.
- **Insights 📈:** Provides detailed insights into the instructor's courses, including the number of views, clicks, and other relevant metrics.
- **Course Management Pages 🛠️:** Enables instructors to create, update, and delete courses, as well as manage course content and pricing.
- **View and Edit Profile Details 👀:** Allows instructors to view and edit their account details.



### Back-end ⚙️

The back-end of the platform is built using NodeJS and ExpressJS, providing APIs for the front-end to consume. These APIs include functionalities such as user authentication, course creation, and course consumption. The back-end also handles the logic for processing and storing the course content and user data.

Description of the Back-end Architecture:
StudyNotion uses a monolithic architecture, with the backend built using Node.js and Express.js, and MongoDB as the primary database. Monolithic architecture refers to a design approach where all the modules of the application are combined into a single large program, with a single codebase, to enable better control, security, and performance.
Node.js is a popular JavaScript runtime that allows us to run JavaScript code outside of the browser. Express.js is a web application framework that simplifies the process of building web applications in Node.js. MongoDB is a popular NoSQL database that allows for flexible data storage and retrieval, making it a suitable choice for complex applications like StudyNotion.
Features and Functionalities of the Back-end:
The back end of StudyNotion provides a range of features and functionalities, including:
User authentication and authorization: Students and instructors can sign up and log in to the platform using their email addresses and password. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.
Course management: Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.
Payment Integration: Students will purchase and enrol on courses by completing the checkout flow that is followed by Razorpay integration for payment handling.
Cloud-based media management: StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.
Markdown formatting: Course content in document format is stored in Markdown format, which allows for easier display and rendering on the front end.

#### Back-end Features

- **User Authentication and Authorization 🔐:** Students and instructors can sign up and log in to the platform using their email addresses and passwords. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.
- **Course Management 🛠️:** Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.
- **Payment Integration 💳:** Students will purchase and enroll in courses by completing the checkout flow, followed by Razorpay integration for payment handling.
- **Cloud-based Media Management ☁️ :** StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.
- **Markdown Formatting ✍️:** Course content in document format is stored in Markdown format, allowing for easier display and rendering on the front-end.



#### Data Models and Database Schema

The back-end of StudyNotion uses several data models and database schemas to manage data, including:

- **Student Schema 🧑‍🎓:** Includes fields such as name, email, password, and course details for each student.
- **Instructor Schema 👩‍🏫:** Includes fields such as name, email, password, and course details for each instructor.
- **Course Schema 📚:** Includes fields such as course name, description, instructor details, and media content.


### Database 🛢️
The database for the platform is built using MongoDB, a NoSQL database that provides a flexible and scalable data storage solution. MongoDB allows for the storage of unstructured and semi-structured data. The database stores the course content, user data, and other relevant information related to the platform.

<hr/>


## React Hooks 🎣

Utilized several React hooks for efficient state management and dynamic behavior:

- `useState`
- `useEffect`
- `useDispatch`
- `useParams`
- `useSelector`
- `useLocation`
- `useNavigate`
- `useRef`
- `useForm`
- `useDropzone`
- `Custom-Hook`

<br/>

## 📚 **React Library**:

- 🚀 **Lazy Loading**: Enhance performance by lazily loading images using the react-lazy-load-image library.
- 📊 **Chart.js:**  Versatile charting library for creating interactive and visually appealing charts.
- 🎭**Framer Motion:**  Animation library for React, providing smooth and expressive motion.
- 📁 **React Dropzone:**  Drag-and-drop file uploader for React applications.
- 🍞 **React Hot Toast:**  Elegant and customizable toast notifications for React applications.
- 🔢 **React OTP Input:**  Input component for one-time password entry in React forms.
- 📊 **React Super Responsive Table:**  Highly responsive and feature-rich table component for React.
- 🔄 **Swiper:**  Modern touch slider for mobile and desktop browsers.
- 🖋️ **React Type Animation:**  Simple and configurable typing animation component for React.
- 🎥 **Video React:**  React-based video player for building rich multimedia experiences in web applications.


## 📚 **API Design:**:

The StudyNotion platform's API is designed following the REST architectural style. The API is implemented using Node.js and Express.js. It uses JSON for data exchange and follows standard HTTP request methods such as GET, POST, PUT, and DELETE.
Sample list of API endpoints and their functionalities:
/api/auth/signup (POST) - Create a new user (student or instructor) account.
/api/auth/login (POST) – Log in using existing credentials and generate a JWT token.
/api/auth/verify-otp (POST) - Verify the OTP sent to the user's registered email.
/api/auth/forgot-password (POST) - Send an email with a password reset link to the registered email.
/api/courses (GET) - Get a list of all available courses.
/api/courses/:id (GET) - Get details of a specific course by ID.
/api/courses (POST) - Create a new course.
/api/courses/:id (PUT) - Update an existing course by ID.
/api/courses/:id (DELETE) - Delete a course by ID.
/api/courses/:id/rate (POST) - Add a rating (out of 5) to a course.
Sample API requests and responses:
GET /api/courses: Get all courses
Response: A list of all courses in the database
GET /api/courses/:id: Get a single course by ID
Response: The course with the specified ID
POST /api/courses: Create a new course
Request: The course details in the request body
Response: The newly created course
PUT /api/courses/:id: Update an existing course by ID
Request: The updated course details in the request body
Response: The updated course
DELETE /api/courses/:id: Delete a course by ID
Response: A success message indicating that the course has been deleted.
In conclusion, the REST API design for the StudyNotion ed-tech platform is a crucial part of the project. The API endpoints and their functionalities are designed to ensure seamless communication between the front-end and back-end of the application. By following RESTful principles, the API will be scalable, maintainable, and reliable. The sample API requests and responses provided above illustrate how each endpoint will function and what kind of data it will accept or return. With this API design, StudyNotion will be able to provide a smooth user experience while ensuring security and stability.
Deployment:
The deployment process for the StudyNotion ed-tech platform will involve hosting the application on various cloud-based services. The front end will be deployed using Vercel, a popular hosting service for static sites built with React. The back-end will be hosted on Render or Railway, two cloud-based hosting services for applications built with Node.js and MongoDB. Media files will be hosted on Cloudinary, a cloud-based media management platform, and the database will be hosted on MongoDB Atlas, a fully managed cloud database service.
The hosting environment and infrastructure for the StudyNotion platform will ensure scalability, security, and reliability. Vercel provides a fast and scalable hosting environment for the front end, while Render or Railway provide a scalable and reliable infrastructure for the back end. Cloudinary provides reliable storage for media files with features like automatic image optimization and transformation, while MongoDB Atlas provides a highly available and secure database environment with features like automatic scaling and disaster recovery. 

### Frameworks, Libraries, and Tools used: ⚙️

The back end of StudyNotion uses a range of frameworks, libraries, and tools to ensure its functionality and performance, including:
Node.js: Node.js is used as the primary framework for the back end.
MongoDB: MongoDB is used as the primary database, providing a flexible and scalable data storage solution.
Express.js: Express.js is used as a web application framework, providing a range of features and tools for building web applications.
JWT: JWT (JSON Web Tokens) are used for authentication and authorization, providing a secure and reliable way to manage user credentials.
Bcrypt: Bcrypt is used for password hashing, adding an extra layer of security to user data.
Mongoose: Mongoose is used as an Object Data Modeling (ODM) library, providing a way to interact with MongoDB using JavaScript.







