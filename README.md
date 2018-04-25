# Maths Mapping Document

## Lowest common multiple
The lowest common multiple is the smallest number that a given amount of numbers can divide into and finding the lowest common multiple of two numbers is very simple. Firstly, one way to find teh LCM of two numbers is to start by listing the prime numbers for each of the two numbers. So for example if we have take 60 and 70, the prime numbrs of 60 are 2, 2, 3, 5 and the prime numbers of 70 are 2, 5 and 7. Then we have to multiply each factor the greatest number of times it appears in both numbers. If the same number occurs more than once in both numbers, you have to multiply the factor the greatest number of times it occurs. So we have 60 = 2 x 2 x 3 x 5 and 70 = 2 x 5 x 7; 2 occurs twice, 3 occurs once, 5 occurs once and 7 occurs once. We then have to multiple them; 2 x 2 x 3 x 5 x 7 = 420. So 420 is the LCM of 60 and 70.

## Greatest common divisor
The greatest common divisor is the biggest number that will divide into (that is the largest number that is a factor of) the numbers given and it is the number that contains all of the factors common to both numbers. First we need to factorize each number; with 60 the outcome is 5 x 3 x 2 x 2 and with 70 the outcome is 7 x 5 x 2. We then look at the similarities when it comes to each numbers prime factors. 5 appears once in 60's prime factors and once in 70's, and 2 appears once in 70's but twice in 60's but as it is only once is 70's we can only use it once. So now we have 5 x 2 which equals 10. So the largest number that can be used to divide 60 and 70 is 10.

## Arithmetic and Geometric Progression
Arithmetic progression is a sequence of numbers, thats difference is constant within the sequence; for example 1, 2, 3, 4 is an Arithmetic progression because the numbers are always 1 apart. Secondly, we have Geometric progression. This is a sequence where instead of the difference being constantly the same between each number, each number in the sequence is multiplied to get to the next number. For example 1, 4, 16, 64, 256; each number is multiplied by 4. 

