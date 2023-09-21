# Fareha Khan, Technology Design Foundation

### Welcome to my GitHub repository! 

![This is me](Me.jpeg)

Hi! my name is Fareha Khan. I am a Mechanical Engineer by profession and a Designer by heart. Currently, I am based in Dubai working as an Industrial Sustainability Engineer at Schneider Electric. I deeply care about ideas and products that make us feel more humane and connect us with our true selves. I am co-founder of Efert, a non-profit public toilet management system in Karachi, my hometown. In my free time, I love to chat with my grandparents, watch sports with my friends or watch movies with my mom.

I came across a video of James Dyson answering some really fun desing questions and I absolutely love his design thinking. 
[Check it out!](https://www.youtube.com/watch?v=zFCFe38EIfE)



---
# Report 1 - Week of 08/31/2023 #
This week, I got introduced to grasshopper and explored some files to design and laser cut a phone stand. So what is Grasshopper? In short, Grasshopper is a visual programming language that runs with Rhinoceros 3D. 

## :memo: Getting Started...

The first step I took to approach this project was to read a little bit about Grasshopper and try to get a sense of what this software is. I found some really helpful information on [Rhino's website](https://www.rhino3d.com/6/new/grasshopper/) It explains how Grasshopper allows a wide range of functions from environmental analysis to robotic control! In addition to that, I also watched Kyle's beginner videos about Rhino. 
![](grasshopper.jpg)


Second step for me was to get started with the Phone Stand files that was shared with us in class last week. When I first opened the file, it was a little difficult for me to locate the options and tools. I was successfully able to open the grasshopper file through Rhino, but my screen looked very different from TJ's Rhino screen during class. 
This is what my screen looked like, very blank and no Remote Control
![No RCP](grasshopperscreen.jpg)

I figured the problem was that my screen was missing the Remote Control Panel which would be used to manipulate the variables. Then after hovering over different tabs and tools, I figured out that the RCP (Remote control panel) was in Grasshopper's window under view!

![RCP](rcp.jpg)

## :swimmer: Progressing...

After being able to locate the Remote Control Panel, I tried to modify the parameters such as phone dimentions, student height and table dimentions. I noticed that my heigth is shorter than the height of the student in example, so I also tried to change the phone angle in such a way that it would cover me completely.

![angle](angle.jpg)


I also chose to product only 2D drawings as I wanted to work with laser cutting. After I was satisfied with the parameters, I saved changes and checked out the drawing for productions file. The drawings seemed to be what I expected them to be so I exported them to dxf file and went on for laser cutting. 

![drawing](drawing.jpg)

The material I chose was plywood 1/4 inch board. I set the dxf file for the right document setup such as stroke line: 0.072 pt, RGB 255,0,0 for cut, and, and no fill. The laser cutting process was very satisfying to watch. 

![lasercutting](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/efe6c14a-24be-480b-bff3-f954820c062c)

After all the parts were cut, I assembled them to construct the phone stand. The assembled peice looked alright in terms of the cut, shape and size.

![First Cut](landscape.jpg)

However, I noticed that the parts were not fitting perfectly, and the phone stand was not exatly sturdy. I noticed that this was because of the cuts in the base being slightly  larger than the thickness of the material. 

![Cuts](oneclose.jpg)

I also realized that this orientation only allowed the phone to be held in landscape which is not very convenient. 


## 📈 Getting There...

I realized that there are a lot of things interconnected in this project and it is easy to get confused. Therefore, I decided to make a flowchart of actions that would help me produce my next phone stand models. The flowchart looked a little bit like this: 

![flowchart](flowchart.jpg)

We start by going back to the Grasshopper and Rhino files to change the parameters. Once the parameters are decided, the drawing should be checked to see if it matches expectation. The next step would be to bake the drawing in grasshopper so it can be exported to dxf for laser cutting. Next, the dxf file should be prepared with the right document set up. The laser cutter safety precautions should be checked. The plywood then should be kept at the right place and with focus view it should be checked whether the drawings are within the scope. 



## 🔮 Final Thoughts...

I think grasshopper is an amazing tool that allows excellent design modifications and automation. For next week, I will focus on modifying the phone stand design to allow portrait orientationa and have a more sturdy fit. I also think that with the use of AI and chatgbt in grasshopper, this entire process in the future may be completely automated. 


---
# Report 2 - Week of 09/07/2023 #

## 🏁 Phone Stand Modification

This week, I spent a little more time with the Rhino and grasshopper files relavant to the phone stand. I realized that the grasshopper file allows many modifications in the final shape of the phone stand. Something new I touched was 'prism' modifications. Modifying the prism offset values has an effect on the 'claw' of the phone stand.

![prism](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/a0eef4de-c9e3-4d8d-926e-4ad45f5826b9)

I realized that if I could completely remove the claw, the phone stand could also allow portrait orientation. Modifying the prism values looked like this: 

![withprism](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/9ce7d181-3954-4397-ba7a-3744dd599c7a)
![prism3d](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/dcf32c00-1b12-4886-80ee-725eb3d46f16)

The next part to tackle is to manage the phone stand width. This is important because the width we set, automatically changes the size of mortoise (the joint to fix the phone stand). In the first trial, the phone stand I produced was not sturdy because I did not change the width in grasshopper. This time, I measured the width of plywood that I am going to laser cut for the phone. The phywood measured to be around 2.1 inches (5.3 cm). Accordingly, I set the width in grasshopper to be 5 cm. I imagined that if the width of mortoise is lesser than the width of the tenon, it could be tight fixed. 

## 🥩 Laser Cutting 

After changing the parameters on grasshopper, the final drawing of the phone stand looked like this:

![newdrawing](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/a7cd560e-18e5-4a46-afad-80d06c5b1192)

I also decided to engrave something on the phone case to make it customized. I added a text "hello" from Adobe illustrator on the drawing. The important point here was to carefully select the lines of the shape to be red, and make sure the lines of text are blue. This is because for laser cutting, a red line indicates the machine to cut and a blue line indicates vectoring etching or engraving. 



https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/cd6227e2-f745-4c61-ad51-2ac93e693ee1

## 🏗️ Assembly

The final and most interesting part of this trial was the assembly. After all the parts were laser cut, I had to assemble and test if they fit tightly. As expected, the tenons were a little bit big and forcing them into the mortoise was a little difficult. I decided to grab a hammer and softly tap on the pieces to fit exactlt in the joints. 


https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/7d667676-46b5-481d-92e1-7fab5feed465

This step was a little scary as I needed to be careful not to deform the joints. The soft taps and gradual fixes of the axis made sure that the phone stand assembled perfectly. It came out to be very sturdy and compact. The absense of 'claw' not allowed different orientations but also made the phone stand very compact and aestheically pleasing. Here is the comparison of the two models:

![two](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/80cad58a-310a-4e38-9ef1-2ff4e2e8a2f4)

## ☑️ Testing

After I assesmbled the phone stand, I placed on top a table with height approximately the same as I set in grasshopper. Then I placed the phone in both landscape and portrait orientation to record a video of me pretending to knit. This step was important for me to understand and test how the parameters such as phone angle, table height, student height, and z focus changed the final quality of filming. This is how the videos turned out to be:

Landscape testing:


https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/15591639-b144-4cef-8a1a-ee23ec7a7a6d


Portrait testing: 



https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/443d6aea-2062-476c-834f-7f0e0776b5df


After reviewing the videos, I was very happy with my work. I changed the phone angle in grasshopper to be less steeper as I know my height is less than the height of the student considered in the example, this means that the phone angle should not focus as high up as it originally was set. 

## 🔮 Final Thoughts...



I think I am happy with the final phone stand model as it is as sturdy as I wanted it to be and it is customized for my height.

![final model](final.jpg)





---
# Report 3 - Week of 09/14/2023 #

### Porject files: 
[PRoject 1.zip](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/files/12656562/PRoject.1.zip)

## Challenge Level: 02. Platypus
I decided to choose this level for two reasons. First, I am working with
grasshopper for the first time, I have worked with Fusion 360 before but not with
a software close to grasshopper. Second, I planned on going for Axolotl level with
a really cool idea I had about making a purse from flexible plywood. However, I
did not find the time to get all the materials needed for that project, so I decided
to go with another idea I had. In this paper, I will be presenting a fruit bowl that I
designed on grasshopper and build through laser cut. I think this project is a
good example of Platypus level as it includes a lot grasshopper functions and the
final piece is functional and rigid

## The Design


![WhatsApp Image 2023-09-18 at 7 58 19 PM](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/41e48f15-79e9-499f-9e9a-c651163f9765)


![WhatsApp Image 2023-09-18 at 7 58 20 PM](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/4e67680e-7d80-40ea-8d75-d405e7417f0a)


## Challenges

### What to build?
Like a lot of other classmates, I first struggled with deciding
how to start with this project. At first, I started by
practicing grasshopper and building basics shapes. I also
laser cut the phone stand two times with different
modifications. One thing that I really wanted to learn was
how to make hinges with Grasshopper similar to the phone
stand. I did some searching and found out different mesh
or waffle shapes that can be created from grasshopper. My
biggest challenge was to understand how to make a curved
shape that can serve as a bowl.

![20160908_112545](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/15626d1a-700f-49ae-9fb5-dd588a3d1ab4)


### How to Start?
I started by watching a few videos about parametric
design. I wanted to make a shape that has repeated
patterns. At first, I started by making simple parametric
shapes, such as repeated rectangles. I then built up and
understood some of the existing tutorials on how to design
parametric shapes.

![Screenshot 2023-09-18 212538](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/c2c121da-875d-46ce-9db5-8e5aed669b21)

### 3D Print or Laser Cut?
I wanted to laser cut instead of 3D print. That is because I
am generally very interested in wood working and
assembling. Another upside or downside to laser cutting is
that it requires more design elements. For example, hinges
and placing the shapes in 2D to be able to cut. This is
something I struggled. I was not sure if there was a
functions to turn a rhino 3D model to 2D drawings.

![bowl screenshot](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/6738eb37-96bd-4f13-8e17-c9b89ecb3bbc)


## Process and Results

### Modeling:
In terms of modeling, I started by
drawing a sphere and cylinder. I
achieved the bowl shape using
solid difference. I then added the
ridges by creating a box around the
sphere and using brep to cut
through.



https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/81a5576c-9ccc-4edc-a8b6-4fbbb7f21e35



### Parameters:
The variable parameters that I kept
for this design were, the radius of
the bow, the height of the bowl, the
number of ribs, the thickness of
each rib, and the roundness of the
ribs edges



https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/d6097b94-285d-4cc6-8951-418a1b1f67e3


### Evaluation:
One of the most important things
to take care of was to make sure
the ridges are placed in 2d, ready
to be laser cut. I also checked the
material thickness of the hinges in
the final render to make sure it is
slight smaller than 0.5 cm, which is
the thickness of the plywood used
for laser cut

### Fabrication:
I started by prepping the plywood first. I taped the plywood
on the laser cut bed carefully so it is completey flat. I aligned
all the pieces on the illustrator in a nested form. I also made
sure that all strokes are red color and set to almost 0 pts. I
then cut and placed all the similar pieces together so that it
is easier to assemble


https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/8fc4a5ff-0ff7-4d84-b0ae-67cc1a55f8df

![WhatsApp Image 2023-09-18 at 9 50 24 PM](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/b0bd1d06-78c6-4efd-b6b7-70e5d1fce35c)


### Testing:
At first, I cut two pieces only and
put them together to check if the
material thickness is right. After
the initial test, I assembled and
placed the bowl on a flat table
top to see if it is stable. I also
tested the bowl by putting
weights in it to check if it still
holds and is rigid. I also fliped the
bowl to check if there were any
loose hinges

![WhatsApp Image 2023-09-14 at 1 27 49 PM (1)](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/7053eaad-b138-4bcb-bd60-53c0d06a173a)

## SPECULATIONS

![WhatsApp Image 2023-09-18 at 10 46 17 PM](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/75d6e5f2-f829-42ca-9411-8cf0cc8f870e)


## CONCLUSION
I am really happy with the final design and
prototype of the model. The fruit bowl is very useful
and works as a product that I can use in day to day
life. I am also glad about achieving all this on
grasshopper. This project helped me understand
many things including, design process, parametric
design, and how to learn a new software efficiently. I
also learned from the feedback given in class and
modified the presentation. I made sure the
voiceover was audible


![WhatsApp Image 2023-09-18 at 7 58 20 PM (1)](https://github.com/Berkeley-MDes/tdf-fa23-Farehak/assets/143111800/60345cf1-8590-41b6-a33e-190587cd159f)



---
# Report 4 - Week of 09/21/2023 #
