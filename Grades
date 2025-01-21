import java.util.ArrayList;
import java.util.Scanner;

public class StudentGradeSystem {

	public static void main(String[] args) {
		Scanner scan=new Scanner(System.in);
		ArrayList<Double> grades=new ArrayList<Double>();
		System.out.print("Enter the student grades Note:if you want to enter type {yes}or else no");
		String s=scan.next();
	   if(s.equalsIgnoreCase("yes"))
	   {
		   System.out.println("please enter the data");
		while(scan.hasNextDouble()||scan.hasNextInt())
		{
			double b=scan.nextDouble();
			grades.add(b);
			System.out.println("Student Grade entered succesfully");			
		}
	   }
		double total=0;
		double max_Double=Double.MIN_VALUE;
		double min_Double=Double.MAX_VALUE;
		for(int i=0;i<grades.size();i++)
		{
			total=total+grades.get(i);
			if(max_Double<grades.get(i))
			{
				max_Double=grades.get(i);
			}
			if(min_Double>grades.get(i))
			{
				min_Double=grades.get(i);
			}
			
		}
		Double average=total/grades.size();
		System.out.println("Student Average Grades:"+average);
		System.out.println("Studens MAX Grade:"+max_Double);
		System.out.println("Students MIN value:"+min_Double);
		scan.close();

	}

}
