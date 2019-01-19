# image-content-detection-android

An experimental Android application that utilizes [Google Cloud Vision API](https://cloud.google.com/vision/) to analyze the content of image taken by the camera. This implementation tries to detect labels and faces, but can be extended to detect for example text, logos, style, etc. 

The result of the analysis is represented both graphical and by sound using [Android TextToSpeech](http://developer.android.com/reference/android/speech/tts/TextToSpeech.html), to show that this type of application can be used to help blind people experience it's surroundings.

# Usage

If you want to try this application out, all you have to do is to create a project in [Google Developer Console](https://console.developers.google.com/) and enable the [Vision API](https://cloud.google.com/vision/). When done, you have to create a new API key. A detailed guide how to do this can be found in [Vision API Quickstart guide](https://cloud.google.com/vision/docs/getting-started).

Once you've obtained the API-key, set it in the utilities/Constants.class in the project along with a application name:
```java
public class Constants {

    public static final String CLOUD_VISION_API_KEY = "YOUR-API-KEY-HERE";
    public static final String APPLICATION_NAME = "NAME-OF-APPLICATION";

}
```
<table>
<tr>

<th><img src="https://github.com/Aayushpatel007/IHACK-VISIONAPI/blob/master/out2.jpeg" width="670" height="540"></th>
</tr>
<table>

<table>
<tr>
<th><img src="https://github.com/Aayushpatel007/IHACK-VISIONAPI/blob/master/out1.jpeg" width="670" height="540"></th>

</tr>
<table>
