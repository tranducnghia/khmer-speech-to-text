
# Khmer Speech-to-Text Project

This project includes an Android app for converting Khmer speech (audio file) into text using Google Cloud Speech-to-Text API.

## Android App
- Allows users to select an audio file and send it to the server.
- Displays the transcription result from the server.

## Flask Server
- Receives audio file from Android.
- Sends the file to Google Cloud Speech-to-Text API.
- Returns the transcription result in Khmer language.

## Setup Instructions
1. **Android Setup**:
    - Import the Android project into Android Studio.
    - Ensure you have the necessary dependencies (OkHttp, etc.).
    - Add permissions for `RECORD_AUDIO` and `READ_EXTERNAL_STORAGE`.

2. **Server Setup**:
    - Install Flask and `google-cloud-speech`.
    - Set up the Google Cloud credentials as `credentials.json`.
    - Run the server on your local machine or deploy it to a cloud service.

3. **Running the Project**:
    - Run the Flask server.
    - Build and run the Android app.

Happy coding!
    