```java
// Visualizing the Random function in Processing
int[] rnums = { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 };

void setup() {
  size(600,600);
  background(255); 
  frameRate(1000);
  line(50,500,550,500);
  fill(0);
  text("500",20,503);
  getGaus();
}

void draw() {
  noStroke();
  int rnum = int(abs(getGaus()));
  switch(rnum) {
  case 1: 
    rnums[0] = rnums[0] + 1;
    if(rnums[0]>rnums[1] && rnums[0]>rnums[2] && rnums[0]>rnums[3] && rnums[0]>rnums[4] && rnums[0]>rnums[5] && rnums[0]>rnums[6] && rnums[0]>rnums[7] && rnums[0]>rnums[8] && rnums[0]>rnums[9]) {
      fill(250,50,50);
      rect(50,0,50,rnums[0]);
    } else {
      fill(100,100,100);
      rect(50,0,50,rnums[0]);
    }
    rect(52,0,44,20);
    fill(255,255,255);
    text("1=" + rnums[0],55,15);
    if (rnums[0] == 500) {
      fill(0);
      textSize(20);
      text("And the winner is #1 after " + frameCount + " rolls, by " + numSort(rnums[0]) + " points!", 50,520);
      //numSort();
      noLoop();
    }
    break;
  case 2: 
    rnums[1] = rnums[1] + 1;
    if(rnums[1]>rnums[0] && rnums[1]>rnums[2] && rnums[1]>rnums[3] && rnums[1]>rnums[4] && rnums[1]>rnums[5] && rnums[1]>rnums[6] && rnums[1]>rnums[7] && rnums[1]>rnums[8] && rnums[1]>rnums[9]) {
      fill(250,50,50);
      rect(100,0,50,rnums[1]);
    } else {
      fill(150,150,150);
      rect(100,0,50,rnums[1]);
    }
    rect(102,0,44,20);
    fill(255,255,255);
    text("2=" + rnums[1],105,15);
    if (rnums[1] == 500) {
      fill(0);
      textSize(20);
      text("And the winner is #2 after " + frameCount + " rolls, by " + numSort(rnums[1]) + " points!", 50,520);
      noLoop();
    }
    break;
  case 3: 
    rnums[2] = rnums[2] + 1;
    if(rnums[2]>rnums[0] && rnums[2]>rnums[1] && rnums[2]>rnums[3] && rnums[2]>rnums[4] && rnums[2]>rnums[5] && rnums[2]>rnums[6] && rnums[2]>rnums[7] && rnums[2]>rnums[8] && rnums[2]>rnums[9]) {
      fill(250,50,50);
      rect(150,0,50,rnums[2]);
    } else {
      fill(100,100,100);
      rect(150,0,50,rnums[2]);
    }
    rect(152,0,44,20);
    fill(255,255,255);
    text("3=" + rnums[2],155,15);
    if (rnums[2] == 500) {
      fill(0);
      textSize(20);
      text("And the winner is #3 after " + frameCount + " rolls, by " + numSort(rnums[2]) + " points!", 50,520);
      //numSort();
      noLoop();
    }
    break;
  case 4: 
    rnums[3] = rnums[3] + 1;
    if(rnums[3]>rnums[0] && rnums[3]>rnums[1] && rnums[3]>rnums[2] && rnums[3]>rnums[4] && rnums[3]>rnums[5] && rnums[3]>rnums[6] && rnums[3]>rnums[7] && rnums[3]>rnums[8] && rnums[3]>rnums[9]) {
      fill(250,50,50);
      rect(200,0,50,rnums[3]);
    } else {
      fill(150,150,150);
      rect(200,0,50,rnums[3]);
    }
    rect(202,0,44,20);
    rect(202,0,44,20);
    fill(255,255,255);
    text("4=" + rnums[3],205,15);
    if (rnums[3] == 500) {
      fill(0);
      textSize(20);
      text("And the winner is #4 after " + frameCount + " rolls, by " + numSort(rnums[3]) + " points!", 50,520);
      noLoop();
    }
    break;
  case 5: 
    rnums[4] = rnums[4] + 1;
    if(rnums[4]>rnums[0] && rnums[4]>rnums[1] && rnums[4]>rnums[2] && rnums[4]>rnums[3] && rnums[4]>rnums[5] && rnums[4]>rnums[6] && rnums[4]>rnums[7] && rnums[4]>rnums[8] && rnums[4]>rnums[9]) {
      fill(250,50,50);
      rect(250,0,50,rnums[4]);
    } else {
      fill(100,100,100);
      rect(250,0,50,rnums[4]);
    }
    rect(252,0,44,20);
    fill(255,255,255);
    text("5=" + rnums[4],255,15);
    if (rnums[4] == 500) {
      fill(0);
      textSize(20);
      text("And the winner is #5 after " + frameCount + " rolls, by " + numSort(rnums[4]) + " points!", 50,520);
      //numSort();
      noLoop();
    }
    break;
  case 6: 
    rnums[5] = rnums[5] + 1;
    if(rnums[5]>rnums[0] && rnums[5]>rnums[1] && rnums[5]>rnums[2] && rnums[5]>rnums[3] && rnums[5]>rnums[4] && rnums[5]>rnums[6] && rnums[5]>rnums[7] && rnums[5]>rnums[8] && rnums[5]>rnums[9]) {
      fill(250,50,50);
      rect(300,0,50,rnums[5]);
    } else {
      fill(150,150,150);
      rect(300,0,50,rnums[5]);
    }
    rect(302,0,44,20);
    fill(255,255,255);
    text("6=" + rnums[5],305,15);
    if (rnums[5] == 500) {
      fill(0);
      textSize(20);
      text("And the winner is #6 after " + frameCount + " rolls, by " + numSort(rnums[5]) + " points!", 50,520);
      //numSort();
      noLoop();
    }
    break;
  case 7: 
    rnums[6] = rnums[6] + 1;
    if(rnums[6]>rnums[0] && rnums[6]>rnums[1] && rnums[6]>rnums[2] && rnums[6]>rnums[3] && rnums[6]>rnums[4] && rnums[6]>rnums[5] && rnums[6]>rnums[7] && rnums[6]>rnums[8] && rnums[6]>rnums[9]) {
      fill(250,50,50);
      rect(350,0,50,rnums[6]);
    } else {
      fill(100,100,100);
      rect(350,0,50,rnums[6]);
    }
    rect(352,0,44,20);
    fill(255,255,255);
    text("7=" + rnums[6],355,15);
    if (rnums[6] == 500) {
      fill(0);
      textSize(20);
      text("And the winner is #7 after " + frameCount + " rolls, by " + numSort(rnums[6]) + " points!", 50,520);
      //numSort();
      noLoop();
    }
    break;
  case 8: 
    rnums[7] = rnums[7] + 1;
    if(rnums[7]>rnums[0] && rnums[7]>rnums[1] && rnums[7]>rnums[2] && rnums[7]>rnums[3] && rnums[7]>rnums[4] && rnums[7]>rnums[5] && rnums[7]>rnums[6] && rnums[7]>rnums[8] && rnums[7]>rnums[9]) {
      fill(250,50,50);
      rect(400,0,50,rnums[7]);
    } else {
      fill(150,150,150);
      rect(400,0,50,rnums[7]);
    }
    rect(402,0,44,20);
    fill(255,255,255);
    text("8=" + rnums[7],405,15);
    if (rnums[7] == 500) {
      fill(0);
      textSize(20);
      text("And the winner is #8 after " + frameCount + " rolls, by " + numSort(rnums[7]) + " points!", 50,520);
      //numSort();
      noLoop();
    }
    break;
  case 9: 
    rnums[8] = rnums[8] + 1;
    if(rnums[8]>rnums[0] && rnums[8]>rnums[1] && rnums[8]>rnums[2] && rnums[8]>rnums[3] && rnums[8]>rnums[4] && rnums[8]>rnums[5] && rnums[8]>rnums[6] && rnums[8]>rnums[7] && rnums[8]>rnums[9]) {
      fill(250,50,50);
      rect(450,0,50,rnums[8]);
    } else {
      fill(100,100,100);
      rect(450,0,50,rnums[8]);
    }
    rect(452,0,44,20);
    fill(255,255,255);
    text("9=" + rnums[8],455,15);
    if (rnums[8] == 500) {
      fill(0);
      textSize(20);
      text("And the winner is #9 after " + frameCount + " rolls, by " + numSort(rnums[8]) + " points!", 50,520);
      //numSort();
      noLoop();
    }
    break;
  case 10: 
    rnums[9] = rnums[9] + 1;
    if(rnums[9]>rnums[0] && rnums[9]>rnums[1] && rnums[9]>rnums[2] && rnums[9]>rnums[3] && rnums[9]>rnums[4] && rnums[9]>rnums[5] && rnums[9]>rnums[6] && rnums[9]>rnums[7] && rnums[9]>rnums[8]) {
      fill(250,50,50);
      rect(500,0,50,rnums[9]);
    } else {
      fill(150,150,150);
      rect(500,0,50,rnums[9]);
    }
    rect(502,0,44,20);
    fill(255,255,255);
    text("10=" + rnums[9],499,15);
    if (rnums[9] == 500) {
      fill(0);
      textSize(20);
      text("And the winner is #10 after " + frameCount + " rolls, by " + numSort(rnums[9]) + " points!", 50,520);
      noLoop();
    }
    break;
  }
}

int numSort(int leadBy) {
  rnums = sort(rnums);
  leadBy = leadBy - rnums[8];
  return leadBy;
}
float getGaus(){
  float x = 0;
  for (int y = 0; y < 10; y++) {
    x = randomGaussian() * 19.01;     
  }
  println(x);
  return x;
}
```
