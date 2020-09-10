## Home Security System using Facial Recognition

## About
This system detects and recognizes faces from real-time video and sends image to owner's email if the face is not recognized.


Download the below packages to run this.
## packages needed
  1. opencv
  2. numpy
  3. pillow
  4. smtplib

## There are three steps for face recognition:
  1. Collecting face data (your face pictures) and labels and save to dataset folder. (code 1)
  2. Input face data and labels into model to train a recognition model. (code 2)
  3. Open up your webcam to start real time face recognition. (code 3)

## Instructions:
  1. Download this folder.
  
  2. Crate two empty folders named 'dataset' and 'trainer' in the above folder if not there.
  
  3. Run the first code, enter number '1' (for first person), then computer will take your face pictures and save into 'dataset' folder.
  When finish taking pictures, "[INFO] Exiting Program and cleanup stuff" pops up.
  
  (Run the first code again, enter number '2' (for second person), follow the same procedure.) 

  4. Run the second code, just wait for few seconds to train the model.
  
  5. Run the third code, it will open your camera and start real time face recognition.

  6. If face will show unknown it will send an email to owner's email id.

  7. Dont Forget to change the email id in email_test.py file.

  8. Give your name and mail id in that file only.