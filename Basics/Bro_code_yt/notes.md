### Program to swap 2 variables
```java

public class Main{

    public static void main(String[] args) {

        // intializing the variables
        int x = 3;
        int y = 9;
        int temp;
        // swapping the variables
        temp = x;
        x=y;
        y=temp;
        // printing the variables
        System.out.println("Value of x: " + x);
        System.out.println("Value of y: " + y);
    }
}

```