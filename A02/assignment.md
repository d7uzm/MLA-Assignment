# Assignment 1b

### Explore ImageNet. ImageNet sample images, Kaggle ImageNet Mini 1000, What surprises you about this data set? What questions do you have? Thinking back to last week’s assignment, can you think of any ethical considerations around how this data was collected Are there privacy considerations with the data?

The impressive aspects of those datasets are that they include people's faces, copyright logos, and watermarks on images, as well as a significant variation in image quality, among other things. I am unsure whether the owners of those images have consented to their use for the purpose of training AI, etc. Ethically, ownership, usage rights, and privacy seems to be the major issues with these databases. The images appear to have been collected via web scraping.

### Using the ml5.js examples above, try running image classification on a variety of images. Pick at least 10 objects in your room. How many of these does it recognize? What other aspects of the image affect the classification, including but not limited to position, scale, lighting, etc.

The model recognized the following objects in my room:
- Water bottle (disposable soft drink cup)
- Paper towel (kitchen towel)
- Lotion
- Desk
- Closet
- Vacuum cleaner
- Pillow
- Window shade
- Electric fan
- Digital watch
- Plastic bag

I am sure that there are more items that can be classified by this model.

The angle of the displayed item, the distance of the object, and others affect the classification.  
Specifically, in my case, my webcam tries to adjust the brightness and warmth(?) of the video, which also has a slight effect on the accuracy of the classification.


### Document your thoughts on MobileNet and image classification in a blog post and add a link to the Assignment 1b Wiki.

It still amazes me how technology has evolved to its current state. Advanced models with a lot of training data are now better than humans at recognizing various types of images, including bot-filtering CAPTCHAs. There has been a lot of research into the medical use of image classifications, such as X-rays and skin images. There are also services that can identify wildlife plants from images. If we can address the black box issue and foster logical trust in image classification (and other) algorithms, we may make further progress in more serious use cases, including the medical industry and truely driverless cars.
