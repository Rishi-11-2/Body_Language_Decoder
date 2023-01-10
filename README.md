# Body_Language_Decoder
A model trained for recognising custom body poses
Mediapipe Holistic is used for extracting facial and body landmarks.
The coordinates of these landmarks are stored in 'coords.csv'.
Then sklearn is used to train various models out of which 'RandomForestClassifier' gave the best result
