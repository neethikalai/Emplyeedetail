# Emplyeedetail
employee
class company
{
	String name;
	String position;
	String branch;
	String section;
	
	void manager(String name)
	{
		this.name=name;
	}
	
	void Assistant_manager(String name,String position)
	{
		this.name=name;
		this.position=position;
	}
	
	void Branch_manager(String name,String position,String branch)
	{
		this.name=name;
		this.position=position;
		this.branch=branch;
	}
	
	void General_manager(String name,String position,String branch,String section)
	{
		this.name=name;
		this.position=position;
		this.branch=branch;
		this.section=section;
	}
	
	void display()
	{
		System.out.println(" name is "+name);
		System.out.println(" position is "+position);
		System.out.println(" branch is "+branch);
		System.out.println(" section is "+section);
		
	}
}
	class employee_detail{
	public static void main(String[]args)
	{
		company c1=new company();
		c1.manager("MR.SHANMUGA");
		c1.display();
		System.out.println("-----------------");
		
		company c2=new company();
		c2.Assistant_manager("MR.SHANMUGA","assistent manager");
		c2.display();
		System.out.println("-----------------");
		
		company c3=new company();
		c3.Branch_manager("MR.SHANMUGA","Branch manager","IT");
		c3.display();
		System.out.println("-----------------");
		
		company c4=new company();
		c4.General_manager("MR.SHANMUGA","General manager","Econes","Deposit branch");
		c4.display();
		System.out.println("-----------------");
	}
}
		
		

		
