# Basic-I-O-syntax
Just Keeping the basic I/O syntax 

# Using Scanner in Java
1. String[] arrRowItems = scanner.nextLine().split(",");


# take care of this while using Scanner:-
# if you are taking string input, just next after the integer input, use a blank sc.nextLine();
Example: 

<stroke><1st Method></stroke><br>
Scanner scanner = new Scanner(System.in);<br>
int T = scanner.nextInt();<br>
scanner.nextLine();<br>
String string = scanner.nextLine();<br>
 <br>
<stroke><2nd Method></stroke><br>
Scanner scanner = new Scanner(System.in);<br>
int T = scanner.nextInt();<br>
scanner.skip("(\r\n|[\n\r\u2028\u2029\u0085])?");<br>


