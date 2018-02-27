# Program-1.7
Intro to Java Programming, Comprehensive Version, 10th Edition, Y. Daniel Liang

Question:
        
        
        (ApproximatePI) PI can be computed using the following formula:
        
        PI = 4 x ( 1 - 1/3 + 1/5 - 1/7 + 1/9 - 1/11 + ... )
        
        Write a prgram that displays the result of 4 x (1- 1/3 + 1/5 - 1/7 + 1/9 - 1/11)
        and 4 x (1 - 1/3 + 1/5 - 1/7 + 1/9 - 1/11 + 1/13). Use 1.0 instead of 1 in your program.
        
Code:

        public class s_1_7 {

	        public static void main (String args[]){
		
		       double pi = (4) * ((1.0) - (1.0/3) + (1.0/5) - (1.0/7) + (1.0/9) - (1.0/11));
		       double pi2 = (4) * ((1.0) - (1.0/3) + (1.0/5) - (1.0/7) + (1.0/9) - (1.0/11) + (1.0/13));
		
		    System.out.println(pi);
		    System.out.println(pi2);
	
      		}
	  }
