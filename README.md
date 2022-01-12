# UnDemo-Builder
 
This is Unobtainium, it's a weird little encryption algorithm I wrote for fun.I called it Unobtainium mostly because I thought it was a funny name for it but here's a basic rundown of the idea: So basically what it does is it takes a matrix of n*3 size, in the form of a list of 3-dimensional numbers, and then creates a shift mask for any set of hex data, by iterating over each hex character and shifting it according to instructions derived from the matrix. Basically at each step it aligns 3 possible points, and then chooses a method of combining the x, y, and z point values based on the central angle of a line drawn between the three points.

Live Demo: https://undemo-builder.web.app/

Demo Instructions:

Fill the list on the left with at least 3 or more (You will see 1, 2, 3 under #) points of data, using non-negative numbers. (Or use the I'm Feelin Lucky button to add a random point)
Click import to add a file from your device to the demo. This does not upload anything; it simply grabs the first chunk of hex data that represents that file to display on the page.
Click generate mask to generate an example of what the shift mask looks like when using the points you've added to the list on the left
Click Up to shift the data Up using the mask (it is now encrypted)
Click copy to copy the output back to the input
Click Down to shift the data Down using the mask (it is now unencrypted)
