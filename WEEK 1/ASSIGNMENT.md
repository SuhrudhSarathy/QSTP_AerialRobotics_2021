# Week I: Assignment
## Transformation of Axis in 2D
Transformation of Axis is a crucial aspect of Robotics. For example, a sensor that is placed on the head of a robot provides sensor data in the robots frame. To convert the this data into the world frame, transformation of data from the camera's frame to the world's frame is paramount.

### Task I
Given two frames `A` and `B` where the the coordinates of a point `P` in `A` frame is `(x, y)`. Find out the coordinates of the the same point `P` in the `B` frame, given that the frame `B` is translated by `(X, Y)` and rotate by an angle `Theta`. Write a python function that does the following and plot the respective Axes using `Matplotlib`. You are allowed to individually to modify the coordinates (https://www.emathzone.com/tutorials/geometry/rotation-of-axes.html). Psuedo code for the function is given below
```javascript
function transformPoint([x, y], [X, Y], Theta):
    // algorithm
    return x_dash, y_dash

function plotAxis([x, y], [X, Y]):
    // algorithm
    plt.plot(FrameA)
    plt.plot(FrameB)
```
Refer to the image below for the final solution Image
<img src="sample.png" alt="Sample Solution" style="height: 200px; width:200px;"/>

### Task II (Bonus)
Refer to this resource: https://www.cs.columbia.edu/~allen/F17/NOTES/frames2.pdf. Transformation of axes can be done using a single matrix multiplication. Do the same task as given in `Task I` but use the matrix given in the above resource and complete the Task.
__Note:__ This task is an optional task. But it is a good task to get familiar with matrix manipulations of coordinates.

### General Guidelines for the Assignment submission:
1. You are advised to fork this repository and add your solutions to that repository. [Here](https://docs.github.com/en/github/collaborating-with-pull-requests/working-with-forks/about-forks) is a resource of setting up forks. Go through the section _Working with forks_ completely.
2. You can use Google Colab for the assignements. The resources for linking the a colab notebook with github is given in the [here](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb.).
3. Information regarding timeline, submission etc. of the assignment will be given in the classroom.