<h2> Lab 400: Part something something setting up on VBCS  </h2>

Let's go ahead and create an entirely new web app, as this lab does not relate to our Library website. Click the computer icon on the far left, then hit the plus sign next to Web Apps. Name it whatever you like.<br>
{img}
<br>
The first thing to do is drag and drop an Input Text component into the top left of the page. Change the label to be one column big by clicking on it, then draging the little box on the edge, and change its text to say "Search Name". Move over the text field to be right next to the label, and change it to be two columns wide. To the right of that, drag on a button, and have it say "Search". <br>
{img}
<br>
In the next row, drag a Panel. By default, it fills the page horizontally, but this isn't what we want. We also can't drag the component to resize it the way we can most components. Go to the Code view and find the `oj-panel` div. You'll see something that says "oj-sm-12 oj-md-12". These indicate the how many columns the component should take up for "small" and "medium" views of the page. For this we will be working with medium screens, so change oj-md to oj-md-5. <br>
{img}
<br>
Now let's add a picture. This will be the searched user's profile picture. Drag and drop an Image component into the left side of the panel. Drag an edge so it becomes four columns wide. In the General tab on the right, set width and height to 100. Next to the image we want to have three rows, so drag on a Flex Container object. Drag and drop three Text components inside this container so that they are stack vertically. Name the first "Followers", the second "Following", and the third "Mutuals". 

need to set image url variable and all variables