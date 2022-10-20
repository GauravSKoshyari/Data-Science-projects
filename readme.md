
<!-- TABLE OF CONTENTS -->
<di>
  <div>Table of Contents</div>
  <ol>
    <li>
      <a href="#project-1">Project 1</a>
    </li>
    <li>
      <a href="#project-2">Project 2</a>
    </li>
    <li><a href="#project-3">Project 3</a></li>
  </ol>
</di>



<!-- ABOUT THE PROJECT -->
# Project 1
Project1 is performed in Seq2SeqImplementation.ipynb . 
In this notebook , two models are implemented from scratch , encoder-decoder and attention model . These models are used  for italian to english translation. 
Finally , BLEU score is used as a metric to evaluate the model. 

Here are some translations on test data using encoder-decoder model.
![Product Name Screen Shot][translation-ss]



# Project 2
Project2 is performed in image_segmentation_project.ipynb . 
Images are taken from  indian traffic and image segmentation is done on them . 
We have implemented CANet model from scratch and then it is trained  and used for segmentation. 

Architecuture implemented is based on this paper - https://arxiv.org/pdf/2002.12041.pdf

Here are final results after performing segmentation.

`first column- test images ;second column- original mask ;third column- predicted mask`
![Product Name Screen Shot][segmentation-ss]
    


# Project 3
Project3 is performed in text_classification_navie_Bayes.ipynb . 
In this notebook , we have performed text classification using Navie Bayes model.  Naive Bayes is tried both with BOW and TFIDF vectorizer.  



## Built With

* [![Tensorflow][Tensorflow.js]][Tensorflow-url]
* [![Python][Python.org]][Python-url]
* Scikit-learn






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[Tensorflow.js]: 	https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white
[Tensorflow-url]: https://www.tensorflow.org/
[Python.org]: 	https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[segmentation-ss]: images/ss_image_seg.PNG
[translation-ss]: images/translation.PNG

