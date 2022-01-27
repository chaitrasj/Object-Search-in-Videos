# Object Search in Videos

Course project for Video Analytics ([VA](https://val.cds.iisc.ac.in/DS-263-VA/)) course: DS 263, at the Indian Institute of Science ([IISc](https://iisc.ac.in/)).

The work is based on the [paper](https://link.springer.com/chapter/10.1007/11957959_7).
Implemented an object retrieval technique that searches for all the occurrences of an object in a video, given a query image of the object using the Bag of Words model. Object is represented by viewpoint invariant SIFT descriptors and Bag of Words model is used for image retrieval.
For more details about the project, please refer to the [Project Report](https://github.com/chaitrasj/Object-Search-in-Videos/blob/main/Object_Search_in_Videos_Video_Analytics.pdf)

### Training
Training code is available at [MinHash.ipynb](https://github.com/chaitrasj/Object-Search-in-Videos/blob/main/MinHash.ipynb) for MinHash based algorithm and at [Tf-idf.ipynb](https://github.com/chaitrasj/Object-Search-in-Videos/blob/main/Tf_idf.ipynb) for TF-IDF based algorithm.

For more details about the Training, testing procedures and the losses used, please refer to the [Project Report](https://github.com/chaitrasj/Object-Search-in-Videos/blob/main/Object_Search_in_Videos_Video_Analytics.pdf).
