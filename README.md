###  [Task 8kyu](https://www.codewars.com/kata/544675c6f971f7399a000e79/train/java)

In a small town the population is p0 = 1000 at the beginning of a year. The population regularly increases by 2 percent per year and moreover 50 new inhabitants per year come to live in the town. How many years does the town need to see its population greater or equal to p = 1200 inhabitants?



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
