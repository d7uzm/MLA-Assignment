# Assignment 3

### Response

#### What questions do you still have about the model and the associated data? Are there elements you would propose including in the biography?

I tried to find something to propose, but I think the information provided is quite comprehensive and thorough.

#### How does understanding the provenance of the model and its data inform your creative process?

To be honest, it did not affect much, partly because the model I used was not included in the slides. Maybe it will influence how I use the model when I work with CoCoSSD.

### Working with Models

I decided to work with the HandPose model because I had seen it used in an art project. I borrowed some example code from the ml5.js page, played with it a bit, and realized that using it for discrete states would be challenging. Classification models would be more suitable for that use case.

In an attempt to create something from this model, I tried to draw the entire hand, as opposed to the code example that only showed keypoints. It was tedious, so I looked up and found the [drawSkeleton](https://github.com/makeabilitylab/p5js/blob/master/ml5js/HandPose/HandPoseDemo/sketch.js) function. I slightly modified the function so that the skeleton looked more like a hand, and added some geometry generation code to include a palm in the drawn hand.

<img src="./hand.png" width="600px"/>

I explored what I could do with the model and thought of two things:
- If the distance from the fingertips to the wrist (palm base) is smaller than the distance from the knuckles to the wrist, it indicates folded fingers. 
- The angle from a fingertip to the wrist can tell where a finger is pointing. 

In a p5.js sketch, I used the above two considerations to control the background color.

#### Working Video

Visit [working video page](./working%20video.mp4).

#### Direct Link to p5.js

https://editor.p5js.org/ob2sd/sketches/b8dsFQsTH
