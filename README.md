# Overall-Driving-Behavior-Recognition-By-Smartphone
Overall Driving Behavior Recognition By Smartphone

Monitoring and evaluating of driving behavior is the main goal of this paper that encourage us to develop a new system based on Inertial Measurement Unit (IMU) sensors of smartphones. In this system, a hybrid of Discrete Wavelet Transformation (DWT) and Adaptive Neuro Fuzzy Inference System (ANFIS) is used to recognize overall driving behaviors. The behaviors are classified into the safe, the semi-aggressive, and the aggressive classes that are adopted with Driver Anger Scale (DAS) self-reported questionnaire results. The proposed system extracts four features from IMU sensors in the forms of time series. They are decomposed by DWT in two levels and their energies are sent to six ANFISs. Each ANFIS models the different perception about driving behavior under uncertain knowledge and returns the similarity or dissimilarity between driving behaviors. The results of these six ANFISs are combined by three different decision fusion approaches. Results show that Coiflet-2 is the most suitable mother wavelet for driving behavior analysis. In addition, the proposed system recognizes the overall driving behavior patterns with 92% accuracy without necessity to evaluate the maneuvers one by one. We show that without longitude acceleration data, the driver behavior cannot be recognized successfully while the results do not disturb substantially when the gyroscope is not available.

If you are interested to use the attached dataset of smartphone data for Overall Driving Behavior Recognition, please refer to the following references:

Hybrid of Discrete Wavelet Transform and Adaptive Neuro Fuzzy Inference System for Overall Driving Behavior Recognition,
Hamid Reza Eftekhari, Mehdi Ghatee
Transportation Research Part F: Psychology and Behaviour, 58 (2018) 782–796.
https://doi.org/10.1016/j.trf.2018.06.044

A similarity-based neuro-fuzzy modelling for driving behavior recognition applying fusion of smartphone sensors,
Hamid Reza Eftekhari, Mehdi Ghatee,
Journal of Intelligent Transportation Systems: Technology, Planning, and Operations, 2018, in press.
DOI: 10.1080/15472450.2018.1506338
