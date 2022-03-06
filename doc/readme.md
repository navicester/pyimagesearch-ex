https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/
https://www.pyimagesearch.com/2018/07/19/opencv-tutorial-a-guide-to-learn-opencv/
https://www.pyimagesearch.com/opencv-tutorials-resources-guides/

Day3:
https://www.pyimagesearch.com/2014/09/01/build-kick-ass-mobile-document-scanner-just-5-minutes/

Day4:
https://www.pyimagesearch.com/2016/10/03/bubble-sheet-multiple-choice-scanner-and-test-grader-using-omr-python-and-opencv/

Day6:
https://www.pyimagesearch.com/2014/11/10/histogram-oriented-gradients-object-detection/?__s=u9xhwc3z0m7m1fvg8oe1

# My secret weapon for detecting objects in images (from faces, to license plates, to beer bottles)

Hi,

If you’ve been paying attention to my Twitter account lately, you’ve probably seen a few teasers of what I’ve been working on -- a Python framework to rapidly construct object detectors.

Image

From faces, to license plates, to beer bottles -- this 6 Step framework can be utilized to detect and recognize objects in images with ease.

The reason I started working on this framework is because I really can’t stand the Haar cascade classifiers provided by OpenCV (i.e. the Viola-Jones detectors). While cascade methods are extremely fast, they leave much to be desired, especially regarding training time and false-positive detections.

There is also the problem that the Viola-Jones detectors are nearing 15 years old. If this detector were a nice bottle of Cabernet Sauvignon, I might be pretty stoked right now. But the field has advanced substantially since then.

And after reading this post, you’ll have a good high-level grasp on the steps required to build your own custom object detectors.

Ready? Let’s get started.