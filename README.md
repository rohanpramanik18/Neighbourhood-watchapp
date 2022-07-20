# Neighbourhood-watchapp
Crime Prediction and IOT based Garbage Tracking App

Features
1. Users can report crime.
2. See crime reports submitted depending upon their current location and only those reports in his/her area will be visible.
3. View news from news api on current location of the user.
4. Chat anonymously with neighbours from the same neighbourhood logged into the app.
5. Users can select on the map to report a crime or select current location as a measure for generating valid report.
6. App is connected with firebase, so crime reports and chats are maintained forever.
7. Since chats are inserted in firebase, they can be monitored and moderated by an admin.
8. Users can read the top headlines of Indian news using news api
9. Upload media evidence to the firebase database storage
10. Retrieve the images uploaded as part of evidence for the crime reports in your area tab
11. Users can check the garbage tracking module
12. Connected the realtime firebase database with the IOT ESP8266 NodeMcu and Arduino Uno along with ultrasonic sensor to measure the capacity of the trash in the bins
13. Depending upon the fetched realtime metric app displays the circular progress bar indicating the percentage of capacity available / occupied
14. Admin entity authentication and moderation (delete reports that are fake) added
15. Crime prediction model that uses data from the reports submitted in app and generate map to show possible crime locations
