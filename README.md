# BLIND-ASSIST-CURRENCY-NOTE-DETECTION-ANDROID-APP

## Objective:
The blind assist app can be used to help blind and visually impaired people who suffer from monetary transactions. Initially, we need to scan any Indian currency and upload it to our application. After some image processing is done and certain steps are carried, we can finalize the currency for blind people. After a lot of research, it showed that the proposed system can be used in real-world scenarios to recognize unknown currency paper images with higher accuracy. Our application displays and pronounces the decoded currency to visually impaired people as they cannot read. We aim to provide a fast and efficient way of currency detection alternative to older currency detection techniques.

## Modules:
1. **Image Upload Module:**<br/>
This module is used to upload the desired 	currency note image into the application for processing. This module requires the user to upload the clear image of the currency note whose value is to be detected. The user can feed the image from his/her gallery to the application by using this module.  

2. **Image Detection Module:**<br/>
This module plays a key role in the application. The image fed into the system by the image upload module is processed in this module. The processing of the image is done with the help TensorFlow package. In this module, the input image is deeply processed and the value of the currency is determined precisely. In case, if any other image rather than the currency note is fed the application will inform the user that this is not a rupee note.  

3. **Output Text Module:**<br/>
This module displays the result value of the processed currency note image. This module prints the value of the currency note on the screen. In case if a none rupee  is found, it will print the message that this is not a rupee note.   

4. **Text-to-Speech Module:**<br/>
This module plays a very important role as it enables the application to aid the blind people in recognizing the currency notes. This module converts the text printed in the output text module into a clear speech so that the persons with eye problems can hear the speech and recognize the value of currency notes. Hence this module acts a great tool for the people with eye problems in recognizing the currency notes.

## Sample Screenshots:
![image](https://user-images.githubusercontent.com/61049937/226937520-242df691-6b9e-4fda-b285-ddf2c14153d0.png)

## Steps to Run the project:
1. Import the project in android studio.
2. Complete the gradle sync.
3. Run the project.
