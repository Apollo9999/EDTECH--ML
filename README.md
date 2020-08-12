# EDTECH--ML

Our solution to the problem is EDTECH or EDTECHPortal. It is an online learning platform where teachers can conduct virtual classes, quizzes and can even generate automatic notes for distribution.
EDTECH also caters to the students living in the remote geographical locations or slow internet with ‘Low Bandwidth Lecture Streaming’ feature


## Features

- Real time WebRTC based teaching solution
- Support for students with low bandwidth connection, i.e. **low bandwidth mode**
- Automatic transcript generation
- In built proctoring support
- Equipped with functionality to take quizzes/assesments
- Automatic lecture notes generation

## What is low bandwidth mode

Most of the students are not endowed with a high bandwidth internet connection. These students are then particularly not able to take advantage of realtime online classes. Low bandwidth mode solves this problem by -

- Sending stil images from the live stream every 3 seconds instead of full stream
- To account for lost audio, live transcription will of teacher will be sent to user

## Tech Stack used

1. NodeJS
2. React JS
3. Python
4. Azure - Cognitive Services, Functions and Blob Storage
5. MongoDB



## Running the project locally

1. [Deploy the azure function](/pdf)
2. Start the backend servers
   - Set mongoDB URI in config folder

```cmd
cd backend
npm install
npm install -g peer
peerjs --port 9000 --key peerjs --path /myapp
npm start
```

3. Start the front end server

```cmd
cd website
npm run start
```

4. Go to [http://localhost:3000](http://localhost:3000) 

