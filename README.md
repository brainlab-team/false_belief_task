# Theory of Mind Assessment in Human-Robot Interaction

This repository contains the code and data related to our research project on assessing **Theory of Mind (ToM)** in Human-Robot Interaction (HRI), using the Pepper humanoid robot. The study explores how a robot's **social attitude** influences users' ability to attribute mental states (ToM) and perform **False Belief Tasks (FBT)**.

## Project Overview

The goal of this project was to investigate whether people attribute mental states to robots and how a robot's social behavior affects their ToM performance. The experiment was conducted using **Pepper** robot and designed with two distinct social behaviors:
- **Interactive social attitude**: Robot exhibits positive social communication, including laughter, surprised reactions, and large, dynamic movements.
- **Passive social attitude**: Robot shows limited engagement with slower movements and forward-leaning postures.

The experiment involved the well-known **Sally-Anne Test**, where participants interacted with Pepper in scenarios that required ToM reasoning.

## Tools and Technologies

- **Robot**: Pepper humanoid robot.
- **Operating System**: Ubuntu (version specific to Pepper robot).
- **Programming Language**: Python 2.7 (with Naoqi framework for robot control).
- **Survey Tool**: Google Forms (used for administering participant questionnaires).
  
## Experiment Design

Participants were randomly assigned to interact with Pepper displaying either an interactive or passive social attitude. The interactions included:
1. Pre-interaction questionnaire to assess Theory of Mind (ToM Inventory).
2. Main interaction where participants engaged in tasks involving the **False Belief Task** with Pepper.
3. Post-interaction questionnaire assessing user perceptions using the **Godspeed Questionnaire**.

## Questionnaires

The study used the following questionnaires:
- **Theory of Mind Inventory (ToMI)**: To evaluate participants' social cognition and ToM abilities.
- **Godspeed Questionnaire Series (GQS)**: To measure perceptions of the robot's anthropomorphism, likeability, intelligence, and perceived safety.
- **False Belief Task (FBT)**: To assess participants' ToM through a robot-assisted version of the Sally-Anne Test.

## Data Collection

Participants' responses were collected via **Google Forms** and analyzed based on their ability to solve the FBT and their perceptions of the robot's social attributes.

## Results

The results of the study suggested that the robot’s social attitude had a significant impact on users' perceptions and ToM performance. Participants interacting with the more socially active robot had a higher success rate in the FBT.

## Repository Contents

- **/code**: Python 2.7 scripts used to control Pepper’s behaviors and execute the experimental tasks.
- **/data**: Anonymized data collected from the questionnaires and experimental sessions.
- **/docs**: Related documentation and research paper.
  
## Citation

If you use this code or data in your research, please cite our paper:

Marino, L., D’Errico, L., Matarese, M., Cangelosi, A., Staffa, M. (2024). Theory of Mind Assessment in Human-Robot Interaction. ICSR 2024.
