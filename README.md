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

#### What is the probability of having a 7, knowing for sure that I will roll a 2?
There are 6 possible outcomes when it comes to rolling two dice. If I already know i will roll a 2.

## What is the probability of a random integer being divisible by 5?
Every fifth number is divisible by 5 as they are all in the 5 times table, so the probability in question is 1/5. The numeric answeris plausible and actually correct; but the idea of selecting a random integer needs to be explained in more detail. These are 5 equivalence classes 0, 1, 2, 3, 4 and modulo 5 (these are the remainders of division by 5.) All events of selecting one of them are very equiprobable, so much that each has the probability of 1/5. The problem of picking one equivalence class out of 5 is the fact is is is not the same as the one we need to solve which will require us to pick select a member of an infinite set. Additionally, if all integers are equiprobable, then selecting one will give us the probability of 0. Although this is useful it does not answer the question fully.

Normally, randomly picking an integer is only possible if it is coming from an infinite set; so we always select from an infinite set but do this repeatedly each time selecting from a bigger set. Here is a better representation of it:

![](https://gyazo.com/66909cf7342cb633ed412fa746f05adb)












