# Age-Detection 


<h2>Objective :</h2>
<p>To build a gender and age detector that can approximately guess the gender and age of the person (face) in a picture or through webcam.</p>

<h2>About the Project :</h2>
<p>In this Python Project, I had used Deep Learning to accurately identify the gender and age of a person from a single image of a face. I used the models trained by <a href="https://talhassner.github.io/home/projects/Adience/Adience-data.html">Tal Hassner and Gil Levi</a>. The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions.</p>

<h2> 📁Dataset :</h2>
<p>For this python project, I had used the Adience dataset; the dataset is available in the public domain and you can find it <a href="https://www.kaggle.com/ttungl/adience-benchmark-gender-and-age-classification">here</a>. This dataset serves as a benchmark for face photos and is inclusive of various real-world imaging conditions like noise, lighting, pose, and appearance. The images have been collected from Flickr albums and distributed under the Creative Commons (CC) license. It has a total of 26,580 photos of 2,284 subjects in eight age ranges (as mentioned above) and is about 1GB in size. The models I used had been trained on this dataset.</p>

<h2>🔑Additional Python Libraries Required :</h2>
<ul>
  <li>OpenCV</li>
  
       pip install opencv-python
</ul>
<ul>
  <li>cmake</li>
  
       pip install cmake
</ul>
<ul>
  <li>dlib</li>
  
       pip install dlib
</ul>

 <p>For face detection, we have a .pb file- this is a protobuf file (protocol buffer); it holds the graph definition and the trained weights of the model. We can use this to run the trained model. And while a .pb file holds the protobuf in binary format, one with the .pbtxt extension holds it in text format. These are TensorFlow files. For age and gender, the .prototxt files describe the network configuration and the .caffemodel file defines the internal states of the parameters of the layers.</p>

 <h2>🔑Workflow :</h2>
 <div align= "center"><img src="https://github.com/Sudhanshu21xx/Age-Prediction/assets/113416452/20105485-38df-4ab4-a16f-1a9a32a7121b"/></div>


 
 <h2>💡Usage :</h2>
 <ul>
  <li>Download the Repository</li>
  <li>Open the notebook OpenCV_dlib_code.</li>
  <li><b>Change the image name :</li>
  
      img = cv2.imread('sample.jpg')

  <p><b>Note: </b>The Image should be present in same folder where all the files are present</p> 
  </ul>
<ul>
  <li>Run the code.</li>
</ul>



<h2>Examples :</h2>
<div align= "center"><img src="https://github.com/Sudhanshu21xx/Age-Prediction/assets/113416452/2c18317a-a7c8-474c-9ba2-68aa903f8521"/></div>
<div align= "center"><img src="https://github.com/Sudhanshu21xx/Age-Prediction/assets/113416452/47eacb64-a2f6-4513-803a-4ea1dd4dc379"/></div>
<div align= "center"><img src="https://github.com/Sudhanshu21xx/Age-Prediction/assets/113416452/30561e73-8537-4720-87b5-e27fcd25ae96"/></div>
<div align= "center"><img src="https://github.com/Sudhanshu21xx/Age-Prediction/assets/113416452/3e3a1cb0-737b-4b43-bc34-485f0dc14735"/></div>
<div align= "center"><img src="https://github.com/Sudhanshu21xx/Age-Prediction/assets/113416452/18b7d6ee-f1ae-4350-b971-19c755ece62d"/></div>
<div align= "center"><img src="https://github.com/Sudhanshu21xx/Age-Prediction/assets/113416452/a88f5203-490b-4f29-bbe0-a41346f6899a"/></div>
             

 





