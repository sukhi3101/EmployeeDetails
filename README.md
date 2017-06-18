# EmployeeDetails
1st assignment


package MyPackage;

public class EmployeeDetails {


	 private String empName;
	 private int empId;
	 private double empSal;
	 EmployeeDetails employees[] = new EmployeeDetails[100];
		 
		 public EmployeeDetails(String empName,int empId,double empSal){
	         this.empName=empName;
	         this.empId=empId; 
	         this.empSal=empSal;
	      }
		 
		 public String getEmpName(){
			 return empName;
		 }
		
		 public int getEmpId(){
		     return empId;
		 }
		 
		  public double getSalary(){
		     return empSal;
		  }
}

package MyPackage;

import java.util.ArrayList;


public class MyClas {
	public static void main(String[] args) {
		
		ArrayList<EmployeeDetails> emp=new ArrayList<EmployeeDetails>(); 	
		for (int i = 0; i <= 100; i++) {
			String name="emp" + i;
			int id= i;
			double sal = i+100;
			EmployeeDetails employees = new EmployeeDetails(name,id,sal);
			emp.add(employees);
		}
		
		for (int i = 0; i < emp.size() ; i++) {
			EmployeeDetails employees = (EmployeeDetails) emp.get(i);
			System.out.println("Employee " + i +  " name is " + employees.getEmpId());
			System.out.println("Employee " + i +  " id is " + employees.getEmpName());
			System.out.println("Employee " + i +  " sal is " + employees.getSalary());
		    } 
		
	
	
	}
  
