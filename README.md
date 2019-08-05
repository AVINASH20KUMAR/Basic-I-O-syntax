# Basic-I-O-syntax
Just Keeping the basic I/O syntax 

# Using Scanner in Java
1. String[] arrRowItems = scanner.nextLine().split(",");


# take care of this while using Scanner:-
# if you are taking string input, just next after the integer input, use a blank sc.nextLine();
Example: 

<stroke><1st Method></stroke>
Scanner scanner = new Scanner(System.in);
int T = scanner.nextInt();
scanner.nextLine();
String string = scanner.nextLine();
 
<stroke><2nd Method></stroke>
Scanner scanner = new Scanner(System.in);
int T = scanner.nextInt();
scanner.skip("(\r\n|[\n\r\u2028\u2029\u0085])?");


