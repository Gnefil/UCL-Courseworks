# Robot Behavioural Cloning
A COMP0188 Deep Learning Coursework. Aims to conduct robotic arm behavioural cloning with multimodal modelling. Given scene images and self-motion data to predict desired actions and gripper state.

Original instructions stored in `CW_Questions.ipynb`. Solved code and discussion stored in `Notebook.ipynb` while PDF version is `Report.pdf`.

# In a nutshell
Develop multimodal model of robot motion data and images to predict actions. Using CLVR Jaco Play Dataset and end-to-end supervised learning and self-supervised VAE + supervised head. 85% accuracy with 50, 60% recall in gripper state, 23% relative error rate in position. E2E worked better.