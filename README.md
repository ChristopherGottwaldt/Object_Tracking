# Object Tracking with Computer Vision Using the Histogram Method!  

This is a project that can track an object in a video. I made this using 
information from my CS 639: Intro to Computer Vision class's lectures.  

## Demo
Here's a [demonstration video](https://youtu.be/xhE-kyd5_5o) of it tracking
a rolling soccer ball!  
![image](https://github.com/ChristopherGottwaldt/Object_Tracking/assets/91114524/8b899eb7-d870-41d9-b2ce-93281578c71e)  


Here's another [demonstration video](https://youtu.be/HfMzB0gXJWs) where the program
tracks a person that's walking around!  
![image](https://github.com/ChristopherGottwaldt/Object_Tracking/assets/91114524/3a3e66be-18ac-4acd-8a17-4dd9b901d046)




  
## Here's how it works:
- Pick a video with an object that's at least a little distinct from its surroundings.
- Run the program.
- On the first frame of the video you can draw a square over the section 
containing the object.
- Then, a histogram with an adjustable bin size is created that represents the
pixels contained within that square.
- For each frame of the video, sections are checked for similarity with the
target square until the right one is found.
- A yellow box is drawn over this area, which *should* contain the object!  

## ## Future Improvements:
    I would like to try a different method of comparing the histograms to each other to test for a performance improvement; 
    Currently the method is using correlation, but another method like vector norms could potentially work better. 
    If I had access to better computing resources or made a more efficient algorithm, then I could try on a higher-quality video
    with a higher framerate for smoother tracking box transitions.
