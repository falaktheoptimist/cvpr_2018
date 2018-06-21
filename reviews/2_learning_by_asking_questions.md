# Learning By Asking Questions
	Ishan Misra ; Ross Girshick ; Rob Fergus ; Martial Hebert ; Abhinav Gupta ; Laurens van der Maaten

## Summary
A new learning framework which is an extension to visual question answering (VQA) called learning by asking (LBA). Trained/ tested on the CLEVR dataset. It is supposed to be closer to natural learning and it is shown to learn an easy to hard curriculum by itself when learning from the oracle (CLEVR dataset). Given an image I, assume there exists a set of all possible questions Q and a set of all possible answers A. At training time, the learner receives as input: (1) a training set of N images, Dtrain = {I1, . . . , IN }, (2) access to an oracle o(I, q) that outputs an answer a ∈ A given a question
q ∈ Q about image I; and (3) a small bootstrap set of (I, q, a) tuples. The learner receives a budget of B answers that it can request from the oracle. Using these B oracle consultations, the learner aims to construct a function v(a|I, q) that predicts
a score for answer a to question q about image I.

## Strengths
The idea of allowing agent to ask questions seems intuitive and matching to how humans learn

## Notes
They've tested in the synthetic environment setting of CLEVR where there are a limited number of objects and attributes and connections.  

Also read about CLEVR: https://cs.stanford.edu/people/jcjohns/clevr/

Project Page: http://imisra.github.io/projects/lba/index.html 
