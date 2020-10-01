# Optical-Mark-Recognition

Optical Mark Recognition, or OMR for short, is the process of automatically analyzing human-marked documents and interpreting their results.Arguably, the most famous, easily recognizable form of OMR are bubble sheet multiple choice tests, not unlike the ones you took in elementary school, middle school, or even high school. 

Now using Python and with its module called OpenCV we can build a computer vision system that can read and grade bubble sheet tests.


To accomplish this, our implementation will need to satisfy the following 7 steps:

Step #1: Detect an image.
Step #2: Apply a perspective transform to extract the top-down, birds-eye-view of the exam.
Step #3: Extract the set of bubbles (i.e., the possible answer choices) from the perspective transformed exam.
Step #4: Sort the questions/bubbles into rows.
Step #5: Determine the marked (i.e., “bubbled in”) answer for each row.
Step #6: Lookup the correct answer in our answer key to determine if the user was correct in their choice.
Step #7: Repeat for all questions in the exam.
