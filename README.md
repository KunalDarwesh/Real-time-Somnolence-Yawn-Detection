## Realtime Somnolence & Yawn Detection
Safety of human being is the major concern in vehicle automation. Statistics shows that 20% of all the traffic accidents are due to diminished vigilance level of driver and hence use of technology in detecting Somnolence and alerting driver is of prime importance. Method for detection of drowsiness based on multidimensional facial features like eyelid movements and yawning is proposed. The geometrical features of mouth and eyelid movement are processed, in parallel to detect drowsiness. Harr classifiers and Shape predictor and face landmarks are used to detect eyes and mouth region. Only the position of lower lip is selected to check for drowsiness as during yawn only lower lip is moved due to downward movement of lower jaw and position of the upper lip is fixed. Processing is done only on one of the eye to analyze attributes of eyelid movement in drowsiness, thus increasing the speed and reducing the false detection. Experimental results show that the algorithm can achieve a 80% performance for drowsiness detection under varying lighting conditions.
## Dependencies

1. Python 3
2. opencv (tested with 3.4) 
3. dlib	(tested with 19.18.0)
4. imutils (tested with 0.5.3)
5. scipy
6. numpy
7. argparse

## Demo
https://www.youtube.com/watch?v=q4VCKxLapM0


