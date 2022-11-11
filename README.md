###  [Task 8kyu](https://www.codewars.com/kata/544675c6f971f7399a000e79/train/java)

We need a function that can transform a string into a number. 



### My solution
```Java
public class StringToNumber {
    public static int stringToNumber(String str) {
        int number = Integer.parseInt(str);
        return number;
    }
}
```

### Fav solution
```Java
public class StringToNumber {
    public static int stringToNumber(String str) {
        return Integer.valueOf(str);
    }
}

```
I like this solution because I like it
