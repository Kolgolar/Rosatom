Задание 1:

SELECT surname
FROM employees
ORDER BY experience DESC
OFFSET 1 ROW
FETCH NEXT 1 ROW ONLY;


Задание 2:

private static void swapValues(int a, int b) {
    System.out.println("Original: a = " + a + ", b = " + b);
    
    a = a ^ b;
    b = a ^ b;
    a = a ^ b;
    
    System.out.println("Swapped: a = " + a + ", b = " + b);
}


Задание 3.2:

private static void isPalindrome(String str) {
   str = str.toLowerCase();
   int i = 0;
   int j = str.length() - 1;
   while (i < j) {
       if (str.charAt(i) != str.charAt(j)) {
           System.out.println("The string is not a pallindrome");
       }
       i++;
       j--;
   }
   System.out.println("The string is a pallindrome");
}