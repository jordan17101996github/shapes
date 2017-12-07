# shapes

This is the first shape of the square(rect).
[screenshot](https://github.com/jordan17101996github/shapes/blob/master/Screen%20Shot%202017-12-07%20at%2013.58.48.png)

float a = 0.0;
float s = 0.0;

void setup() {
  size(640, 360);
  noStroke();
  rectMode(CENTER);
  frameRate(30);
}

void draw() {
  
  background(102);
  
  a = a + 0.04;
  s = cos(a)*2;
  
  translate(width/2, height/2);
  scale(s); 
  fill(51);
  rect(0, 0, 50, 50); 
  
  translate(75, 0);
  fill(255);
  scale(s);
  rect(0, 0, 50, 50);       
}

I decided to alter the shape to circle (ellipse). This is the second code.
float a = 0.1;
float s = 0.1;

void setup() {
  size(640, 360);
  noStroke();
  ellipseMode(CENTER);
  frameRate(160);
}

void draw() {
  
  background(102);
  
  a = a + 0.05;
  s = cos(a)*2;
  
  translate(width/2, height/2);
  scale(s); 
  fill(77, 88, 51);
  ellipse(56, 46, 55, 55); 
  
  translate(85, 10);
  fill(33, 66, 255);
  scale(s);
  ellipse(56, 46, 55, 55);       
}
