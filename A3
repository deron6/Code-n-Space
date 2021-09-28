let core01_XPos=100;
let core01_speed=4;
let core02_XPos=300;
let core02_speed=2.5;
let core03_XPos=300;
let core03_speed=5;
let core04_XPos=500
let core05_XPos=400
let angle=0



function setup() {
  createCanvas(600, 600);
}

function draw() {
  background(0)
noFill()
stroke(255)
strokeWeight(1.5)
angleMode(DEGREES)

//core01
fill('red')
if(core01_XPos>200 || core01_XPos<0) {core01_speed=core01_speed*-1;}
core01_XPos=core01_XPos + core01_speed
triangle(core01_XPos,100,core02_XPos, core01_XPos,200,200)


//core02
fill('yellow')
if(core02_XPos>400 || core02_XPos<0) {core02_speed=core02_speed*-1;}
core02_XPos=core02_XPos + core02_speed

triangle(core02_XPos,core01_XPos,500,core01_XPos,400,200)

//core03
fill('red')
if(core03_XPos>500 || core03_XPos<0) {core03_speed=core03_speed*-1;}
core03_XPos=core03_XPos + core03_speed + core02_speed
triangle(core03_XPos,500,core02_XPos,500,core02_XPos,400)

//core04
fill('blue')
triangle(core03_XPos,core04_XPos,core04_XPos,core04_XPos,core03_XPos,core05_XPos)


//core05
fill('purple')
push()
translate(200, 200)
rotate(angle)
triangle(200,200,200,core05_XPos,225,300)
triangle(400,200,core05_XPos,core05_XPos,375,300)
pop()
angle++;
//core06
push()
translate(0,0)
rotate(angle)
triangle(300,300,200,400,375,300)
pop()
angle++

push()
translate(CENTER)
rotate(-angle)
triangle(400,200,400,400,225,300)
pop()
angle++

push()
translate(200,200)
rotate(angle)
line(200,200,400,200)
pop()
angle++

push()
translate(200,400)
rotate(angle)
line(200,400,400,400)
pop()
-angle++

fill('white')
push()
translate(200,135)
rotate(angle)
triangle(core01_XPos,core01_XPos,300,core01_XPos,200,135)
triangle(core01_XPos,core01_XPos,200,200,200,135)
pop()
angle++

triangle(core02_XPos,100,500,100,core05_XPos,135)
triangle(core02_XPos,100,core05_XPos,200,core05_XPos,135)
triangle(core01_XPos,500,300,500,200,465)
triangle(core01_XPos,500,200,core05_XPos,200,465)
triangle(core02_XPos,core04_XPos,core04_XPos,core04_XPos,core05_XPos,465)
triangle(core02_XPos,500,core05_XPos,core05_XPos,core05_XPos,465)














}
