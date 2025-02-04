# bien55
bien55
class variablestypes{
//declare an instance variable
int b=10;
//declare a static variable
static int c=20;

public void localuse()
{
//declare a local variable
int a=30;
System.out.println("value from local variable is: "+ a);
System.out.println("value from instance variable is: "+ b);
System.out.println("value from static variable is: "+ c);
}
public static void main(String[] args){
// creating an object
variablestypes md= new variablestypes();
//call the method
md.localuse();

}
}