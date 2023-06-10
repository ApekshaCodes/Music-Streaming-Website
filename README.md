# Music Streaming Website

This Music Streaming Website is a web application built with Flask that allows users to upload, download, play, and delete songs. It provides a user-friendly interface for browsing and managing a collection of music tracks.

## Features

- Browse and play music: Users can browse through their uploaded songs and play them directly on the web application.
- Search Song: Users can search for a specific song by its name, artist, or album.
- Upload New Song: Users can upload new songs to add them to their collection.
- Delete Song: Users can delete unwanted songs from their collection.
- View All Songs: Users can view all the songs available in their collection.

## Installation

1. Install Python and pip:

   ```
   sudo apt-get update
   sudo apt-get install python3 python3-pip
   ```

2. Clone the repository to your local machine:

   ```
   git clone <repository_url>
   ```

3. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Set up the Flask app environment:

   ```
   export FLASK_APP=app.py
   ```

5. Create a MySQL database:

   ```
   CREATE DATABASE music_streaming;
   ```

   Create the necessary tables by running the SQL scripts provided in the repository (`songs.sql`, `songs_list.sql`).

6. Run the application:

   ```
   flask run
   ```

## Usage

1. Open your web browser and navigate to `http://localhost:5000`.
2. Use the "Play" button to browse and play music tracks.
3. Utilize the search functionality to find specific songs by name, artist, or album.
4. Upload new songs using the "Upload Song" button.
5. Remove unwanted songs from your collection by clicking the "Delete Song" button.
6. To view all the songs in your collection, click the "View All Songs" button.

## Contributing

Contributions to the Flask Music App are always welcome! If you find any bugs, have suggestions for improvements, or want to contribute new features, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as per the terms of the license.
