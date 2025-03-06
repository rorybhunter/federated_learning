# federated_learning

Federated Learning for Osteoporosis diagnosis
Rory Hunter
University of Glagsow
Level 4 Project

Currently, the dataset is extremely small and the highest accuracy is around 60%, which is achieved after as little as 3 rounds as well as 50 rounds. The test loss increases almost immediatley after round 1.

The plan is to get the model to a reasonable percentage then use semi supervised techniques to improve it more i.e. predict on unlabelled images and use the ones with the highest confidence to train the model again and improve the test accuracy.

I have been running the code on Kaggle as a notebook using T4 GPU x2
