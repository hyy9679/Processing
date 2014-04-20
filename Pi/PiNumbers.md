```java

// Visualizing instances of numbers in pi
import java.math.BigInteger;
int[] rnums = { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 };

final BigInteger TWO = BigInteger.valueOf(2);
final BigInteger THREE = BigInteger.valueOf(3);
final BigInteger FOUR = BigInteger.valueOf(4);
final BigInteger SEVEN = BigInteger.valueOf(7);

BigInteger q = BigInteger.ONE;
BigInteger r = BigInteger.ZERO;
BigInteger t = BigInteger.ONE;
BigInteger k = BigInteger.ONE;
BigInteger n = BigInteger.valueOf(3);
BigInteger l = BigInteger.valueOf(3);

void setup() {
  size(600, 1100);
  background(255); 
  frameRate(5000);
  line(50, 1000, 550, 1000);
  fill(0);
  text("1000", 20, 1003);
}

void draw() {
  noStroke();
  BigInteger nn, nr;
  if (FOUR.multiply(q).add(r).subtract(t).compareTo(n.multiply(t)) == -1) {
    println(n.toString());
    int i = n.intValue();
    switch(i) {
    case 1: 
      rnums[0] = rnums[0] + 1;
      if (rnums[0]>rnums[1] && rnums[0]>rnums[2] && rnums[0]>rnums[3] && rnums[0]>rnums[4] && rnums[0]>rnums[5] && rnums[0]>rnums[6] && rnums[0]>rnums[7] && rnums[0]>rnums[8] && rnums[0]>rnums[9]) {
        fill(250, 50, 50);
        rect(50, 0, 50, rnums[0]);
      } 
      else {
        fill(100, 100, 100);
        rect(50, 0, 50, rnums[0]);
      }
      rect(52, 0, 44, 20);
      fill(255, 255, 255);
      text("1=" + rnums[0], 55, 15);
      if (rnums[0] == 1000) {
        fill(0);
        textSize(20);
        text("The first number to appear 1000 times in pi is 5 by " + numSort(rnums[0]), 50, 1020);
        //numSort();
        noLoop();
      }
      break;
    case 2: 
      rnums[1] = rnums[1] + 1;
      if (rnums[1]>rnums[0] && rnums[1]>rnums[2] && rnums[1]>rnums[3] && rnums[1]>rnums[4] && rnums[1]>rnums[5] && rnums[1]>rnums[6] && rnums[1]>rnums[7] && rnums[1]>rnums[8] && rnums[1]>rnums[9]) {
        fill(250, 50, 50);
        rect(100, 0, 50, rnums[1]);
      } 
      else {
        fill(150, 150, 150);
        rect(100, 0, 50, rnums[1]);
      }
      rect(102, 0, 44, 20);
      fill(255, 255, 255);
      text("2=" + rnums[1], 105, 15);
      if (rnums[1] == 1000) {
        fill(0);
        textSize(20);
        text("The first number to appear 1000 times in pi is 5 by " + numSort(rnums[1]), 50, 1020);
        noLoop();
      }
      break;
    case 3: 
      rnums[2] = rnums[2] + 1;
      if (rnums[2]>rnums[0] && rnums[2]>rnums[1] && rnums[2]>rnums[3] && rnums[2]>rnums[4] && rnums[2]>rnums[5] && rnums[2]>rnums[6] && rnums[2]>rnums[7] && rnums[2]>rnums[8] && rnums[2]>rnums[9]) {
        fill(250, 50, 50);
        rect(150, 0, 50, rnums[2]);
      } 
      else {
        fill(100, 100, 100);
        rect(150, 0, 50, rnums[2]);
      }
      rect(152, 0, 44, 20);
      fill(255, 255, 255);
      text("3=" + rnums[2], 155, 15);
      if (rnums[2] == 1000) {
        fill(0);
        textSize(20);
        text("The first number to appear 1000 times in pi is 5 by " + numSort(rnums[2]), 50, 1020);
        //numSort();
        noLoop();
      }
      break;
    case 4: 
      rnums[3] = rnums[3] + 1;
      if (rnums[3]>rnums[0] && rnums[3]>rnums[1] && rnums[3]>rnums[2] && rnums[3]>rnums[4] && rnums[3]>rnums[5] && rnums[3]>rnums[6] && rnums[3]>rnums[7] && rnums[3]>rnums[8] && rnums[3]>rnums[9]) {
        fill(250, 50, 50);
        rect(200, 0, 50, rnums[3]);
      } 
      else {
        fill(150, 150, 150);
        rect(200, 0, 50, rnums[3]);
      }
      rect(202, 0, 44, 20);
      rect(202, 0, 44, 20);
      fill(255, 255, 255);
      text("4=" + rnums[3], 205, 15);
      if (rnums[3] == 1000) {
        fill(0);
        textSize(20);
        text("The first number to appear 1000 times in pi is 5 by " + numSort(rnums[3]), 50, 1020);
        noLoop();
      }
      break;
    case 5: 
      rnums[4] = rnums[4] + 1;
      if (rnums[4]>rnums[0] && rnums[4]>rnums[1] && rnums[4]>rnums[2] && rnums[4]>rnums[3] && rnums[4]>rnums[5] && rnums[4]>rnums[6] && rnums[4]>rnums[7] && rnums[4]>rnums[8] && rnums[4]>rnums[9]) {
        fill(250, 50, 50);
        rect(250, 0, 50, rnums[4]);
      } 
      else {
        fill(100, 100, 100);
        rect(250, 0, 50, rnums[4]);
      }
      rect(252, 0, 44, 20);
      fill(255, 255, 255);
      text("5=" + rnums[4], 255, 15);
      if (rnums[4] == 1000) {
        fill(0);
        textSize(20);
        text("The first number to appear 1000 times in pi is 5 by " + numSort(rnums[4]), 50, 1020);
        //numSort();
        noLoop();
      }
      break;
    case 6: 
      rnums[5] = rnums[5] + 1;
      if (rnums[5]>rnums[0] && rnums[5]>rnums[1] && rnums[5]>rnums[2] && rnums[5]>rnums[3] && rnums[5]>rnums[4] && rnums[5]>rnums[6] && rnums[5]>rnums[7] && rnums[5]>rnums[8] && rnums[5]>rnums[9]) {
        fill(250, 50, 50);
        rect(300, 0, 50, rnums[5]);
      } 
      else {
        fill(150, 150, 150);
        rect(300, 0, 50, rnums[5]);
      }
      rect(302, 0, 44, 20);
      fill(255, 255, 255);
      text("6=" + rnums[5], 305, 15);
      if (rnums[5] == 1000) {
        fill(0);
        textSize(20);
        text("The first number to appear 1000 times in pi is 5 by " + numSort(rnums[5]), 50, 1020);
        //numSort();
        noLoop();
      }
      break;
    case 7: 
      rnums[6] = rnums[6] + 1;
      if (rnums[6]>rnums[0] && rnums[6]>rnums[1] && rnums[6]>rnums[2] && rnums[6]>rnums[3] && rnums[6]>rnums[4] && rnums[6]>rnums[5] && rnums[6]>rnums[7] && rnums[6]>rnums[8] && rnums[6]>rnums[9]) {
        fill(250, 50, 50);
        rect(350, 0, 50, rnums[6]);
      } 
      else {
        fill(100, 100, 100);
        rect(350, 0, 50, rnums[6]);
      }
      rect(352, 0, 44, 20);
      fill(255, 255, 255);
      text("7=" + rnums[6], 355, 15);
      if (rnums[6] == 1000) {
        fill(0);
        textSize(20);
        text("The first number to appear 1000 times in pi is 5 by " + numSort(rnums[6]), 50, 1020);
        //numSort();
        noLoop();
      }
      break;
    case 8: 
      rnums[7] = rnums[7] + 1;
      if (rnums[7]>rnums[0] && rnums[7]>rnums[1] && rnums[7]>rnums[2] && rnums[7]>rnums[3] && rnums[7]>rnums[4] && rnums[7]>rnums[5] && rnums[7]>rnums[6] && rnums[7]>rnums[8] && rnums[7]>rnums[9]) {
        fill(250, 50, 50);
        rect(400, 0, 50, rnums[7]);
      } 
      else {
        fill(150, 150, 150);
        rect(400, 0, 50, rnums[7]);
      }
      rect(402, 0, 44, 20);
      fill(255, 255, 255);
      text("8=" + rnums[7], 405, 15);
      if (rnums[7] == 1000) {
        fill(0);
        textSize(20);
        text("The first number to appear 1000 times in pi is 5 by " + numSort(rnums[7]), 50, 1020);
        //numSort();
        noLoop();
      }
      break;
    case 9: 
      rnums[8] = rnums[8] + 1;
      if (rnums[8]>rnums[0] && rnums[8]>rnums[1] && rnums[8]>rnums[2] && rnums[8]>rnums[3] && rnums[8]>rnums[4] && rnums[8]>rnums[5] && rnums[8]>rnums[6] && rnums[8]>rnums[7] && rnums[8]>rnums[9]) {
        fill(250, 50, 50);
        rect(450, 0, 50, rnums[8]);
      } 
      else {
        fill(100, 100, 100);
        rect(450, 0, 50, rnums[8]);
      }
      rect(452, 0, 44, 20);
      fill(255, 255, 255);
      text("9=" + rnums[8], 455, 15);
      if (rnums[8] == 1000) {
        fill(0);
        textSize(20);
        text("The first number to appear 1000 times in pi is 5 by " + numSort(rnums[8]), 50, 1020);
        //numSort();
        noLoop();
      }
      break;
    case 0: 
      rnums[9] = rnums[9] + 1;
      if (rnums[9]>rnums[0] && rnums[9]>rnums[1] && rnums[9]>rnums[2] && rnums[9]>rnums[3] && rnums[9]>rnums[4] && rnums[9]>rnums[5] && rnums[9]>rnums[6] && rnums[9]>rnums[7] && rnums[9]>rnums[8]) {
        fill(250, 50, 50);
        rect(500, 0, 50, rnums[9]);
      } 
      else {
        fill(150, 150, 150);
        rect(500, 0, 50, rnums[9]);
      }
      rect(502, 0, 44, 20);
      fill(255, 255, 255);
      text("0=" + rnums[9], 499, 15);
      if (rnums[9] == 1000) {
        fill(0);
        textSize(20);
        text("The first number to appear 1000 times in pi is 5 by " + numSort(rnums[9]), 50, 1020);
        noLoop();
      }
      break;
    }
    nr = BigInteger.TEN.multiply(r.subtract(n.multiply(t)));
    n = BigInteger.TEN.multiply(THREE.multiply(q).add(r)).divide(t).subtract(BigInteger.TEN.multiply(n));
    q = q.multiply(BigInteger.TEN);
    r = nr;
    System.out.flush();
  }
  else {
    nr = TWO.multiply(q).add(r).multiply(l);
    nn = q.multiply((SEVEN.multiply(k))).add(TWO).add(r.multiply(l)).divide(t.multiply(l));
    q = q.multiply(k);
    t = t.multiply(l);
    l = l.add(TWO);
    k = k.add(BigInteger.ONE);
    n = nn;
    r = nr;
  }
}

int numSort(int leadBy) {
  rnums = sort(rnums);
  leadBy = leadBy - rnums[8];
  return leadBy;
}

```
