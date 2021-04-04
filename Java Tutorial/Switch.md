## Switch Statements

### Use the switch statement to select one of many code blocks to be executed.

### break Keyword

#### When Java reaches a break keyword, it breaks out of the switch block.

```java
public class Main {
  public static void main(String[] args) {
      int day = 5;
      
      switch(day)
      {
            case 1 :
              System.out.print("Monday");
              break;
         
            case 2 :
              System.out.print("Tuesday");
              break;
            
            case 3 :
              System.out.print("wednesday");
              break;
         
            case 4 :
              System.out.print("thursday");
              break;
         
            case 5 :
              System.out.print("Friday");
              break;
         
            case 6 :
              System.out.print("Saturday");
              break;
         
            case 7 :
              System.out.print("Sunday");
              break;
      }
  }
}

```


### default Keyword

#### The default keyword specifies some code to run if there is no case match:

```java
public class Main {
  public static void main(String[] args) {
      int day = 7;
      
      switch(day)
      {
            case 1 :
              System.out.print("Monday");
              break;
         
            case 2 :
              System.out.print("Tuesday");
              break;
            
            case 3 :
              System.out.print("wednesday");
              break;
         
            case 4 :
              System.out.print("thursday");
              break;
         
            case 5 :
              System.out.print("Friday");
              break;
         
            case 6 :
              System.out.print("Saturday");
              break;
         
            default:
              System.out.print("Sunday");
              break;
      }
  }
}

```
