# Collision-Prediction-Based-On-Semantic-Relations

In this thesis, a model developed to predict collision based on the predicted trajectory.
It aims to predict the trajectory of multiple objects in the scene and detect
the collision. For this purpose, in the SUMO driving behaviour of the ego vehicle
and object vehicles are generated. The training and testing scenes generated, in
addition to that collisions are incorporated in the scenes. After that, data pre-processed in the form of a semantic entity-relationship model. Subsequently, that
data fed to various neural network models such as Recursive forecast LSTM and
Encoder-Decoder LSTM.
Based on the obtained results the mean absolute error is minimal for the semantic
entity relationship’s based LSTM encoder-decoder model, hence this model selected for collision prediction.
Finally, the selected model tested on various collision probable scenarios. The
outcome of the test results shows that the model detects the collision priorly in
the given scenario successfully.

## Programming languages
Python (scikit-learn, numpy, pandas)

## Framework & Software
TensorFlow, Keras, SUMO

## Authors
- Rakesh Allampally - Main Contributor - @ra-171967


## License
To be determined.

