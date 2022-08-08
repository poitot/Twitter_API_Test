### Twitter API Test

Using node + express to handle serving static assets (HTML, CSS)

Main HTML web pages created with only HTML, CSS with Bootstrap 5, with porting to make use of React after main features are completed on the backend and tested.

# Features (Planned)

1. Show a users liked tweets
  - Get username from input
    - find user ID for querying API
  - Use Twitter API to retrieve users liked tweets
  - Pass JSON to front-end to render tweets for user


2. Save a Video or GIF found on twitter
  - Get tweets URL from input
  - Query API to check that the tweets contains a video
  - Retireve video url
  - Embed video on page for user to verify that the correct vieo was retrieved
  - Display URL to allow user to download
  
  3. ...

# Potential Features

1. Provide a different UI for browsing Twiiter
2. Integrate Web Assembly into the project using RUST to allow a client to edit videos locally in their browser and save as a file using FFMPEG, to add new audio or stitch videos together
