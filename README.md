# Project 3: Authenticity Management Algorithm for Digital Images

Company: Adastra Bulgaria

An Android application is used for taking pictures. Those pictures need to be digitally signed in order to verify their authenticity later. The task is to create an algorithm which adds a digital watermark to an image and a corresponding algorithm which verifies if a given image is watermarked by the original algorithm.
The following conditions must be met:

    The algorithm must be able to detect if the image has been tampered with – e.g. re-saving, cropping, resizing, editing small parts of the image in a photo-editing software, copying and moving regions, etc.
    There should be no visibly discernible difference between the original image and the watermarked image.
    Watermark verification should not require the original image.
    The watermark embedded in an image generated by using a particular marking key must be detected only by providing the corresponding information to the verification algorithm. All other side information provided to the verification algorithm should fail to detect the mark.
    The insertion of a mark by unauthorised parties should be difficult.
    The watermark should be capable of being embedded in the compressed domain.