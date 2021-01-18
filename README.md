### Summer Olympic medallists 1896 to 2008 visualized in parallel coordinate
- - -
#### Participants:
xudong Li & luohan du
#### Introduction of different files
> Dashboard.jpg is for different designing plans
Questions.pptx is for questions & answers of the different plans

>parallelC.html is for the third requirement, which is an implementation.

#### Javascript library used
>D3.js   
>[Documents](https://d3js.org/)   
>[Github]("https://github.com/d3/d3")   
>[WIKI]("https://zh.wikipedia.org/wiki/D3.js")
#### Lunching locally
> Need: Python (You can choose other methods to start a server. Here we use Python)   
> 1. Change to the directory of you cloned project (Use cd command in linux/Mac terminal)
> 2.Enter command "python -m SimpleHTTPServer 8001" in linux/Mac terminal
> 3.Type "http://localhost:8001/parallelC.html" in
address field. Press Enter, a parallel coordinate should be shown.
#### Check the result in Internet
>You can also check the result at http://parallelvisualization.ml/ (It could be slow due to the huge data)

#### Usage
>+ You can use brushing, reording for the parallel coordinate.The color is based on the gender at first. Opacity is 0.1 for each athletes, so you can get information from how clear a color shown.
>+ By pressing the dimension labels except ID,
you can change the color base. 
>+Pressing labels will also let balls shown 
at the bottom of parallel coordinate.
Size of balls are based on the number of athletes who win an honor belongs to that category. Colors for balls are same as colors which represent that dimension in parallel coordinate.
