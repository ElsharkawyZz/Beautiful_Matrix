Beautiful_Matrix

using System;
					
public class Program
{
	public static void Main()
	{
		int[,]matrix=new int[5,5];
		
		int count=0;
		for(int i=0;i<5;i++)
		{
		  for(int j=0;j<5;j++)
		 {
		     matrix[i,j]=int.Parse(Console.ReadLine());
		  
			  if(matrix[i,j]==1)
			  {
			    count+=Math.Abs(i-2)+Math.Abs(j-2);
				  break;
			  }
		 
		  }
		}
		Console.WriteLine(count);
	}
}
