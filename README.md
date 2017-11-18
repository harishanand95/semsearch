### Semantic Indexing Enhanced Video Searching Utility using Neural Networks Nov 2016 - Apr 2017

*  Implemented a video search software capable of understanding semantic contents from the video.
*  The method involves using a CNN (Convolutional Neural Network) followed by a RNN (Recurrent Neural Network) framework (im2txt model in Tensorflow) to detect objects/actions in the video frames and describe them.
*  Network was trained over MSCOCO dataset to detect and describe objects and actions.
*  Implemented inverted indexing for improving search performance on top of the video frame
descriptions.
*  Search queries can address both boolean and temporal modalities. A boolean query could use
AND, OR, NOT operators and temporal modality query could use ”after” and ”before”. For example, input to the search software could be like cat AND dog, cat before dog and the output will be frames in the video where such occurrence occured.
*  Build a web page using Django framework that leveraged on the inverted indexed database created from the frame descriptions.

### References

_"Show and Tell: Lessons learned from the 2015 MSCOCO Image Captioning Challenge."
Oriol Vinyals, Alexander Toshev, Samy Bengio, Dumitru Erhan.
IEEE transactions on pattern analysis and machine intelligence (2016)._
