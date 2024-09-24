# VerbalMin

Objective: To develop a speech processing algorithm using routine patient-nurse verbal communication and evaluate its performance when combined with electronic health record (EHR) data in detecting early signs of cognitive decline.
Method: We analyzed 125 audio-recorded patient-nurse verbal communication for 47 patients from a major home healthcare agency in New York City. Out of 47 patients, 19 experienced symptoms associated with the onset of cognitive decline. An NLP algorithm was developed to extract domain-specific linguistic and interaction features from these recordings. The algorithm's performance was compared against EHR-based screening methods. Both standalone and combined data approaches were assessed using F1-score and Area Under the Curve (AUC) metrics. 
Results: The initial model using only patient-nurse verbal communication achieved an F1-score of 85 and an AUC of 86.47. The model based on EHR data achieved an F1-score of 75.56 and an AUC of 79. Combining patient-nurse verbal communication with EHR data yielded the highest performance, with an F1-score of 88.89 and an AUC of 90.23. Key linguistic indicators of cognitive decline included reduced linguistic diversity, grammatical challenges, repetition, and altered speech patterns. Incorporating audio data significantly enhanced the risk prediction models for hospitalization and emergency department visits.
