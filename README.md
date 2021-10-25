# Face_Recognition

### Description:
A real-time face recognition system built using pre trained FaceNet model.

database.pickle is a python dictionary containing 15 names and face embeddings, few of which are of celebrities.

### Methodology:
* Faces are detected in images using Haar Cascade or MTCNN and their corresponding embeddings are obtained from the FaceNet model.
* A database containing names and face embeddings is created.
* For a given frame of input video or image, step 1 is repeated and the face embeddings are compared with embeddings in the database using their L2 distance.

*All functions required to create a database and to add a new face to the database are provided in the notebook.*

## Installation

Install all dependencies using requirements.txt like so:

```shell
pip install -r requirements.txt
```  

## Examples

1)
<p float="left">
  <img src="https://github.com/Mihirsahu2307/Face_Recognition/blob/master/Examples/Walter_White_Recognized.jpg" height = "500" width="500" /> 
</p>

2)
<p float="left">
  <img src="https://github.com/Mihirsahu2307/Face_Recognition/blob/master/Examples/Obama_with_Modi_Recognized.jpg"/> 
</p>

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements
 - Florian Schroff, Dmitry Kalenichenko, James Philbin (2015). [FaceNet: A Unified Embedding for Face Recognition and Clustering](https://arxiv.org/pdf/1503.03832.pdf)
 - [FaceNet github repository](https://github.com/davidsandberg/facenet)
 - [MTCNN github repository](https://github.com/ipazc/mtcnn)
