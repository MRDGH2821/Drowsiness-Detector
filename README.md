# Drowsiness Detector

This project is aimed towards developing a prototype of drowsiness detection system.

This system is a real time system which captures image continuously and measures the state of the eye according to the specified algorithm and gives warning if required.

For DOD the per closure value of eye is considered. So, when the closure of eye exceeds a certain amount then the driver is identified to be sleepy for system, we are using Python language in which we are working on open CV library and D library

Project demo - https://youtu.be/ByVMz_EK_x8

## USAGE

To use the code, copy paste the following line & execute it in your terminal.

```terminal
python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat
```
To use the code with alarm sound use the following line.  Replace ```alarm.wav``` with your favorite alarm tone.

```terminal
python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm alarm.wav
```