  output-:
  
Employee0 name is =emp0
Employee0 id is =0
Employee0 sal is =100.0
Employee1 name is =emp1
Employee1 id is =1
Employee1 sal is =101.0
Employee2 name is =emp2
Employee2 id is =2
Employee2 sal is =102.0
Employee3 name is =emp3
Employee3 id is =3
Employee3 sal is =103.0
Employee4 name is =emp4
Employee4 id is =4
Employee4 sal is =104.0
Employee5 name is =emp5
Employee5 id is =5
Employee5 sal is =105.0
Employee6 name is =emp6
Employee6 id is =6
Employee6 sal is =106.0
Employee7 name is =emp7
Employee7 id is =7
Employee7 sal is =107.0
Employee8 name is =emp8
Employee8 id is =8
Employee8 sal is =108.0
Employee9 name is =emp9
Employee9 id is =9
Employee9 sal is =109.0
Employee10 name is =emp10
Employee10 id is =10
Employee10 sal is =110.0
Employee11 name is =emp11
Employee11 id is =11
Employee11 sal is =111.0
Employee12 name is =emp12
Employee12 id is =12
Employee12 sal is =112.0
Employee13 name is =emp13
Employee13 id is =13
Employee13 sal is =113.0
Employee14 name is =emp14
Employee14 id is =14
Employee14 sal is =114.0
Employee15 name is =emp15
Employee15 id is =15
Employee15 sal is =115.0
Employee16 name is =emp16
Employee16 id is =16
Employee16 sal is =116.0
Employee17 name is =emp17
Employee17 id is =17
Employee17 sal is =117.0
Employee18 name is =emp18
Employee18 id is =18
Employee18 sal is =118.0
Employee19 name is =emp19
Employee19 id is =19
Employee19 sal is =119.0
Employee20 name is =emp20
Employee20 id is =20
Employee20 sal is =120.0
Employee21 name is =emp21
Employee21 id is =21
Employee21 sal is =121.0
Employee22 name is =emp22
Employee22 id is =22
Employee22 sal is =122.0
Employee23 name is =emp23
Employee23 id is =23
Employee23 sal is =123.0
Employee24 name is =emp24
Employee24 id is =24
Employee24 sal is =124.0
Employee25 name is =emp25
Employee25 id is =25
Employee25 sal is =125.0
Employee26 name is =emp26
Employee26 id is =26
Employee26 sal is =126.0
Employee27 name is =emp27
Employee27 id is =27
Employee27 sal is =127.0
Employee28 name is =emp28
Employee28 id is =28
Employee28 sal is =128.0
Employee29 name is =emp29
Employee29 id is =29
Employee29 sal is =129.0
Employee30 name is =emp30
Employee30 id is =30
Employee30 sal is =130.0
Employee31 name is =emp31
Employee31 id is =31
Employee31 sal is =131.0
Employee32 name is =emp32
Employee32 id is =32
Employee32 sal is =132.0
Employee33 name is =emp33
Employee33 id is =33
Employee33 sal is =133.0
Employee34 name is =emp34
Employee34 id is =34
Employee34 sal is =134.0
Employee35 name is =emp35
Employee35 id is =35
Employee35 sal is =135.0
Employee36 name is =emp36
Employee36 id is =36
Employee36 sal is =136.0
Employee37 name is =emp37
Employee37 id is =37
Employee37 sal is =137.0
Employee38 name is =emp38
Employee38 id is =38
Employee38 sal is =138.0
Employee39 name is =emp39
Employee39 id is =39
Employee39 sal is =139.0
Employee40 name is =emp40
Employee40 id is =40
Employee40 sal is =140.0
Employee41 name is =emp41
Employee41 id is =41
Employee41 sal is =141.0
Employee42 name is =emp42
Employee42 id is =42
Employee42 sal is =142.0
Employee43 name is =emp43
Employee43 id is =43
Employee43 sal is =143.0
Employee44 name is =emp44
Employee44 id is =44
Employee44 sal is =144.0
Employee45 name is =emp45
Employee45 id is =45
Employee45 sal is =145.0
Employee46 name is =emp46
Employee46 id is =46
Employee46 sal is =146.0
Employee47 name is =emp47
Employee47 id is =47
Employee47 sal is =147.0
Employee48 name is =emp48
Employee48 id is =48
Employee48 sal is =148.0
Employee49 name is =emp49
Employee49 id is =49
Employee49 sal is =149.0
Employee50 name is =emp50
Employee50 id is =50
Employee50 sal is =150.0
Employee51 name is =emp51
Employee51 id is =51
Employee51 sal is =151.0
Employee52 name is =emp52
Employee52 id is =52
Employee52 sal is =152.0
Employee53 name is =emp53
Employee53 id is =53
Employee53 sal is =153.0
Employee54 name is =emp54
Employee54 id is =54
Employee54 sal is =154.0
Employee55 name is =emp55
Employee55 id is =55
Employee55 sal is =155.0
Employee56 name is =emp56
Employee56 id is =56
Employee56 sal is =156.0
Employee57 name is =emp57
Employee57 id is =57
Employee57 sal is =157.0
Employee58 name is =emp58
Employee58 id is =58
Employee58 sal is =158.0
Employee59 name is =emp59
Employee59 id is =59
Employee59 sal is =159.0
Employee60 name is =emp60
Employee60 id is =60
Employee60 sal is =160.0
Employee61 name is =emp61
Employee61 id is =61
Employee61 sal is =161.0
Employee62 name is =emp62
Employee62 id is =62
Employee62 sal is =162.0
Employee63 name is =emp63
Employee63 id is =63
Employee63 sal is =163.0
Employee64 name is =emp64
Employee64 id is =64
Employee64 sal is =164.0
Employee65 name is =emp65
Employee65 id is =65
Employee65 sal is =165.0
Employee66 name is =emp66
Employee66 id is =66
Employee66 sal is =166.0
Employee67 name is =emp67
Employee67 id is =67
Employee67 sal is =167.0
Employee68 name is =emp68
Employee68 id is =68
Employee68 sal is =168.0
Employee69 name is =emp69
Employee69 id is =69
Employee69 sal is =169.0
Employee70 name is =emp70
Employee70 id is =70
Employee70 sal is =170.0
Employee71 name is =emp71
Employee71 id is =71
Employee71 sal is =171.0
Employee72 name is =emp72
Employee72 id is =72
Employee72 sal is =172.0
Employee73 name is =emp73
Employee73 id is =73
Employee73 sal is =173.0
Employee74 name is =emp74
Employee74 id is =74
Employee74 sal is =174.0
Employee75 name is =emp75
Employee75 id is =75
Employee75 sal is =175.0
Employee76 name is =emp76
Employee76 id is =76
Employee76 sal is =176.0
Employee77 name is =emp77
Employee77 id is =77
Employee77 sal is =177.0
Employee78 name is =emp78
Employee78 id is =78
Employee78 sal is =178.0
Employee79 name is =emp79
Employee79 id is =79
Employee79 sal is =179.0
Employee80 name is =emp80
Employee80 id is =80
Employee80 sal is =180.0
Employee81 name is =emp81
Employee81 id is =81
Employee81 sal is =181.0
Employee82 name is =emp82
Employee82 id is =82
Employee82 sal is =182.0
Employee83 name is =emp83
Employee83 id is =83
Employee83 sal is =183.0
Employee84 name is =emp84
Employee84 id is =84
Employee84 sal is =184.0
Employee85 name is =emp85
Employee85 id is =85
Employee85 sal is =185.0
Employee86 name is =emp86
Employee86 id is =86
Employee86 sal is =186.0
Employee87 name is =emp87
Employee87 id is =87
Employee87 sal is =187.0
Employee88 name is =emp88
Employee88 id is =88
Employee88 sal is =188.0
Employee89 name is =emp89
Employee89 id is =89
Employee89 sal is =189.0
Employee90 name is =emp90
Employee90 id is =90
Employee90 sal is =190.0
Employee91 name is =emp91
Employee91 id is =91
Employee91 sal is =191.0
Employee92 name is =emp92
Employee92 id is =92
Employee92 sal is =192.0
Employee93 name is =emp93
Employee93 id is =93
Employee93 sal is =193.0
Employee94 name is =emp94
Employee94 id is =94
Employee94 sal is =194.0
Employee95 name is =emp95
Employee95 id is =95
Employee95 sal is =195.0
Employee96 name is =emp96
Employee96 id is =96
Employee96 sal is =196.0
Employee97 name is =emp97
Employee97 id is =97
Employee97 sal is =197.0
Employee98 name is =emp98
Employee98 id is =98
Employee98 sal is =198.0
Employee99 name is =emp99
Employee99 id is =99
Employee99 sal is =199.0
Employee100 name is =emp100
Employee100 id is =100
Employee100 sal is =200.0
