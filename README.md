# MSc Computer Science Dissertation
 This repository contains all code and data related to my Computer Science MSc dissertation.
 
The files contained in this repository are all linked to my Computer Science Dissertation.

The breakdown of the folders (and files contained there-in) is explained below:


1. BipedalWalker-v3 Data
This folder contains all of the results obtained during my dissertation. The folder is split up into subsections relating to the different 
stages and optimsations of my project. These can be read about in my report (also included in this repo). 
Specifically, the files are all excel files. The files ending with 'ba' or 'la' represent the 'best actor' (responsible for the best 
reward obtained), and 'last actor' (the actor at the end of training) produced by the agents during training. These files contain the reward 
earned each episode by each respective actor across 100 episodes in the BipedalWalker-v3 environment of OpenAI Gym. All other files contain 
the reward data earned each episode by the agents during training over 3000 episodes.

2. DDPG, TD3, SAC code templates
These code templates are the .ipynb files containing (example) code that was used in each stage of the optimisations. Note that to access the
actual workspace and files used for testing, visit the google colab links from this repo.

3. Hyperparameter Tuning Results
This folder contains the results for hyperparameter tuning(i.e. original and tuned values for each hyperparameter), colour coded by 
the author's confidence in the results.

4. myRL Mobile App
This folder contains a pdf file overviewing the different screens and navigational logic in the app. Futhermore, thhis folder contains the
Unity files used to create the prototype of this app. 

5. myRL Package
This folder contains a user manual for the myRL python package (developed for manual hyperparameter tuning), as well as the .ipynb files 
used in the example of the user manual (inc. the myRL package itself). Visit the google colab of this project to use these .ipynb files.

6. Videos
This folder contains the videos created for this project.

7. Link to colab notebooks
This contains the link to all the colab notebooks used during this project, where all code was implemented and tested. This file also contains 
the setup of the colab notebook filespace which should help with navigation through these files.
