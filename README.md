# Ultrasound Nerve Segmentation

## About the competition

The task in this competition is to segment a collection of nerves called the Brachial Plexus (BP) in ultrasound images.

Moreover, this is a segmentation problem where the pixels in each image belonged to one of two possible classes: nerve vs. not nerve.


## Other aspects about the competition

* Images are in tiff file format
* Evaluation by Dice coefficient
* Submission using Run-length encoding format.(	In order to reduce the submission file size, our metric uses run-length encoding on the pixel values )


## About the training data

The large training set of images where the nerve has been manually annotated by humans. Annotators were trained by experts and instructed to annotate images where they felt confident about the existence of the BP landmar

The images have a size of 580x420 pixels. There are 5635 training images and 5508 test images (of which 20% were used for public ranking and 80% for the final ranking).