# Video to Sound using Machine Learning
### By Brian Do - Winter Term 2023

Live_vid_input.maxpat: A Max program that transforms live video from device's webcam into a 20x15 pixels video, and then sends 900 numeric representation of each frame to Wekinator through port 6448

Video_input_from_external_cam.maxpat: A Max program that transforms live video from an external camera into a 20x15 pixels video, and then sends 900 numeric representation of each frame to Wekinator through port 6448

Sound_output.maxpat: A Max program that receives 4 outputs from Wekinator through port 12000, which are then turned into meaningful sound attributes to then create sound

Sound_classifier_output.maxpat: A Max program that receives 1 output from Wekinator through port 12000, which determine which sound is being played 

Live_20x15_900inps_Sound_4outps: A folder contain a trained Wekinator model Live_20x15_900inps_Sound_4outps.wekproj . This model was trained using Live_vid_input.maxpat for input and Sound_output.maxpat for output. 

Live_900_classifier_sound_4: A folder contain a trained Wekinator model Live_900_classifier_sound_4.wekproj . This model was trained using Live_vid_input.maxpat for input and Sound_classifier_output.maxpat for output.

#### To run these models, open the model and the corresponding input and output programs, press 'Start listening' for port 6448 and follow the instructions in the input and output programs
