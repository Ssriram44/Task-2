# Task-2


1) //float r=2.5f % 2; //0.5 --commented ----> how is this 0.5 comes as result?

	float r=2.5f / 2;    //1.25
	System.out.println(r);

Explanation :

In the expression 2.5f % 2, the first operand is a floating-point number 2.5f, and the second operand is an integer.
When using the modulus operator, both operands are converted to the same type before performing the operation.
In this case, the integer 2 is promoted to a floating-point number, resulting in 2.0.
So, the result is 0.5.


Task 2 :
-----------------------------------------------------------------------------------------------------------------------------------------------
Write a program for the below mentioned scenario

23 ==> 2+3=5
54 ==> 5+4=9
33 ==> 3+3=9
19 ==> 1+9=10=1+0 // no need for this
//55,65 - no need

int r=14; //use only literals  (hardcoded values)


class SumOfDigits 
{
	public static void main(String args[])
	{
		int[] numbers = {23, 54 , 33 , 43, 31};
		
		for(int num :numbers)
		{
			int digit1 = num /10 ;
			int digit2 = num % 10 ;
			
			int sum  = digit1 + digit2 ;
			
		System.out.println("Sum of the digits"+"  "+ num +"==>" + digit1 + "+" + digit2 + "==>" + sum  );
			
		}
	
		
	}
}

output :
-----------
Sum of the digits  23==>2+3==>5
Sum of the digits  54==>5+4==>9
Sum of the digits  33==>3+3==>6
Sum of the digits  43==>4+3==>7
Sum of the digits  31==>3+1==>4


Task 3 :
---------------------------------------------------------------------------------------------------------------------------------------------
c/=2, e%=2

decrement optr - demo

class DecrementalOperators
{
    public static void main(String args[])
    {
        int c =10 ;
        int e = 5;
        // Applying decrement operators 

        c/=2;         //it means : c= c/2;
        e %=2;       // it means : e= e % 2;

        system.out.println(" c after decrement: " +c);
        system.out.println(" e after decrement: " +e);

 int x=3;
 int y=7;

          system.out.println(x--);
          system.out.println(x--);
          system.out.println(--x);
          system.out.println(--y);
          system.out.println(y--);
          system.out.println(x+y);
        
        
        
    }
}

Output :
--------------
c after decrement :5

e after decrement :1
3
2
0
6
6
5
