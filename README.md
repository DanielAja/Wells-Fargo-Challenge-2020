# Self-Calibrating-Machine-Learning-Model
In short, I built a machine learning model that is able to calibrate itself to a user’s specified accuracy percentage, by excluding the lower half of the predetermined effective features and correlation values. This mode has the added benefit of never having to guess if 1, or 2 more features could have removed a large portion of errors, however, due to the linear nature of the calibration system the amount of time it takes is a heavy drawback. It is important to note that this is a one time cost if you choose to save the values it arrives at. Because the model I created has a F1 score > .5 mark (0.5614035087719299) I believe it is suitable for experimental use, however it may require some tweaking before it is ready for commercial use. With quickly self-calibrating machine learning models we may be able to determine relevant data and subsequently arrive at solutions much faster than we would have otherwise. Overall I believe that the process I began here can be utilized to help improve machine learning models already in use.
