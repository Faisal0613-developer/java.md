## While Loop

#### The while loop loops through a block of code as long as a specified condition is true:

````java

public class Main {
  public static void main(String[] args) {
      int i = 0;
      
      while(i < 10)
      {
          System.out.println(i);
          i++;
      }
  }
}

````

### Do/While Loop

```java

public class Main {
  public static void main(String[] args) {
      int i = 10;
      
      do 
      {
          System.out.println(i);
          i--;
      }
      while(i > 0);
  }
}


```

### For Loop

```java

public class Main {
  public static void main(String[] args) {
      for(int i = 0; i<10; i++)
      {
          System.out.println(i);
      }
  }
}


```

### Each Loop

```java

public class Main {
  public static void main(String[] args) {
      String[] days = {"Mondau" , "Tuesday" , "Wednesday" , "Thursday" , "Friday" , "Saturday" , "Sunday"};
      
      for(String i : days)
      {
          System.out.println(i);
      }
  }
}


```
