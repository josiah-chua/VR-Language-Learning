# VR-Language-Learning

# Introduction
Roleplaying is effective and important for Foreign Language learning. However, current methods of
In-Person Role-playing are manpower intensive, inconsistent in feedback quality, or inconvenient to
access.
The project aims to design a solution that allows users to practise realistic and situationally-based
conversations in a foreign language without needing a practice partner. The solution also provides
feedback on their use of the foreign language to improve their proficiency.
We prototyped a Virtual Reality (VR) app where users can practise role-play with an Artificial
Intelligence (AI) enabled chatbot and receive an automated evaluation of their pronunciation.
This report defines the problem, identifies the stakeholders’ needs and product specifications. It defines
the product functions and the derivation of our final concept. It explains our prototyping method, user
testing of our Minimum Viable Product (MVP), and potential future works.

# App Concept
![image](https://github.com/josiah-chua/VR-Language-Learning/assets/81459293/b0f53f73-f940-45f1-b00b-42381a1621fb)

The App will feature an AI chatbot in a VR environment, represented by a Non-Player Character
(NPC) using preset animations. The chatbot will operate based on a scripted and structured conversation,
however it will accept a range of relevant user responses based on its appropriateness. Other AI models
will be utilised to evaluate the users’ responses and score them. As such, the entire system will be fully
automated.

# VR
**Barebones Animation and graphics for first prototype**
![image](https://github.com/josiah-chua/VR-Language-Learning/assets/81459293/c0010664-d26a-4fcb-b250-fd466164a0d7)
There are 3 interactable NPCs in the prototype. For each NPC, there are 3 subtasks to complete. A script was created to facilitate the dialogue for the tasks.
 
Each NPC initiates a subtask by saying a sentence. Users must then respond to the NPC according to the objective. Note that the app allows for dynamic resposes to allow users to practice sentence formation. The apprporateness of the response will be evaluated using a semantics detection LLM. 

The conversation is guided by a script, written in Spanish. It contains the NPC’s dialogue for each subtask and a list of possible replies from the user as a reference for evaluation of appropriateness.

The prototype script was written in English and translated into Spanish via Google Translate. We then collaborated with CLS and partnered with a Spanish lecturer from NUS Centre for Language Studies to refine the Spanish script to ensure that the sentences were grammatically correct, suitable for our target group and similar to how natives would naturally speak.


# Backend
![image](https://github.com/josiah-chua/VR-Language-Learning/assets/81459293/62aea433-7eea-4afd-abfd-7dc47d41cfc5)
![image](https://github.com/josiah-chua/VR-Language-Learning/assets/81459293/9cc10992-8578-4c0a-a282-f02e21728ee3)

# Testing
We tested our prototype on three Spanish LAS2201 tutorials. We split the Spanish learners equally into 1 test group and 1 control group. 

![image](https://github.com/josiah-chua/VR-Language-Learning/assets/81459293/253273da-1055-4acd-a09b-995739723192)

We enlisted the help of a native Spanish speaker, to do a blind comparison between the student’s voice recordings before and after the roleplay practice as mentioned.

# Results
**User Feedback**
![image](https://github.com/josiah-chua/VR-Language-Learning/assets/81459293/adb86b71-d4ec-4bee-af48-8b21e2742f3c)

**Assesment Results**
![image](https://github.com/josiah-chua/VR-Language-Learning/assets/81459293/9475ad7f-0325-4a27-bd3d-10ba9b54ed5e)

![image](https://github.com/josiah-chua/VR-Language-Learning/assets/81459293/8382024c-c39f-417b-b7f1-f24dfcf6c0d1)

# Future Works
![image](https://github.com/josiah-chua/VR-Language-Learning/assets/81459293/3dc4bca6-2124-48be-83b5-980b9e881b28)
![image](https://github.com/josiah-chua/VR-Language-Learning/assets/81459293/f2f7dd5e-620d-4e20-bd33-04e6afce2557)

# Acknowledgements
The authors wish to express our heartfelt gratitude to our project supervisor Dr Khoo Eng Tat, and the iDP Immersive Reality Lab for their continuous guidance and support.
We would also like to thank the staff at Centre for Language Studies (CLS) and fellow students of Residential College 4 for their participation in our primary research.
In particular, we would like to thank Prof Sergio Rodríguez Flores and his class for supporting us in our trial, and participating in our research. We would also like to thank John Guilherme Pires Almeida for assisting us in evaluating our user testing results. 
Finally, we would like to express our gratitude to NUS Engineering Design and Innovation Centre (EDIC) for providing us with the opportunity and support to embark on this project.




