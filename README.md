## Speech Recognition and Response Generation

This project is a comprehensive solution for building interactive voice experiences. It leverages Google Cloud's Speech-to-Text, Text-to-Speech, and Dialogflow APIs to transcribe speech, understand intent, and generate spoken responses.

**Functionalities**

* **Speech Recognition:** Converts an audio file (in mono format) to text using Google Cloud's Speech-to-Text API. (https://cloud.google.com/speech-to-text)
* **Intent Detection:** Analyzes the transcribed text with Dialogflow to identify the user's intent (what they're trying to achieve). (https://dialogflow.cloud.google.com/)
* **Text-to-Speech Conversion:** Generates a spoken response based on the detected intent using Google Cloud's Text-to-Speech API. The resulting audio is saved as an MP3 file. (https://cloud.google.com/text-to-speech)

**Applications**

This project is ideal for building:

* Voice assistants
* Automated customer service systems
* Interactive voice response applications

**Technical Details**

* **Programming Language:** Python
* **Required Libraries:**
    * `google-cloud-speech`
    * `google-cloud-texttospeech`
    * `google-cloud-dialogflow`
    * `io`
    * `os`
    * `pydub`
* **Supported Language:** Lithuanian (lt-LT) (easily adaptable to other languages)

**Using the Project**

1. Replace `"API KEY JSON"` with your actual Google Cloud API key.
2. Update `.flac` files with the path to your audio file.
3. Set up own DialogFlow bot from GoogleCloud.

