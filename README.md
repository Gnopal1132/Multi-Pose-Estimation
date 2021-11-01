# Multi-Pose-Estimation
Multi Pose Estimation in Realtime and in a Video Clip.

![ezgif com-gif-maker](https://user-images.githubusercontent.com/51056214/139657812-9039284a-062b-48ec-b19a-45c7ceb387f2.gif)


We are using Movenet Multipose model.

A convolutional neural network model that runs on RGB images and predicts human joint locations of people in the image frame. This model is able to detect multiple people to be exact 6 in the image frame at the same time while still achieving real-time speed. 

I am using the model to actually draw joints in a video clip.

The process to get started:

Step 1: Install basics like Python Interpreter and clone the repository.

Step 2: Create your Environment: Creating an environment will create a separate room for your project and the libraries installed will be separate from your installed one.
```
python -m venv {NAME_OF_YOUR_ENVIRONMENT} or conda create -n {NAME_OF_YOUR_ENVIRONMENT}
```
Step 3: Activation of Your Environment.
```
.\ENVIRONMENTNAME\Scripts\activate  or conda activate {NAME_OF_YOUR_ENVIRONMENT}
```
Step 4: Install IpyKernel so that you can attach the environment with Jupyter notebook
```
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=EnvironmentName
```

In conda:
```
conda install -n EnvironmentName pip  # This will install pip in our environment
conda install ipykernel
python -m ipykernel install --user --name=EnvironmentName
```
Step 5: Open the Jupyter notebook Click Your Environment in the Corner and Select it.

And Then Simply Execute the file.
