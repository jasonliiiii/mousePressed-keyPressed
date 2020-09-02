# mousePressed-keyPressed
change the width and the height of a circle
float widthOfCircle = 50;
float heightOfCircle = 50;
void setup(){
  size(800,800);
}
void draw(){
  ellipse(width/2, height/2, widthOfCircle, heightOfCircle);
}
void mousePressed(){
  widthOfCircle = widthOfCircle + 1;
}
void keyPressed(){
  heightOfCircle = heightOfCircle + 1;
}

click to shift the circle right or left
float x = 400; 
float y = 400;
void setup(){
  size(800,800);
}
void draw(){
  background(225,225,225);
  ellipse(x,y,50,50);
}
void mousePressed(){
  x = x + 10;
}
void keyPressed(){
  x = x - 10;
}

mouse click = circle ; key click = rectangle
void setup(){
  size(800,800);
}
void draw(){}
void mousePressed(){
  background(255,255,255);
  fill(100,120,150);
  ellipse(100,100,50,50);
  ellipse(700,100,50,50);
  ellipse(100,700,50,50);
  ellipse(700,700,50,50);
}
void keyPressed(){
  background(255,255,255);
  fill(90,150,190);
  rect(100,100,50,50);
  rect(700,100,50,50);
  rect(100,700,50,50);
  rect(700,700,50,50);
}

