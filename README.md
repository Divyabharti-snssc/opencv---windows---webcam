# ## Nalanda It Zone 
* ** Project report under Nalanda it on intership program.
  # Name : **Divya Bharti
  # Course : **BSC (5th Semester)
  # Session : (2024-2028)
  # University Roll NUMBER : **(24281200454)
  # University Registration NUMBER : **(24120023228) 
  # College Name : S.N. Sinha College 
  # Institute Name : Nalanda It Zone 
 #  Application ID : (2PFWM0BB)
 #  Project Topic : OpenCV Windows Webcam 

# ## OpenCV Inst & Webcam Launch Guide

An official practical assignment submitted for **Nalanda it zone This project covers installing openCV on windows and running Python script to launch a live webcam.
  
---

## Step 1: Install OpenCV
Open your terminal or command prompt and run:
''' bash
pip install opencv-python 
'''

---

## Step 2: Python Code ('webcam . py')
create a file named 'webcame.py' and past this code:

''' python 
import cv2

# Open default webcam
Cap = cv2.Video Capture(0)

while True: 
     ret.frame = cap.read()
     if not ret: 
        break

      # Show live video
      cv2.imshow('Nalanda IT ZONE') - Webcam ' , frame)

      # Press 'q' to exit
      if cv2. waitKey(1) & 0xFF == ord ('q'):
          break

cap.release()
cv2.destroy AlWindows ()
'''

---

## Step 3. Run Project 

Execute the using this command:
''' bash
Python Webcam. py
 '''
 * Press **'q'** on your keyboard to close the Webcam window.*
Submission Details: ** Nalanda It Zone / Practical Lab assignment and paste this code.

   # Thank You 🌿 

       * Respectful thanks to the teacher for guidance and checking my project file.
        

