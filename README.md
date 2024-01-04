# Object Tracking with Computer Vision Using the Histogram Method!  

This is a project that can track an object in a video. I made this using 
information from my CS 639: Intro to Computer Vision class's lectures.  

Here's a [demonstration video](https://youtu.be/HfMzB0gXJWs) where the program
tracks a person that's walking around!  

And here's [another demonstration](https://youtu.be/xhE-kyd5_5o) of it tracking
a rolling soccer ball!  
  
## Here's how it works:
- I have a video that I want to use.
- Run the program.
- On the first frame of the video you can draw a square over the section 
containing the object.
- Then, a histogram with an adjustable bin size is created that represents the
pixels contained within that square.
- For each frame of the video, sections are checked for similarity with the
target square until the right one is found.
- A yellow box is drawn over this area, which *should* contain the object!  

Link to [presentation site](https://christophergottwaldt.notion.site/Object-Tracking-Project-8a7a474de6314d91808fc24f46287030).