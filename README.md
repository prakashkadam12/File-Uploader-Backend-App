# File Uploader Backend App

The File Uploader Backend App is a backend application built using Express.js. It allows users to upload files to the Cloudinary cloud storage service.

## Features

- **File Upload:** Allows users to upload files to Cloudinary.
- **Cloud Storage:** Utilizes Cloudinary for storing uploaded files securely.
- **RESTful API:** Provides a RESTful API for handling file upload requests.

## Setup Instructions

To use the File Uploader Backend App:

1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/file-uploader-backend-app.git
    ```

2. Navigate to the project directory:
    ```sh
    cd file-uploader-backend-app
    ```

3. Install the dependencies:
    ```sh
    npm install
    ```

4. Set up environment variables:
    Create a `.env` file in the root directory and add your Cloudinary credentials:
    ```
    CLOUDINARY_CLOUD_NAME=your_cloud_name
    CLOUDINARY_API_KEY=your_api_key
    CLOUDINARY_API_SECRET=your_api_secret
    ```

5. Start the server:
    ```sh
    npm start
    ```

6. Use the provided API endpoints to upload files to Cloudinary.

## API Endpoints

- `POST /upload`: Uploads a file to Cloudinary. Requires a `multipart/form-data` request with a file field named `file`.
