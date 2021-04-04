
## Java Math
### The Java Math class has many methods that allows you to perform mathematical tasks on numbers.

```java
public class Main {
  public static void main(String[] args) {
      
      int x= 5, y=55, z=-10;
      
    //Find the Maximum Value
    System.out.println("In X and Y Max Number is : "+Math.max(x, y));
    
    //Find the Minimum Value
    System.out.println("In X and Y Min Number is : "+Math.min(x, y));
    
    //Find the Square Root
    System.out.println("Square root of X is : "+Math.sqrt(x)+"\nSquare root of Y is : "+Math.sqrt(y));
    
    //Absolute value
    System.out.println("absolute (positive) value of z : "+Math.abs(z));
    
    //Find the Reundom Number 0 1o 100.
    System.out.println("Random Number : "+Math.random()*101);
  }
}


```
