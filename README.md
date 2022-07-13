# Manipulation *On-The-Move*
Why do mobile robots come to a stop when they grasp something or put something down? Humans are quite capable of performing such manipulation tasks while walking or even running. By performing tasks *on-the-move* overall execution time for multi-step tasks can be significantly reduced, and the resulting motion is more natural and graceful.

This project develops an architecture for allowing mobile manipulators to perform reactive manipulation tasks on-the-move. Reactive control allows for robust performance in complex, dynamic environments, such as grasping moving objects.

This video demonstrates performance of the architecture on a real-world mobile manipulator performing a pick-and-place task.

![Frankie Pick-and-Place](gifs/FrankiePickPlace.gif)

Closed-loop feedback from a camera in the palm and the reactive controller enables grasping of objects with unpredictable motion. 

![Frankie Pick-and-Place Moving Object](gifs/FrankiePickPlaceDynamic.gif)

The generalised architecture allows for chaining of multiple actions and the execution of complex, multi-step tasks.

[![Frankie Pick-and-Place Loop](images/FrankieLoopThumbnailCropped.jpg)](https://www.youtube.com/watch?v=5lZfAJ_AHP0 "Frankie Pick-and-Place Loop")

Paper coming soon!
