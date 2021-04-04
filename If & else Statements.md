## Conditions and If Statements

### if Statement:

```java
public class Main {
  public static void main(String[] args) {
      int x = 25, y = 20;
      if(x>y)
      {
          System.out.println("x is grater then y");
      }
  }
}

```

### if else Statement:

```java
public class Main {
  public static void main(String[] args) {
      int time = 20;
      if(time > 25)
      {
          System.out.print("Good Day!!!");
      }
      else
      {
          System.out.print("Good Night!!!");
      }
  }
}

```


### else if statement:

```java
public class Main {
  public static void main(String[] args) {
      int time = 18;
      if(time < 10)
      {
          System.out.print("Good Morning!!!");
      }
      else if(time < 20)
      {
          System.out.print("Good Day!!!");
      }
      else
      {
          System.out.print("Good Night!!!");
      }
  }
}

```

### Short Hand If...Else (Ternary Operator)

```java
public class Main {
  public static void main(String[] args) {
      int time = 20;
      
      String result = (time < 22) ? "Good Day!!!" : "Good Night!!!";
      
      System.out.println(result);
  }
}

```
