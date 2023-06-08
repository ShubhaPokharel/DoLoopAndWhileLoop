# DoLoopAndWhileLoop

# While Loop

While loop is also a looping statement like for loop and for each loop.It is condition based looping statement. While loop takes conditions only. 

It is different from other loops, for example for loop takes 3 arguments(initialization, condition, increment or decrement). For each loop does not 
have condition. 

In total, for loop has 3 parts and while loop has only one part which is condition.


## Example:
import java.util.Scanner;

class Test {

  public static void main(String[] args){
  
    Scanner s = new Scanner();
    
    
    while(true){
    
      System.out.println("Enter your number");
      
      int num = s.nextInt();
      
      
      if(num > 0){
      
        System.out.println("Your number is positive");
        
      }
      
      else if(num < 0){
      
        System.out.println("Your number is negative");
        
      }
      
      else{
      
      System.out.println("Your number is 0);
      
      }
      
    }
    

  }
  

}

When we have the starting point, ending point and increment / decrement , we use for loop. When we have only condition check then use while loop. If we know the number of iteration and if you want to pick a specific range of data, we use for loop. If it is a condition, we can use while loop.


