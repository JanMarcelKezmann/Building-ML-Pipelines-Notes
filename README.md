# Building-ML-Pipelines-Notes

<p>This Repository contains Notes in form of Jupyter Notebooks for every Chapter of the Book "Building Machine Learning Pipelines" by Hannes Hapke &amp; Catherine Nelson published by O'Reilly.</p>


## Preface

<p>While going through the book it helped me personally to follow along with the codes and reproduce most of the the things showed in the book. Due to the fact that some things were harder than explained I thought of providing that Repository for other people facing similar difficulties.</p>
<p>Even though I have coded everything by myself most of the raw python codes are out of the book and I just changed a couple of lines to make it working for myself.</p>

 
## Table of Contents
 
 - [About the Repository](#about-the-repository)
 - [Installation and Setup](#installation-and-setup)
 - [Citing](#citing)
 - [License](#license)

## About the Repository

<p>The repository contains codes and additional information from nearly all chapters of the book. Especially the chapter 2 - 8 are working seemlessly in a Jupyter Notebook. I personally developed all the Notebooks in Google Colab Environments, but they should run all locally too. For the Chapters 9 - 11 and 14 I provided a lot of comprehended information, but with less code and the chapter 12 and 13 and all the appendices are not covered in great detail or at all. This is due to the fact that the explanation would needed to be just as detailed as in the book to be valuable. Therefore I did not rephrase theses few chapter on Orchestration.</p>
<p>Even though I coded more or less every line that was mentioned in the book, I will not include almost all of the output, this is due to the fact that some files are pretty large. But anyway the outputs can easily be generated by yourself, by just running the codes.</p>
<p>I personally added some additional resources at the end of each notebook, which I just stumbled accross and found useful, but I took some out of the book too. Further the repository contains not just code, but a lot of text that is helpful for the understanding of the tools used. I did not wanted to quote the book for every sentence I rephrased and I hope that it is fine, since the repository is just an additional explanation to the things mentioned in the book and should lead to a better understanding.</p>

### Skip Directly to the Chapter's Notebooks:

 - <a href="https://github.com/JanMarcelKezmann/Building-ML-Pipelines-Notes/blob/main/Chapter%202/Chapter_2_Introduction_to_TensorFlow_Extended.ipynb">Chapter 2</a>
 - <a href="https://github.com/JanMarcelKezmann/Building-ML-Pipelines-Notes/blob/main/Chapter%203/Chapter_3_Data_Ingestion.ipynb">Chapter 3</a>
 - <a href="https://github.com/JanMarcelKezmann/Building-ML-Pipelines-Notes/blob/main/Chapter%204/Chapter_4_Data_Validation.ipynb">Chapter 4</a>
 - <a href="https://github.com/JanMarcelKezmann/Building-ML-Pipelines-Notes/blob/main/Chapter%205/Chapter_5_Data_Preprocessing.ipynb">Chapter 5</a>
 - <a href="https://github.com/JanMarcelKezmann/Building-ML-Pipelines-Notes/blob/main/Chapter%206/Chapter_6_Model_Training.ipynb">Chapter 6</a>
 - <a href="https://github.com/JanMarcelKezmann/Building-ML-Pipelines-Notes/blob/main/Chapter%207/Chapter_7_Model_Analysis_and_Validation.ipynb">Chapter 7</a>
 - <a href="https://github.com/JanMarcelKezmann/Building-ML-Pipelines-Notes/blob/main/Chapter%208/Chapter_8_Model_Deployment_with_TensorFlow_Serving.ipynb">Chapter 8</a>
 - <a href="https://github.com/JanMarcelKezmann/Building-ML-Pipelines-Notes/blob/main/Chapter%209/Chapter_9_Advanced_Model_Deployments_with_TensorFlow_Serving.ipynb">Chapter 9</a>
 - <a href="">Chapter 10</a>
 - <a href="">Chapter 11</a>
 - <a href="">Chapter 12</a>
 - <a href="">Chapter 13</a>
 - <a href="">Chapter 14</a>

## Installation and Setup

**Clone the repo**

    $ git clone https://github.com/JanMarcelKezmann/Building-ML-Pipelines-Notes

**Install requirements**

```shell
pip install --upgrade -r requirements.txt
```

Make sure you have the following installed:
 - Python 3.6 or 3.7
 - tensorflow >= 2.3.0
 - tfx >= 0.24.0
 - tensorboard_plugin_fairness_indicators >= 0.24.0
 - tensorflow_hub >= 0.9.0
 - tensorflow_privacy >= 0.5.1
 - pandas >= 1.1.2
 - witwidget >= 1.17.0
 - apache-beam >= 2.24.0
 - google-cloud-core >= 1.4.2
 
## Citing

    @misc{Kezmann:2020,
      Author = {Jan-Marcel Kezmann},
      Title = {YourCookBook},
      Year = {2020},
      Publisher = {GitHub},
      Journal = {GitHub repository},
      Howpublished = {\url{https://github.com/JanMarcelKezmann/Building-ML-Pipelines-Notes}}
    }

## License

Project is distributed under <a href="https://github.com/JanMarcelKezmann/Building-ML-Pipelines-Notes/blob/master/LICENSE">MIT License</a>.
