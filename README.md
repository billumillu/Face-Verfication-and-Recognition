# Face Verification & Recognition | FaceNet

Face recognition problems commonly fall into two categories:

* Face Verification - "is this the claimed person?". For example, at some airports, you can pass through customs by letting a system scan your passport and then verifying that you (the person carrying the passport) are the correct person. A mobile phone that unlocks using your face is also using face verification. This is a 1:1 matching problem.
* Face Recognition - "who is this person?". For example, employees entering the office without needing to otherwise identify themselves. This is a 1:K matching problem.

FaceNet learns a neural network that encodes a face image into a vector of 128 numbers. By comparing two such vectors, you can then determine if two pictures are of the same person. We use FaceNet's pre-trained model.

## Data
Own database consisting of 12 individuals, an image for each.

## Outputs
camera_0.jpg is a picture of Younes.

![](/camera_0.jpg)
### Face Verification
![](/face_ver.jpg)

Gives the output as 'True' or 'False'
### Face Recognition
![](/face_rec.jpg)

Gives the name of the person.
