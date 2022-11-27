# EEG Lie Detector

Lie detection has immense application in crime reduction and control. Current lie detectors, such as polygraphs, often use blood pressure, heart rate, respiration, etc., as indicators of stress. In turn, the level of stress of a partipant can be interpretted as the extent to which they are being honest. However, the fact that participants may become stressed despite being telling the truth renders polygraphs unreliable and unacceptable for industrial use.

We set out to create an improved method for lie detection that takes advantage of electroencephalography (EEG). The P300 wave in particular is an event-related potential component that is evoked when a subject is exposed to a stimulus with meaning to them. It is characterized by a positive peak of about 300 ms. Theoretically, if a subject had previous knowledge of a certain stimulus, the P300 signal would be elicited and could be detected.

A dataset of 6,991 human faces was used to create a simulated suspect lineup. In each trial, participants would first view 10 random faces from the dataset. They were then presented with 10 additional faces, 5 of which were chosen randomly from the original list of 10 faces and 5 other random faces from the dataset. As this second set of faces was shown to the participant, EEG data was collected.

EEG data was collected from one male participant using a four-electrode setup. The Fz, Cz, Pz, and Oz electrode positions of the 10/20 system were used for data collection. Noise was limited to 5-8 microvolts.

It is expected that each of the previously-shown faces would elicit a visible P300 signal in the collected EEG data while the new faces would not. The collected data was compared to this expected result to test the accuracy of the detector.
