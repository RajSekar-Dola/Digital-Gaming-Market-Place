# Digital Gaming Marketplace Store

## Description

This is a digital gaming marketplace where users can:
1. *Register and Login*: Users can register an account, log in, and access their personal dashboard.
2. *Browse Online Games*: Users can browse a wide range of games available for purchase, categorized by genre, price, and more.
3. *Add to Cart & Payment*: Users can add games to their cart, complete the purchase, and download the game after successful payment.
4. *Game Reviews*: Users can leave reviews and ratings for games they have played.
5. *Chat with Other Users*: Real-time messaging functionality allows users to chat with other gamers within the platform.
   
The website uses MongoDB for the database, Node.js and Express for backend functionality, and provides an interactive and engaging experience for gaming enthusiasts.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Credits](#credits)

## Installation

To set up and run this project locally, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/RajSekar-Dola/Digital-Gaming-Market-Place.git
    ```

2. Navigate to the project directory:
    ```bash
    cd P2P_FINAL
    ```

3. Install the necessary dependencies:
    ```bash
    npm install
    ```

**Set Up Environment Variables**:
   - Create a `.env` file in the root directory with the following environment variables:

     ```bash
     MONGODB_URI=your_mongodb_uri
     JWT_SECRET=your_jwt_secret
     ```

     Replace `your_mongodb_uri` with your actual MongoDB connection string, and `your_jwt_secret` with a secure, randomly generated string for JWT token signing.


5. Start the development server:
    ```bash
    node app
    ```

   Access the website at [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

1. **User Registration and Login**: Register for an account or log in to view personalized content, games, and cart.
2. **Browse Games**: Navigate through different game categories such as action, adventure, strategy, and more.
3. **Add to Cart and Purchase**: Add games to your cart and proceed with the payment for instant access and download.
4. **Game Reviews**: After playing a game, users can provide feedback and rate the game.
5. **Chat with Other Users**: Use the real-time chat feature to connect with other players and share gaming experiences.


## Features

- **User Registration & Authentication**: Secure login and registration with JWT authentication.
- **Game Browsing**: Search and filter games by category, price, and rating.
- **Add to Cart & Payment**: Users can add games to their cart and complete the checkout process.
- **Game Reviews & Ratings**: Users can rate and review games based on their experience.
- **Real-time Chat**: In-app chat for users to interact with others in real-time.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend**: Javascript, CSS, HTML
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)

## Credits

- This project was created and maintained by [RajSekar-Dola](https://github.com/RajSekar-Dola).
- Game browsing and filtering logic was developed with custom algorithms.
- Real-time chat was implemented using Socket.io to enable seamless communication between users.

