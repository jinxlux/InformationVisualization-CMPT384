<!-- xudong Li, xul395, 11206927 -->
<!-- luohan du, lud380,11201129 -->

Dashboard.jpg is for different designing plans
Questions.pptx is for questions & answers of the different plans

parallelC.html is for the third requirement, which is an implementation.
It uses d3.parcoords.js & d3.parcoords.css
Data is from the file called t.csv, which is originally called 
"Summer Olympic medallists 1896 to 2008"
We delete the first 4 rows to make it readable for the d3, and so we 
give it the new name t.csv
For lunching, enter command "python -m http.server 8888" in linux/Mac terminal,
and the working dictionary should contains all implementation files and
t.csv. In a browser(like google), type "http://0.0.0.0:8888/parallelC.html" in
address field. Press Enter, a parallel coordinate should be shown.
You can also check the result at http://parallelvisualization.ml/ (It could be slow due to the huge data)
You can use brushing, reording for the parallel coordinate.
The color is based on the gender at first (red=women,blue=men).
opacity is 0.1 for each athletes, so we can get information from
how clear a color shown.
By pressing the dimension label "Nation", "Medal" & "Gender",
we can change the color base.
Also, Pressing "Nation" and "Gender" will also let balls shown 
at the bottom of parallel coordinate.
Size of balls are based on the number of athletes belongs to
that category. Colors for balls are same as colors which represent
that category in parallel coordinate.
