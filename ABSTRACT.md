The **Ant Detection** dataset consists of images of ants moving on a marked out polygon in the open air and annotations to them. Image size 1920x1080. Annotations are text files that store the coordinates of bounding boxes encompassing all fully visible ants within the image. The dataset is divided into test and training sets containing 120 and 480 images, respectively.

## Motivation

Presently, there's a notable momentum in robotics towards advancing the development of biosimilar systems. Leveraging the ant family as a model object proves to be both intriguing and instructive for this endeavor. Biologists engaged in ant research often find themselves needing to elucidate their behavior. Observation stands as the most accessible method for achieving this goal. While analyzing data from video recordings presents distinct advantages over real-time observation—such as increased accuracy and informativeness—it also demands considerable time investment. To streamline this process, a proposed solution involves the creation of an ant detector utilizing video recordings. Subsequent data processing from the detector offers a partial automation of the research workflow.

## Dataset description

The dataset consists of three-channel images. The marking of objects was carried out through the Label Studio utility and gives the output in .json format, one file for all images. The object description is a bounding box, which is described by two points: the top left point and the bottom right point. Key points: point marking the center of the head - H. point marking the center of the abdomen - A.

<img src="https://github.com/dataset-ninja/ant-2/assets/120389559/71439dc0-d7c8-4c7a-b05f-213418ae1b3a" alt="image" width="500">

