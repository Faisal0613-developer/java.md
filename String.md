## Java String Examples

```java

public class Main {
  public static void main(String[] args) {
    String programmerName = "Faisal Iqbal";
    String programmerId = "19JZBCS0092";
    String programmerAddress = "Jalozi Peshawar";
    
    //String Concatenation
    System.out.println("\nProgrammer Name is :"+programmerName + "\nProgrammer ID : "+programmerId + "\nProgrammer Address :"+programmerAddress);
    
    //In this Program we use length()  to print String length
    System.out.println("*** length()  Function *** ");
    System.out.println("Name String Length :"+programmerName.length());
    System.out.println("ID String Length : "+programmerId.length());
    System.out.println("Address String Length :"+programmerAddress.length());
    
    //In this Program we Use toUpperCase() to print String in Upper case Alphabet 
     System.out.println("\n*** toUpperCase() Function ***");
    System.out.println("\nProgrammer Name in Upper Case : "+programmerName.toUpperCase());
    System.out.println("Programmer ID in Upper Case : "+programmerId.toUpperCase());
    System.out.println("Programmer Address in Upper Case : "+programmerAddress.toUpperCase());
    
    //In this program we use toLowerCase() to print String in Lower Case Alphabet
    System.out.println("\n*** toLowerCase() Function ***");
    System.out.println("\nProgrammer Name in Lower Case : "+programmerName.toLowerCase());
    System.out.println("Programmer ID in Lower case : "+programmerId.toLowerCase());
    System.out.println("Programmer Address in Lower Case : "+programmerAddress.toLowerCase());
    
    //In this program we Finding a Character in a String use indexOf()
    System.out.println("\n*** indexOf() ***");
    System.out.println("In given Programmer Name the 'l' character location is : "+programmerName.indexOf("l"));
    System.out.println("In given Programmer ID the '9' character location is : "+programmerId.indexOf("9"));
    System.out.println("In given Programmer Address the 'w' character location is : "+programmerAddress.indexOf("w"));
    
    //In this Program we use concat() for print morethen two String
    System.out.println("\n*** concat() ***");
    System.out.print("Programmer Nmae is : "+programmerName.concat("\tProgrammer ID is : "+programmerId.concat("\tProgrammer Address is : "+programmerAddress)));
  }
}


```
