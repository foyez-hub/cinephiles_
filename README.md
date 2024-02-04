# Cinephiles

Cinephiles is a feature-rich web application designed for movie enthusiasts. This platform offers a comprehensive movie-watching experience, allowing users to discover, connect, and engage in various activities related to their favorite films.

## Getting Started

These instructions will help you set up and run the project on your local machine.

### Prerequisites

- Git
- PHP (>= 7.3)
- Composer
- MySQL
- Laravel CLI (optional but recommended)

### Installing

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/foyez-hub/cinephiles_.git
    cd cinephiles_
    ```

2. **Switch to Database Branch and Download Database File:**

    ```bash
    git checkout Database
    ```

    Find and download the cinephilesdb file.

3. **Import Database to MySQL:**

    ```bash
    mysql -u username -p database_name < path/to/cinephilesdb.sql
    ```

4. **Install Dependencies:**

    ```bash
    composer install
    ```

5. **Configure Environment:**

    Rename `.env.example` to `.env` and in the  .env file  set  the [ ` DB_DATABASE=cinephilesdb `] .

6. **Generate Application Key:**

    ```bash
    php artisan key:generate
    ```

7. **Run the Laravel Application:**

    ```bash
    php artisan serve
    ```

    Access the application in your browser at http://127.0.0.1:8000.



## Features

### 1. **Movie Exploration**
   - Explore a vast collection of movies spanning different genres.
   - Search for movies based on titles, genres, or actors.

### 2. **Personal Lists**
   - **Favorites:** Curate your list of favorite movies for quick access.
   - **Watchlist:** Plan your movie nights by adding films to your watchlist.

### 3. **Watch Parties**
   - **Create Parties:** Host movie nights and invite friends for a shared cinematic experience.
   - **Join Parties:** Participate in watch parties hosted by your friends.
   - **Live Chat:** Discuss the movie in real-time with friends during watch parties.

### 4. **Friendship Features**
   - **Connect:** Add friends and expand your movie-loving network.
   - **Privacy Controls:** Customize who can view your favorite movies and watchlist.
   - **Notifications:** Receive alerts for friend requests and messages.

### 5. **Meme Contest**
   - **Participate:** Join the meme contest by submitting creative memes based on movie screenshots.
   - **Vote:** Engage with the community by voting for your favorite memes.
   - **Winners:** The meme with the highest votes takes the crown.


-clone the repository
-Download database file cinephilesdb from Database Branch and import to your local mysql server.
-fun folder with [php artisan serve ]  



  
Dive into the cinematic world with Cinephiles! 🎥🍿
