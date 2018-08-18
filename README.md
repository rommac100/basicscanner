# basicscanner
A scanner that uses opencv to convert edges into contours which are exported into svgs. Helps with laser cutting pieces out of scrap wood and optimizing cuts.

Dependencies:
Opencv

Compile Instructions:
Make a build folder and run "cmake .." inside it
Run make in the build folder and an executable 
should be created.

Run Instructions:
run the command with the first parameter for img 
file name

ex:
./opencv_test test.jpg parameter1 parameter2

parameter1:
-S - Show windows with contours and regular image

parameter2:
-D - Show diagnostic info
