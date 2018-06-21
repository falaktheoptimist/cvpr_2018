# Embodied Question Answering 
Abhishek Das, Samyak Datta, Georgia Gkioxari, Stefan Lee, Devi Parikh, Dhruv Batra 

## Summary
Embodied Question Answering is an AI task wherein an agent is asked a question. It has to explore the environment, gathering visual data (first person vision) and then answer the question. It has aspects of – natural language understanding, object recognition, active perception, goal based navigation, logical reasoning, and linking language to corresponding actions. Model learning the 4 aspects - vision, language, navigation, answering to map raw inputs - vision and words to answers is based on Adaptive Computation Time (ACT) RNNs by Graves. 


## Strengths
Well defined AI task for small environment
Difference compared to video QA (VQA) in that this allows the agent to move through and interact with the environment and perceive things on its own. 
QA dataset generated programmatically inspired from an older such set called CLEVR. 
Encompasses different aspects - language understanding, vision, RL, navigation
They have provided the data (House3d environment) being used for training and models

## Notes
Has been done in a simulation environment only and navigation isn't as good as per their video. (https://embodiedqa.org/)
v1 focuses on just 4 basic questions: location, color, color_room, preposition. 

Project Page: https://github.com/facebookresearch/EmbodiedQA
