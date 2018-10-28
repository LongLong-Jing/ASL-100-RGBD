<p align="center"> 
<b>
<font size="5"> Recognizing American Sign Language Manual Signs from RGB-D Videos  </font> 
</b>
</p>
<p align="center">
Longlong Jing, Elahe Vahdani, Yingli Tian, Fellow, IEEE, and Matt Huenerfaut
</p>



![alt text](./media/demo_img.jpeg "Title")

------

<p align="center"> 
<b>
<font size="5"> Abstract </font> 
</b>
</p>

In this paper, we propose a 3D Convolutional Neural Network (3DCNN) based multi-stream framework to recognize American Sign Language (ASL) manual signs (consisting of movements of the hands, as well as non-manual face movements in some cases) in real-time from RGB-D videos, by fusing multimodality features including hand gestures, facial expressions, and body poses from multi-channels (RGB, depth, motion, and skeleton joints.) To learn the overall temporal dynamics in a video, we generate a proxy video by selecting a subset of frames for each video which then be used to train the proposed 3DCNN model. We collect a new ASL dataset, ASL-100-RGBD, which contains 42 RGB-D videos, each of 100 ASL manual signs, including RGB channel, depth maps, skeleton joints, face features, and HDface. The dataset is fully annotated for each semantic region (i.e. the time duration of each word that the human signer performs). Our proposed method achieves 75.9% accuracy from only RGB channel and 80.3% from the fusion of multi-channels for recognizing 100 ASL words, which demonstrate the effectiveness of recognizing ASL signs from RGB-D videos.

------

<p align="center"> 
<b>
<font size="5"> Demo Video </font> 
</b>
</p>
<p align="center">
<video width="950" height="540" controls>
  <source src="./media/demovideo.mp4" type="video/mp4">
</video>
</p>


A new dataset has been collected for this research in collaboration with ASL computational linguistic researchers, from native ASL signers (individuals who have been using the language since very early childhood) who performed a word list of 100 ASL signs by using a Kinect V2 camera. Participants responded affirmatively to the following screening question: Did you use ASL at home growing up, or did you attend a school as a very young child where you used ASL? Participants were provided with a slide-show presentation that asked them to perform a sequence of 100 individual ASL signs, without lowering their hands between words.  Since this new dataset includes 100 signs with RGB and depth data, we refer to it as the ASL-100-RGBD dataset. 

------


<p align="center"> 
<b>
<font size="5"> Full List of the 100 ASL words </font> 
</b>
</p>

![alt text](./media/list.png "The Full list of the 100 ASL words")

The full list of the 100 ASL words in our ASL-100-RGBD" dataset under 6 semantic categories. These ASL words have been strategically selected to support sign recognition technology for ASL education tools (many of these words consist of both hand gestures and facial expression changes.)


