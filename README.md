Model Descriptions	
Model/Algorithm Name:	Description
Random:	Selects a random, valid Mancala move
Smart:	Selects a move that will yield an extra turn; Else selects a random move
20k:	DQN Model trained against Smart AI for 20,000 iterations
30k:	DQN Model trained against 20k Model for 10,000 iterations. Model was initialized from 20k. The 20k adversarial model was not updated at all during training.
40k:	DQN Model trained against its own target network for 10,000 iterations. Both this model and the target model were initiliazed from 30k.
