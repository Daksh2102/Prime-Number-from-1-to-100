# Prime-Number-from-1-to-100
class Prime_Series
{  
	public static void main(String args[])  
	{    
	int c=1; 
	System.out.println("Prime Numbers Series");
	  for (int j = 1; j <= 100; j++)         
    { 		  	  
      int counter=0; 	  
		  for(int num =j; num>=1; num--)
		  {
			  if(j%num==0)
			  {
				  counter = counter + 1;
			  }
		  }
		  if (counter ==2)
		  {
			  System.out.print(j + " ");c++;
		  }
		  if(c>15)
		  {
		  break;
		  }
	  }
 }
