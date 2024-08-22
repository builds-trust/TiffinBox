# Tiffin Box

The project’s purpose is to provide a platform through which the food ordering and delivery process becomes easy for both the customers and food service providers. It also has an administrator role to manage the customers and food service providers of the application. Our goal is to enhance the overall food experience by providing a platform for effective order tracking and meal management. With features like tracking deliveries in real-time, earning reward points, and easy-to-use dashboards, we aim to make the experience smooth for everyone.

- _Deployment URL_: <https://tiffinbox-csci5709.netlify.app/>


## Getting Started

### Prerequisites

To have a local copy of this project up and running on your local machine, you will first need to install the following:


- [NodeJS](https://nodejs.org/en) `v20.x`
- [npm](https://www.npmjs.com/) `v10.x`
- [JDK](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html) `Java 17`
- [Maven](https://maven.apache.org/)
- [MongoDB](https://www.mongodb.com/products/platform/atlas-database)


### Installing

Clone the Repository

Clone with HTTPS
```bash
 git clone https://github.com/Keval-Gandevia/TiffinBox.git
 ```
OR

Clone with SSH
 ```bash
 git clone git@github.com:Keval-Gandevia/TiffinBox.git
```

### Local Setup - Frontend

```
cd tiffinbox/frontend
npm install
npm run dev
```

Frontend should be running on http://localhost:5173/

### Local Setup - Backend


```
cd tiffinbox/backend/
mvn spring-boot:run
```
The backend should be running on http://localhost:8080/


## Deployment

This app has been deployed on Netlify (Frontend) and Render (Backend).

- Frontend Deployed App URL: https://tiffinbox-csci5709.netlify.app/
- Backend Deployed App URL: https://tiffin-box.onrender.com

Deployment to Netlify

#### 1. Login to Netlify: Sign up or log in at Netlify.

#### 2. Create a New Site:

- Click "Add new site".
- Connect your GitHub account and select your repository.

#### 3. Configure Settings:

- Base directory: frontend
- Build Command: npm run build
- Publish Directory: /frontend/dist
- Deploy: Click "Deploy site".

## Built With

- [React](https://react.dev/) - The JavaScript library used for building the user interface.
- [Vite](https://vitejs.dev/) - The build tool used for faster and leaner development.
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework for rapidly building modern websites.
- [Daisy UI](https://daisyui.com/) - Tailwind CSS component library.
- [npm](https://docs.npmjs.com//) - Dependency Management.
- [Spring Boot](https://spring.io/projects/spring-boot) - The backend framework used
- [Java](https://www.java.com/) - The programming language used
- [Maven](https://maven.apache.org/) - Used as a build tool and for dependency management. 
- [Docker](https://www.docker.com/) - Used for containerization.
- [MongoDB](https://www.mongodb.com/atlas/database) - Database used.

## Acknowledgments
- Spring Boot
- Render
- Docker
- ViteJS
- daisyUI
- Tailwind CSS
- MongoDB Atlas
- Netlify
- Cloudinary