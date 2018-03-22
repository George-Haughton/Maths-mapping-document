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














