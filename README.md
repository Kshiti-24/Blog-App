# Blog Website (React + VITE)

**Blog Website** is a feature-rich React application designed to provide a seamless blogging experience. This repository houses the source code for Blog Website, a powerful platform offering user authentication, secure signup, login functionalities, and CRUD operations for creating, editing, and deleting blog posts.

## Sign-up Page

![2024-07-14](https://github.com/user-attachments/assets/eb005b60-2ad2-4567-a844-d9f3cf73c714)

## All Post Page

![2024-07-14 (2)](https://github.com/user-attachments/assets/bfd2c650-d272-4682-a935-9768c2c4cafc)

## Add Post Page

![2024-07-14 (3)](https://github.com/user-attachments/assets/6586f7f0-6670-4549-b60b-897b834fb0da)

## Post Page

![2024-07-14 (4)](https://github.com/user-attachments/assets/59177b7d-da5a-4b07-9c57-6681da4f6777)

## Edit Post Page

![2024-07-14 (5)](https://github.com/user-attachments/assets/c0d85013-fb15-4d04-b8e2-502210b7f105)



## Features

- **Register**: New users can sign up to create an account.
- **Login**: Registered users can log in to access their account.
- **Show Others' Posts**: Users can view posts made by other users.
- **Add Post**: Users can create and publish new blog posts.
- **Delete Post**: Users can delete their own posts.
- **Like Post**: Users can like posts to show appreciation.
- **Comment on Post**: Users can leave comments on posts.
- **View User Profile**: Users can view their profile and other users profiles.
- **Logout**: Users can log out of their account.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **Redux**: A state management library for JavaScript apps.
- **Appwrite**: An open-source backend server.
- **TailwindCSS**: A utility-first CSS framework for rapid UI development.
- **Vite**: A fast front-end build tool.
- **Vercel**: A platform for frontend developers, providing global deployment.

## Getting Started

### Prerequisites

Ensure you have the following installed on your local machine:

- Node.js
- npm (Node Package Manager)
- Appwrite backend setup

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/blog-website.git
    cd blog-website
    ```

2. Install dependencies:
    ```bash
    npm install
    ```
    
3. Provide necessary environment variables to run the app properly:
    ```bash
    VITE_APPWRITE_URL='YOUR_APPWRITE_URL'
    VITE_APPWRITE_PROJECT_ID='YOUR_APPWRITE_PROJECT_ID'
    VITE_APPWRITE_DATABASE_ID='YOUR_APPWRITE_DATABASE_ID'
    VITE_APPWRITE_COLLECTION_ID='YOUR_APPWRITE_COLLECTION_ID'
    VITE_APPWRITE_FEEDBACK_COLLECTION_ID='YOUR_APPWRITE_FEEDBACK_COLLECTION_ID'
    VITE_APPWRITE_BUCKET_ID='YOUR_APPWRITE_BUCKET_ID'
    VITE_APPWRITE_API_KEY='YOUR_APPWRITE_API_KEY'
    VITE_TINYMCE_API_KEY='YOUR_TINYMCE_API_KEY'
    VITE_EMAILVERIFICATION_URL='YOUR_EMAILVERIFICATION_URL'
    ```

4. Run the app:
   ```bash
   npm run dev
   ```
   
5. Open your browser and navigate to:
    ```
    http://localhost:3000
    ```
