## Java String Examples

```java

public class Main {
  public static void main(String[] args) {
    String programmerName = "Faisal Iqbal";
    String programmerId = "19JZBCS0092";
    String programmerAddress = "Jalozi Peshawar";
    
    //this program count String length and print it
    System.out.println("*** String Length *** ");
    System.out.println("Name String Length :"+programmerName.length());
    System.out.println("ID String Length : "+programmerId.length());
    System.out.println("Address String Length :"+programmerAddress.length());
    
    //This Program Print all Output in Upper Case
     System.out.println("\n*** Upper Case ***");
    System.out.println("\nProgrammer Name in Upper Case : "+programmerName.toUpperCase());
    System.out.println("Programmer ID in Upper Case : "+programmerId.toUpperCase());
    System.out.println("Programmer Address in Upper Case : "+programmerAddress.toUpperCase());
    
    //This Program Print all Output in Lower Case
    System.out.println("\n***Lower Case ***");
    System.out.println("\nProgrammer Name in Lower Case : "+programmerName.toLowerCase());
    System.out.println("Programmer ID in Lower case : "+programmerId.toLowerCase());
    System.out.println("Programmer Address in Lower Case : "+programmerAddress.toLowerCase());
    
    
    System.out.println("\nProgrammer Name is :"+programmerName + "\nProgrammer ID : "+programmerId + "\nProgrammer Address :"+programmerAddress);
  }
}


```
