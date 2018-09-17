# ML.AI..Face.Recognition.UsingAzureFaceAPI
Face Recognition and Identification System

This application can be used to train a group with different person faces and enables you to identify the person from a new pictures if the person is in the trained set.


How to Run the application:
1. login to Azure portal
2. create a FACE api service
3. copy the endpoint and the service key
4. Open the .sln from visual studio 2015 or above
5. replace the key and endpoint in the Faceform.cs file
6. run the application after you build(Before building run restore nuget packages).

Create a folder with person name subfolders...place images of the person in each folder. 
Create a group using the root folder.
The browse a new image and use process/identify to identify the person
