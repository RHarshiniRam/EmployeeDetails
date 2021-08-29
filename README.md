# EmployeeDetails
To print employee details
import java.util.*;
public class employeedetails
{
     String employeid,empname, empemail,empaddress;
     public void read()
     {
        Scanner sc= new Scanner(System.in);
        System.out.println("Enter the employee id");//taking all the inputs from the user
        employeid=sc.next();
        System.out.println("Enter the employee name");
        empname=sc.next();
        System.out.println("Enter the employee email ");
        empemail=sc.next();
        System.out.println("Enter the employee address")
        empaddress=sc.next();
     }
     public void display()  
     {
        System.out.println("Employee Id  :"+employeid+"n"+"Employee Name  : "+empname+"n"+"Employee email :"+empemail+"n"+"Employee Address:"+empaddress);
     }
}
class main
{
     public static void main(String args[])
     {
         employee employeobj=new employee();
         employeobj.read();
         employeobj.display(); 
     }
}
