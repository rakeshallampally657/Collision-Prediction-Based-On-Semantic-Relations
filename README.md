## Master Thesis at IAV GMBH
![1519855970181](https://user-images.githubusercontent.com/79206625/125457028-b44bc8d9-fdbf-49e6-8ca8-82e4d1db6fa0.png)



# Collision-Prediction-Based-On-Semantic-Relations

## Programming languages
Python (scikit-learn, numpy, pandas)

## Framework & Software
TensorFlow, Keras, SUMO

# Overview
In this thesis, a model developed to predict collision based on the predicted trajectory.
It aims to predict the trajectory of multiple objects in the scene and detect
the collision. For this purpose, in the SUMO simulation software driving behaviour of the ego vehicle
and object vehicles are generated. The training and testing scenes generated, in
addition to that collisions are incorporated in the scenes. After that, data pre-processed in the form of a semantic entity-relationship model. Subsequently, that
data fed to various neural network models such as Recursive forecast LSTM and
Encoder-Decoder LSTM.
Based on the obtained results the mean absolute error is minimal for the semantic
entity relationship’s based LSTM encoder-decoder model, hence this model selected for collision prediction.
Finally, the selected model tested on various collision probable scenarios. The
outcome of the test results shows that the model detects the collision priorly in
the given scenario successfully.

[thesis_presenation.pdf](https://github.com/rakeshallampally657/Collision-Prediction-Based-On-Semantic-Relations/files/6809340/thesis_presenation.pdf)


## Authors
- Rakesh Allampally - Main Contributor - @ra-171967


## License
To be determined.

