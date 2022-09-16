# aaa
## kata task1  
[Task link](https://www.codewars.com/kata/5168bb5dfe9a00b126000018/)    
My solution

    public class aaa {

      public static String solution(String str) {
        StringBuilder sb = new StringBuilder(str);
        sb.reverse();
        return sb.toString();
      }

    }
My fav solution

      public class aaa {

      public static String solution(String str) {
        return new StringBuilder(str).reverse().toString();
      }

    }
## kata task2    
[Task link](https://www.codewars.com/kata/5aff237c578a14752d0035ae/)

My solution

      public class Solution {
        public static int predictAge(int age1, int age2, int age3, int age4, int age5, int age6, int age7, int age8) {
          int s = age1 * age1 + age2 * age2 + age3 * age3 + age4 * age4 + age5 * age5 + age6 * age 6 + age7 *age7 + age8 * age8;
        return ((int) (Math.sqrt(s)/2.0));
      }
    }
My fav solution

    import static java.util.stream.IntStream.of;

    public class Solution {
  
      public static int predictAge(int ... ages) {
      return (int) Math.sqrt(of(ages).map(a->a*a).sum())/2;
      }
  
    }
