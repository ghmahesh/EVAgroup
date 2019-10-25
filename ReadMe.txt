The input file VID_20191020_132419.mpg. 
The output file is video.avi.
Also the file shape_predictor_68_face_landmarks.dat, has to be uploaded to googledrive and its location should be specified in the program, DrawLandmarks. It can be accessed from below utl.

https://github.com/AKSHAYUBHAT/TensorFace/blob/master/openface/models/dlib/shape_predictor_68_face_landmarks.dat


Work completion status so far:
---------------------------------
* Have a 5 seconds original selfie video extracted into frames and also code for converting the frames back to video.
* Used dlib face detector.
* Run a 68-pt landmarks generator on the  faces. (Not aligned).
* Make a video from the frames with unstabilized landmark points.

Work Pending: (Please update this as progress is made):
----------------------------------------------------------
* Align the frames using the method specified in the assignment (refer the notes in the session). Should be easy. (Person-1: Vikas?)
* Run my landmarks code on top of aligned frames instead of directly on the original frames.  (Person-2: Balaji)
* The current selfie video may not have enough tilted face frames. So, please replace it with a your own 5 seconds selfie video so as to have a few tilted face frames, so that face alignment can be noticed. Make sure code still works.  (Person-2: Balaji)
* Use stabilization algorithms as mentioned in the assignment and session notes. (Direct code copy should work with little modifications).  (Person-3: Chaitanya)
* Merge the 3 videos frames side by side to make a 3x size video (all to be of same size, rescale original video if necessary). (Person-4: Jenisha?)
