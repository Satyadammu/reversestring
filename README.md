# reversestring
import java.util.*; 
class ReverseString
{  
public static void main(String args[])  
{ 
System.out.print("Enter a String: ");  
Scanner sc = new Scanner(System.in);
String str = sc.nextLine();
String s="";
String reverse[] = str.split(" ");
for(int i = reverse.length-1;i>=0;i--)
{
 s+=reverse[i]+" ";
}
System.out.print("after reverse:"+s);
}
}
