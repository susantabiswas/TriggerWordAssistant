# Trigger Word Assistant
An voice based assistant application which executes the assigned command on detecting the **trigger word** from the user voice. Here the trigger word used is **"activate"**. The user needs to speak through the microphone , then the audio data is processed and fed to the model. The model after detecting the trigger word does the action specified in the code, like I coded it to open Chrome everytime it detects that the user has spoken **activate**.

The Model used for detecting trigger word uses a **deep Recurrent Neural Network** with **Gated Recurrent Units (GRU)**.
The model is build using Keras.

After the audio is processed by the model a notification alert is inserted at the timesteps where the model detected the trigger word in the audio file, you can listen to it inside the **output folder**.

Inside the **audio** folder the recorded voice of user is stored.
  


There are 2 versions for this application: 
### 1. Python file incase you want to directly see what is happening.
Just run the script and wait for the message **"Started Listening"** , then speak through the microphone of the Computer and see it work.
<br>Inside the **output folder** the spectogram of the processed audio is stored.
Here is a gif showing this in action<br><br>
![Alt Text](images/2.gif)



### 2. Jupyter notebook explaining everything.
Detailed walkthrough of the code including option to listen to the actual output processed by the model.
![Alternate image text](images/1.png)<br><br>


