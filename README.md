# FaceRecognizer
Face detection and recognition using python and openCV


## About
- This is the desktop application used for face recognition and face detection.
- This is used with FaceRecognitionServer(OMOD).

### Usage
- Deploy FaceRecognizerOMOD in OpenMRS.
- Use this as Client.
  - It will start server. Use train and predict endpoints.
  - Bahmni need to invoke train endpoint with UUID while registering a patient.
  - Temperature sensor will invoke the predict to get the UUID of recognized patient and send the temperature to Bahmni.

