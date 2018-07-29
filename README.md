# Addition1
Sum of two numbers
class Sum1
{
 int a,b,total;
void add()
{
 total=a+b;
 System.out.println("Sum is:"+total);
} 

public static void main(String args[])
{
  Sum1 obj=new Sum1();
 obj.a=10;
  obj.b=20;
  obj.add();
} 
}
