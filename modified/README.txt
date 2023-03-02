Brief Explanation of my work 

YOLOv5 object detection was used on the butterfly video. The pre-trained model did not detect the butterflies as it was not trained on butterflies. 
Hence, I performed transfer learning with a labelled dataset from the internet  with 1.3K images. 
Initially I used Anaconda prompt to train the model, however, due to my laptop hardware restrictions I had to move it to the cloud.  Only the training 
was done on the cloud.  

With the newly trained model, I was able to make the inferences on the butterfly video.  To count the butterflies, I saved the log which was outputted 
in Anaconda prompt. Under the folders: yolov5/modified/inference_log.txt.  Note all my files that I made are under folder named 'modified'.
The file 'counter.ipynb', loops through the inference_log.txt file and outputs the number of butterflies in 'count_by_frame.csv'.  

The code in 'Video Generator' generates a new video with the butterfly count printed on screen.  Final output file with butterfly count is 'out_test.mp4'
Due to some other unforeseen activies, I was only able to finish this part of the assignment. However, I look foward to tackling AI projects.  


Butterfly Dataset 
https://universe.roboflow.com/aparna-das/final_project-hnbll

Transfer Learning Training on Colab
https://colab.research.google.com/drive/1HgWp49BDDd2WjSIyyFgCPM3_w6bSIMdS?usp=sharing

