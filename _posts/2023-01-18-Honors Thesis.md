---
title: "Honors Thesis: Evaluating the Viability of Motion Tracking in Nurse Training Applications"
layout: post
---

Summary and updates on my thesis: exploring the viability of motion tracking and feedback during nursing procedures. This work is being done in collaboration with the [Mechatronics and Robotics Research Lab][MRRL] at UMass Amherst. 

Committee Chair: Dr. Frank Sup



## Computer Vision: Mediapipe and YOLO Object tracking

Initial trial to use YOLO to crop "person" objects in a frame and run hand or pose tracking on them through Mediapipe.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ujhqqQvhGOc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> 

Mediapipe ['Pose'][Pose] and ['Hands'][Hands] only support singlebody tracking. Using the YOLO module to crop bodies to get data from multiple bodies in one frame was successful. More work is required to increase the accuracy of the tracking and improve the latency of the system. Wearable trackers may need to be incorporated to prevent these problems.

## Literature Review
[📄 Literature Review (PDF)](assets/pdf/Literature.Review(1).pdf)

## Final Report
[📄 Final Report (PDF)](/assets/pdf/Honors_Thesis_Final_Report(1).pdf)

## Scripts

{% highlight ruby %}

   #Pending...

{% endhighlight %}

## MASS URC Thesis Presentation 

<iframe
  src="https://docs.google.com/presentation/d/e/2PACX-1vS3XeYr7z0mWrCesPUUIw2vGzSXX0GL4xC0UYxf3KQ61KLlT9XF3c8v_r0Xvo1a7w/embed?start=false&loop=false&delayms=5000"
  width="800"
  height="460"
  frameborder="0"
  allowfullscreen>
</iframe>

[🔗 Open presentation in Google Slides](https://docs.google.com/presentation/d/e/2PACX-1vS3XeYr7z0mWrCesPUUIw2vGzSXX0GL4xC0UYxf3KQ61KLlT9XF3c8v_r0Xvo1a7w/pub)


[MRRL]: https://www.umass.edu/robotics/mrrl
[Pose]: https://google.github.io/mediapipe/solutions/pose.html#:~:text=MediaPipe%20Pose%20is%20a%20ML,ML%20Kit%20Pose%20Detection%20API. 
[Hands]: https://google.github.io/mediapipe/solutions/hands.html 
