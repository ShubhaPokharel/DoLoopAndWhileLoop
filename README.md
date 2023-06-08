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


For loop and While loop are called entry controlled loops. It means they check the condition first and then they execute the logics. Do While is called exit controlled loop. Exit controlled loop means first it enters into body although the condition is false. In Do - While, it does not check the condition first, body is executed first. In other words, first body is executed, which is inside do block and then it checks the condition.

Minimum occurance is 0 in entry controlled loop(for and while loop). 

# Do While

Do While is also a looping statemnt where the body gets executed first before checking the condition. It is exit controlled looping statement. It means the body gets executed first, checks the condition secondly.So, the body will be executed even though condition is false. WHen the condition is false, the body will be executed only once.

Minimum occurance is 1 in exit controlled loop(Do - While loop).

## Example:

class Test{

public static void main(String[] args){

    do{
    
      System.out.println("Good Night");  //1
      
    }
    
    while(10 > 20); // 2

  }

}


