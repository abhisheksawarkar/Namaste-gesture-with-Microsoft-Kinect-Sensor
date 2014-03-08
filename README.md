Namaste-gesture-with-Microsoft-Kinect-Sensor
============================================

Namaste is an Indian gesture done when greeting someone for the first time
The code identifies this gesture with Microsoft kinect Sensor written in C# in Visual Studio
It makes use of certain functions which help in calculating the depth distance data for recognizing the gesture.
It uses open source Microsoft Kinect SDK library which contains methods for skeleton tracking.
One can utilize this data to find position of centre of shoulder, and centre of both wrists.
A namaste can be notified when the distance between centre of right wrist, centre of left wrist and shoulder centre 
is less than certain threshould value.
