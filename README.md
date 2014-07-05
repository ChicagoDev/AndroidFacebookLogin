Clone Project, then add the facebook sdk as a module in Android Studio. Build and enjoy.

* Make note of the `facebook/build.gradle` file here. You need to overwrite Facebook's build.gradle file with the one in this repository. 

* You need to change the `app_id` value in `res/values/strings.xml` and add your Key Hash to your Facebook app's settings

* The command to generate your key-hash is: `keytool -exportcert -alias androiddebugkey -keystore ~/.android/debug.keystore | openssl sha1 -binary | openssl base64`