interface A
{
	public void display();
}
class B implements A
{
	public void display()
	{
		System.out.println("Hello im implemented");
	}
}
class Jala {
	public void show()
	{
		System.out.println("Im definition of abstact method");
	}
	public static void main(String[] args){ 
			 B b = new B();
			 b.display();
		
	}
}
