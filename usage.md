# SPORE: Usage guide

This guide will briefly go through the installation and usage process for SPORE, including the parameters currently supported by the voicebank. 

# Installing 
OpenUtau (Lunai Edition) is recommended for SPORE. It is a fork of OpenUtau made specifically for diffsinger voicebanks. You can view the guide on how to install that [here](https://lunaiproject.github.io/howtouse/)

To Install SPORE, head to Tools -> Install Singer. Select the SPORE.zip that you got from the releases page. 

In Singer Setup, make sure “Archive File Encoding” is set to Unicode (UTF-8)


After Installing, Create a new project. In track one, hit “Select Singer” and choose SPORE by going to DiffSinger -> SPORE

By default, SPORE’s phenomizer should be set to English.

<img width="296" height="106" alt="1" src="https://github.com/user-attachments/assets/a4a8f62f-7ca1-4263-8f32-f13aef54a07a" />

# Lets make her say something! 

After Installing, head to the piano roll and put in some notes. Type in the lyrics by double clicking the desired note you want to change. 

<img width="1431" height="779" alt="2" src="https://github.com/user-attachments/assets/1e5a37ca-0e7f-459b-8ff0-158afeeea6fd" />


The tools at the top will allow you to tweak various settings, such as vibratos, pitch bends, etc. You also have access to a pitch writing tool, knife tool, and eraser. 

<img width="685" height="148" alt="3" src="https://github.com/user-attachments/assets/948d4c44-4330-481d-b163-2f86f03b4eb6" />


If you have “View Phonemes” enabled, you can see the current phoneme(s) being said as well as their timing. This can be toggled by simply pressing the “O” key. 

This works great for when you don’t like the way SPORE says a word. You can edit the desired phoneme by double clicking it. You can also drag the phonemes around to change the timing. 

# Expressions
This section will guide you on how to use SPORE's supported voice paramaters:

Hit the cogwheel Icon on the bottom left to access the expression settings

<img width="793" height="558" alt="4" src="https://github.com/user-attachments/assets/3b0d8fdd-4b48-43c5-9d2f-9eee3c56717e" />

Before starting, select “Add all expressions suggested by renderers” and hit apply. 
Now, you can select the desired parameter from the dropdown list.

Parameters can be altered by drawing a curve in the expressions menu, located at the bottom of the piano roll.

<img width="849" height="199" alt="6" src="https://github.com/user-attachments/assets/7f90d58e-5b9c-4827-8c0f-249519cd40a7" />

* Tension (TENC): Turning up the tension up to a positive value will make SPORE sing the words in a stronger tone. Negative values will make her sing in a softer tone. 

* Gender (GENC): Positive Values will give them a lower pitched, masculine voice. While negative values give her a higher pitched, feminine voice.

* Breathiness (BREC): 

* Velocity (VELC):

* Tone Shift (SHFC):

* Voicing (VOIC): 

# Autopitch

SPORE includes an additional autopitch model based on the singing samples that can be found in her dataset. This can be accessed by going to Batch Edits -> Notes -> load rendered pitch. 


When using Autopitch, it is recommended to render one part at a time. Rendering an entire track may cause the program to crash. 

That should be enough to get you started with using SPORE! If you have any questions, or have any issues with the voicebank, please let me know! My contact is linked in this github's README :)
