# Smart-Dental-Kit-The-Future-of-Oral-Hygiene
The smart dental kit designed for personal Dental hygiene monitoring. The kit utilizes an ESP32 cam module, a 3.7V battery, and TensorFlow lite for real-time image classification. This system streams video captured by the camera to a Flutter application in mobile(wireless) for further analysis and user experience.
The Personalized AI-Powered Dental Hygiene Monitoring Kit advances personal dental hygiene with real-time video streaming in a mobile application (wireless) and image classification, improving oral health through its user-friendly interface. The system uses an ESP32 intraoral camera to stream video to the built-in application, where AI algorithms analyze the footage for dental issues like plaque buildup, cavities, gum disease, and oral cancer, providing tailored recommendations based on patient profiles. Dental smart devices facilitate remote consultations by allowing patients to share images, videos, and symptoms with dentists through secure platforms, improving access to care and bridging geographical gaps.
## Components:
ESP32 cam module: This microcontroller integrates processing power, Wi-Fi connectivity, and a camera. It captures video and streams it to the Flutter application.(https://hubtronics.in/t-camera-plue-mpu6050-q298)
9V battery: Powers the ESP32 cam module.
TensorFlow: A machine learning model optimized for the ESP32 cam, responsible for image classification tasks related to Dental hygiene.
LED Light: Enhances image clarity and detail, optimizing diagnostic accuracy during video streaming.
Flutter application: Receives video stream from the ESP32 cam, displays it visually, and utilizes the TensorFlow Lite model for classification.
## Functionality:
Video Streaming: The ESP32 cam captures video of the user's teeth and mouth and streams it to the Flutter application in real time over Wi-Fi in the mobile app.
Image Classification: The Flutter application utilizes the pre-trained TensorFlow Lite model to analyze the incoming video frames and classify them based on dental hygiene conditions (e.g., plaque buildup, and tooth decay).
User Interface: The Flutter application displays the video stream and visualizes the classification results in a user-friendly interface, potentially offering feedback and recommendations for improved dental hygiene.
## Software Setup:
ESP32 development environment: Install Arduino IDE and required libraries for ESP32 development.
TensorFlow Lite: Convert your pre-trained image classification model to a format compatible with TensorFlow Lite on the ESP32 cam.
Flutter development environment: Install Flutter SDK and create a Flutter application to receive video streams and handle image classification.
## Further Development:
Implement feedback mechanisms in the Flutter application based on classification results.
Expand the TensorFlow Lite model for more complex dental hygiene analysis.
## Benefits:
Enhanced Dental Procedures: DentAssist enhances diagnostic accuracy and treatment planning through real-time video streaming and image classification.
Portability: With its compact design and battery-powered operation, DentAssist is suitable for use in various clinical settings, including remote locations.
Improved Image Quality: The addition of LED lighting ensures optimal illumination, resulting in clear and detailed dental images for precise diagnostics.
## Conclusion:
The Smart Dental Monitoring Kit represents a significant advancement in personal dental hygiene monitoring, leveraging real-time video streaming and image classification technologies. With its user-friendly interface and powerful capabilities, this kit has the potential to revolutionize dental hygiene practices and improve overall oral health outcomes.
