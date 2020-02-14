# hw3
1. What code draws the blades of grass?
function draw() {
  stroke(random(60, 70), 100, 90);
  line(x, height-10, x+random(-10, 10), height-10-random(h));
  noStroke();
  
2. What code makes the "lawnmower" come by? How often does it come by?
if (random(1000) > 999) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
  }
  any numbers between 999-1000
  
3. What's the point of the h variable?
h is the prime hight of the grass
h is for height

4.What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?
-10 control the starting way where the grass grow,to make sure the grass grow from the side
