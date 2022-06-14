# MyWk1
Day1_assignment

package week1.day1;

public class MyPrime {
public static void main(String[] args) {
	int a = 13;
	boolean xfactor = false;
	
	for(int i=2; i<=(a/2);i++) {
		if((a%2) ==0) {
			xfactor = true;
		}
	
	}
		
		
		if (xfactor) 
			System.out.println("13 is not a prime number");
		else 
			System.out.println("13 is a prime number");
			
		}
}



-----------------------------------------------------------

package week1.day1;

public class MyFactorialNum {
	public static void main(String[] args) {
		int x = 5;
		int fact = 1;
		for(int i=1;i<=x;i++) {
			fact = fact *i;
		}
		System.out.println("Factorial of 5 is");
		System.out.println(fact);
	}

}
________________________________________________________________


package week1.day1;

public class MyFiboNum {
	public static void main(String[] args) {
		int x = 0;
	    int y = 1;
	    int sum;
		System.out.println(x);
		System.out.println(y);
		for(int i=1;i<=7;i++) {
			sum = x+y;
			x = y;
			y = sum;
			System.out.println(sum);
			
		}
	}
		
	}


