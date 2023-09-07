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