### Algorithm to calculate Arithmetic and Geometric Progression.
#include <iostream>
	

	using namespace std;
	

	int main(){
	  int a, sum, geo = 1;
	  cout << "Number";
	  cin >> a;
	  
	  
	  for (int i=1; i <= 10; i++){
	    sum += a;
	    geo *= a;
	    cout << "Iteration: " << i << endl;
	    cout << "Airthmetic: " << sum  << endl;
	    cout << "Geometric: " << geo << endl;
	    cout << endl;
	  }
	  return 0;
	
## Conditional Probability 
Lets take the example that you have been asked to give the probabilty of a 5 being rolled on a fair die. There is only one side of the die that is 5, and there are only 6 possible outcomes which means the probability of rolling a 5 is 1/6. Additionally, if you had been told the number that the number rolled was an odd number, the probability of you rolling a 5 would now be 1/3; as there are only 3 odd numbers on a die. The revised probabilty that an event A has occured, given the information that an additional event B has definitely occured, is called Conditional Probability. The reason employed within this example can be explained to yield the formula in the following definition:

![](https://i.gyazo.com/3aa9d793656a22f6ed6e8c6a1ca1aa7f.png)

#### What is the probability of having 7 when rolling two die?
There are 36 possible outcomes when it comes to rolling two die. For each of the possible outcomes add the two numbers up and count how many times it is equal to seven; after doing this you will realize there are 6 times, both numbers are equal to 7. This being said if there are 6 outcomes that add up to 7, and there are 36 possible outcomes the probability of you rolling a 7 on two dic will be 6/36, simplified down to 1/6.

#### What is the probability of having having at least one 2 when rolling two dice?
There are 36 possible outcomes when it comes to rolling two dice. First count how many times after I roll the two die that at least one of the two numbers will be a 2. There is 11 possible outcomes that will contain at least one 2. Now we know this we can say that the possibility of rolling two die and one of them being 2 is 11/36.

#### What is the probability of having 7 after rolling a 2?
There are 6 possible outcomes when it comes to rolling a die. If i already have a 2 and i need to get to seven i will need to count how many of the 6 outcomes, when added onto 2 will make 7. There is only one outcome that will help equal 7 and this is 5. Knowing this, the possibility of rolling of having 7 after i have just roled a 2 is 1/6.

Here is a picture that shows all of the possible outcomes:

![](https://gyazo.com/623c7273669a505f75bc3117f1ff168d.png)

## What is the probability of a random integer being divisible by 5?
Every fifth number is divisible by 5 as they are all in the 5 times table, so the probability in question is 1/5. The numeric answeris plausible and actually correct; but the idea of selecting a random integer needs to be explained in more detail. These are 5 equivalence classes 0, 1, 2, 3, 4 and modulo 5 (these are the remainders of division by 5.) All events of selecting one of them are very equiprobable, so much that each has the probability of 1/5. The problem of picking one equivalence class out of 5 is the fact is is is not the same as the one we need to solve which will require us to pick select a member of an infinite set. Additionally, if all integers are equiprobable, then selecting one will give us the probability of 0. Although this is useful it does not answer the question fully.

Normally, randomly picking an integer is only possible if it is coming from an infinite set; so we always select from an infinite set but do this repeatedly each time selecting from a bigger set. Here is a better representation of it:

![](https://gyazo.com/66909cf7342cb633ed412fa746f05adb.png)

Aditionally this screenshot will demonstrate how using this definition can answer our problem: 

![](https://gyazo.com/15849c8cb0193fe30989cc035111152a.png)

## Co-ordinate geometry
Co-ordinate geometry can seem daunting if you dont fully understand it. There are alot of formulas and different definitions you need to get to grips with. I am going to explain each definition and formula to help you better understand them all. Parallel lines, this is where two lines both have the exact same slope and different y-intercept, here is an example of two Paralell lines:

![](https://gyazo.com/19ee05acaba30694d4f9a82e862a3360.png)

Next we have Perpendicular lines these are two lines that both make a 90 degree angle, if their slopes are negative reciprocals. As you can see in the picture below, lines M and B would be the Perpendicular lines as they make the 90 degree angle.

![](https://gyazo.com/7d3bb59f6c2af25b657d6f6ad36cb7bf.png)

A Parallelogram is a quadrilalteral shape that has two pars of Parallel lines. As you can see lines A and B are the first set of Parallel lines and D and C are the second set, these two together create the Parallelogram.

![](https://gyazo.com/2ebd65ec1c8c96fced77d2dbb69df077.png)

Now we have a Rectangle which everyone can easily identify, as it has four right angles and is also a quadrilateral. Two of the four lines will be equal to one another and the same with the other two lines. I will add an example of a rectangle just as reference.

![](https://gyazo.com/c0826d305a277877a41aee6cbe0c4121.png)

Rhombus, again this is a quadrilateral but instead of four right angles like the Rectangle it has four equal sides and can be described as a diamond.

![](https://gyazo.com/ed1abe072ca1b75260bc336f29eb225d.png)

Lastly for the shapes, we have the simple and the very well known, Square. Unlike the Rhombus and Rectangle it does not just have four right angles or just four equal sides it has both; a completel symmetrical shape.

![](https://gyazo.com/969db51a4a60d7d8647322adb83875f9.png)

Now we move onto formulas. Firstly we are going to look at the Slope formula which can be used to fine the Slope of a line that passes through two points. For example if we take two points such as (5, 4) and (8, 6) and using the formula m = y2-y1/x2-x1. Putting in our number sthat in this case would be 6 being our y2 and 4 being our y1 which gives us 2 and then 8 being x2 and 5 being x1. This gives us 6-4/8-5 which will simplify to 2/3 so the slope of this line would be two thirds, which is m = 2/3.

![](https://gyazo.com/e2467c4e10d2b72e1cc3f89720f8231d.png)

Next we have the Distance formula which is used to find the disance between two points (x1, y1) and (x2, y2. So for example lets say we are trying to find the difference between (2, 1) and (1, 5) we can draw the lines that form a right-angled triangle, using the points as thee two corners, then we will need to find the lengths of the sides and to do this we will need to subtract the x-values and the y-values. 

![](https://gyazo.com/2da08963fa800c14a1ed5bf975c0c64c.png)

Then use the Pythagorean Theorem to find the length of the third side, which we also know as the hypotenuse of the triangle. Here is is being put to use:

![](https://gyazo.com/12c8f1557f025aba299b757cdb2533bd.png)
 
As you can see from the picture after using Pythagorean Theorem we get the answer 5. So the distance between (2, 1) and (1, 5) is 5.
 
Lastly, we are going to look at the Midpoint formula this formual as in the name is used to find the Midpoint of two points. 
 
![](https://gyazo.com/e11908eed4fa264542e38c9179c7a4bf.png)
 
So if you need to find the point that is exactlty in the middle of two other points, all you need to do is average the x-values and the y-values. For example if we take (-1, 2) and (3, 6) and use the Midpoint formula it will look something like this: 
 
![](https://gyazo.com/76313e6a9d3d96dc873e5a2f935f2348.png)
 
As you can see from the formula the Midpoint between (-1, 2) and (3, 6) is (1, -2).
 
## Rate of change 
ROC is the speed at which a variable changes over a specific period of time. Rate of change is normally mentioned when referred to momentum and it can normally be represented as a ratio between a change in one variable relative to a corresponding change in another. Graphically, the rate of change is expressed as a slope if line.

Here are a couple of examples:
The question is f (x) = x3 + 10, and we are trying to work out the rate of change from 0 to 1. Firstly, we need to put the biggest number, this being 1 into the formula. So 1 x 1 x 1 + 10 = 11, then 0 x 0 x 0 + 10 = 10. Now we need to work out the answer of the question minus the inputs. So we have 11 – 10/ 1 - 0  = 1. So the rate of change of 1 – 0 = 1. Also the question asks for the answer to be put into binary, which for us is easy as the answer to the question was 1 which is already in binary.

Another example is if the question is F (x) = 3x3 + 2x2 + 20x + 100. Again we will need to put the biggest number into the formula first which in this case is 16. So we do 16 x 16 x 16 which = 4096, then 4096 x 4096 

f (x) = x3 = 10
CHANGE FROM 0 - 1
1 x 1 x 1 + 10 = 11
0 x 0 x 0 + 10= 10
11 - 10/ 1 - 0 = 1 
in binary = 1
 
## Integral Calculus 
This involves summing up infinitesimally small portions of a mathmatical expression to more commonly find the next higher dimension or the area. If a given shape is too complicated we use Integral calculus to calculate the shapes area and next higher dimension. Additionally, when the shape is too complicated we use Integral Calculus with the two points a and b (normally 2 points in a graph) and then use it to calculate the area of a and b which is called the area of a function.

Here are the main formulas that we use when going about calculating the area of curved lines and using Integral calculus:

![](https://raw.githubusercontent.com/matthewsides/Mathematics/master/IC_MF.png)


The symbol ∫ is used to describe the finding of an intergral or intergals which is called intergration. A and B are shown on each side of the ∫ symbol to represent that we would like to find the area from A to B. This helps when looking at the shape we are trying to find the area of as we can simply label two points A and B. Curved lines can be difficult to answer and this is why we use Higher derivative to help us. Higher derivative is a way of making a complex or hard function easier/simpler. A simple function is most commonly referred to as a linear function as it is seen as a straight line on a graph but again when it becomes curved we use Higher derivative to simplify the function. In essence by multiplying the function against the derivative of the function within the shape we can create an infinite area of rectangles to find the area of the shape using the information we already know such as the formula for the area of the rectangle.

Here are a couple examples of integral calculus being used:

![](https://raw.githubusercontent.com/matthewsides/Mathematics/master/IC_E1.png)

![](https://raw.githubusercontent.com/matthewsides/Mathematics/master/IC_E2.png)
 
## Vector 
A Vector has to have two distinguishable quantities: a direction and a magnitude. Without a direction it is not a Vector but a Scalar and if u give a Scalar a direction it becomes a Vector. Most commonly Vectors as represented by an arrow which is perfect as you can see the direction and the magnitude (which is the length of the arrow) very clearly. 

We can create many shapes using Vectors, such as triangles, squares and rectangles and I have created an Algorthm that when told to will create shapes using Vectors. As a reference here is the code:

```
<html>
<body>

<canvas id="myCanvas" width="300" height="150" style="border:1px solid #d3d3d3;"></canvas>

<br>
<button onclick="move(1)">LEFT</button>
<button onclick="move(2)">UP</button>
<button onclick="move(3)">DOWN</button>
<button onclick="move(4)">RIGHT</button>
<br>
<button onclick="move(5)">DIAGONAL RIGHT DOWN</button>
<button onclick="move(6)">DIAGONAL RIGHT UP</button>
<br>
<button onclick="move(7)">DIAGONAL LEFT DOWN</button>
<button onclick="move(8)">DIAGONAL LEFT UP</button>
<br>
<button onclick="shape()">SHAPE?</button>


<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.beginPath();

var curX=parseInt(prompt("Please enter the initial X"));;
var curY=parseInt(prompt("Please enter the initial Y"));;

function move(dir){
var mag = parseInt(prompt("Please enter the magnitude"));

if(dir==1){
  //left
  ctx.moveTo(curX, curY);
  curX = curX-mag;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Left / Vector Magnitude: "+mag);
}else if(dir==2){
  //up
  ctx.moveTo(curX, curY);
  curY = curY-mag;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Up / Vector Magnitude: "+mag);
}else if(dir==3){
  //down
  ctx.moveTo(curX, curY);
  curY = curY+mag;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Down / Vector Magnitude: "+mag);
}else if(dir==4){
  //right
  ctx.moveTo(curX, curY);
  curX = curX+mag;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Right / Vector Magnitude: "+mag);
}else if(dir==5){
  //diagonal right down
  ctx.moveTo(curX, curY);
  curX = curX+mag/2;
  curY = curY+mag/2;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Diagonal Right Down / Vector Magnitude: "+mag);
}else if(dir==6){
  //diagonal right up
  ctx.moveTo(curX, curY);
  curX = curX+mag/2;
  curY = curY-mag/2;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Diagonal Right Up / Vector Magnitude: "+mag);
}else if(dir==7){
  //diagonal left down
  ctx.moveTo(curX, curY);
  curX = curX-mag/2;
  curY = curY+mag/2;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Diagonal Left Down / Vector Magnitude: "+mag);
}else if(dir==8){
  //diagonal left up
  ctx.moveTo(curX, curY);
  curX = curX-mag/2;
  curY = curY-mag/2;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Diagonal Left Up / Vector Magnitude: "+mag);
}

ctx.stroke();

}

function shape(){
  var shape = prompt("Is this a shape Y/N?");

  if(shape=='Y'){
      prompt("What shape?");
  }else {
      alert("Keep drawing!");
  }
}

</script>

</body>
</html>
```


Additionally, here is a screenshot of a upside down triangle I made using my Algorithm:

![](


























                                                                                                          

