## Overview

This project makes use of deep neural networks to accomplish neural style transfer, an optimization technique used to take a content image and a style reference image and blend them together so the output image inherits the appearance of content image and the style of style reference image. After preprocessing the images to fit the requirement for the tensorflow package, I'm able to extract the features of the style reference image using the parameters of certain convolution layers from VGG19 models. The result below is a nicely blended image of Golden Gate Bridge with the style of Starry Night.

|Image|Content|Style|
|-----|-------|-----|
||<img src=content_image.jpeg width="350">|<img src=style_image.jpeg width="350">|

|Image|Result|
|-----|------|
||<img src=output_image.jpeg width="728">|


