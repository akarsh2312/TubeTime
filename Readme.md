# Videotube

Videotube is a complex backend project built with Node.js, Express.js, MongoDB, Mongoose, JWT, bcrypt, and more. It serves as the backbone for a video hosting website similar to YouTube, equipped with features like user authentication, video upload, like/dislike, comments, subscriptions, and more.

The Videotube project includes a powerful aggregation pipeline designed to extract relevant information from the MongoDB database. This pipeline is crafted to efficiently process and transform data, providing valuable insights for various functionalities within the video hosting platform.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (JSON Web Tokens)
- bcrypt

## Features

### User Management:

- Registration, login, logout, password reset
- Profile management (avatar, cover image, details)
- Watch history tracking

### Video Management:

- Video upload and publishing
- Video search, sorting, and pagination
- Video editing and deletion
- Visibility control (publish/unpublish)

### Tweet Management:

- Tweet creation and publishing
- Viewing user tweets
- Updating and deleting tweets

### Subscription Management:

- Subscribing to channels
- Viewing subscriber and subscribed channel lists

### Playlist Management:

- Creating, updating, and deleting playlists
- Adding and removing videos from playlists
- Viewing user playlists

### Like Management:

- Liking and unliking videos, comments, and tweets
- Viewing liked videos

### Comment Management:

- Adding, updating, and deleting comments on videos

### Dashboard:

- Viewing channel statistics (views, subscribers, videos, likes)
- Accessing uploaded videos

### Health Check:

- Endpoint to verify the backend's health

## Installation and Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Hruthik-28/youtube-twitter.git
    ```

2. **Install dependencies:**

    ```bash
    cd youtube-twitter
    npm install
    ```

3. **Set up environment variables:**
    Create a .env in root of project and fill in the required values in the .env file using .env.sample file

4. **Start the server:**

    ```bash
    npm run dev
    ```

## Contributing

If you wish to contribute to this project, please feel free to contribute.