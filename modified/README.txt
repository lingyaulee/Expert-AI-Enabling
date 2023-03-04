Brief Explanation of my work 

Note all my files that I created myself are under: https://github.com/lingyaulee/Expert-AI-Enabling/tree/butterfly/modified
My folder is embedded within a larger framework of files from the YOLOv5 which I cloned from the internet.(https://github.com/lingyaulee/Expert-AI-Enabling)

YOLOv5 object detection was used on the butterfly video. The pre-trained model did not detect the butterflies as it was not trained on butterflies. From the main respository https://github.com/lingyaulee/Expert-AI-Enabling, detect.py was called with Anaconda prompt, which runs the object detection direclty from python code.  Because there were no detections,  I performed transfer learning with a labelled dataset from the internet  with 1.3K images (https://universe.roboflow.com/aparna-das/final_project-hnbll). Initially I used train.py to train the model, however, due to my laptop hardware restrictions I had to move it to the cloud.  Only this training part was done on the cloud. The training can be seen on the Colab link: https://colab.research.google.com/drive/1HgWp49BDDd2WjSIyyFgCPM3_w6bSIMdS?usp=sharing

With the newly trained model, I was able to make the inferences on the butterfly video.  To count the butterflies, I saved the log which was outputted in Anaconda prompt which I saved under the folders: lingyaulee/Expert-AI-Enabling/modified/inference_log.txt.  
The file 'counter.ipynb', loops through the inference_log.txt file and outputs the number of butterflies in 'count_by_frame.csv' for every frame in the video.  

The code in 'Video Generator' generates a new video with the butterfly count printed on screen.  Final output file with butterfly count is 'out_test.mp4' and emailed separately because it could not uploaded on Github as it is over the limit.  

Due to some other unforeseen activies, I was only able to finish this part of the assignment. However, I look foward to tackling more AI projects in the future.  Thank you.  

