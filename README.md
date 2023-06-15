# The Currency Converter Project in Java is the knowledge of the real value of one currencyto be converted into another country’s currency so that you can convert between the two currencies. The Currency Converter Project in Java Source Code was created in Java Programming language using  NetBeans IDE.
# A cash converter is programming code that is intended to change one money into another all together over to check its relating esteem. The code is commonly a piece of a site or it frames a portable application and it depends on current market or bank trade rates. To change over one cash into another, a client enters a measure of cash (for example '1000') and picks the cash he/she wishes to check the money related estimation of (for example 'US Dollar'). From that point forward, the client choose one, or some of the time a few different monetary forms, he/she might want to see the outcome in. The application programming at that point computes and shows the comparing measure of cash. Money converters expect to keep up continuous data on current market or bank trade rates, so the determined outcome changes at whatever point the estimation of both of the segment monetary standards does. They do as such by interfacing with an information base of current cash trade rates. The recurrence at which cash converters update the trade rates they use differs: Yahoo cash converter refreshes its.
# MINIPROJECT
//java program to implement the currency convertor
import java.util.*; 
import java.text.DecimalFormat; 
public class CurrencyConverter 
{ 
public static void main(String[] args) 
{ 
double rupee,dollar,pound,code,euro,yen; 
DecimalFormat f = new DecimalFormat("##.###"); 
Scanner sc = new Scanner(System.in); 
System.out.println("Enter the currency code 1:Rupees\n2:Dollar\n3:Pound\n4:Euro\n5:Yen"); code=sc.nextInt(); 
//For Rupees Conversion 
if(code == 1) 
{ 
System.out.println("Enter amount in rupees"); 
rupee = sc.nextFloat(); 
dollar = rupee / 66; 
System.out.println("Dollar : "+f.format(dollar)); 
pound = rupee / 98; 
System.out.println("Pound : "+f.format(pound)); 
euro = rupee / 72; 
System.out.println("Euro : "+f.format(euro)); 
yen = rupee / 0.55; 
System.out.println("Yen : "+f.format(yen)); 
} 
//For Dollar Conversion 
else if (code == 2) 
{ 
System.out.println("Enter amount in dollar"); 
dollar = sc.nextFloat(); 
rupee = dollar * 66; 
System.out.println("Rupees : "+f.format(rupee)); 
pound = dollar * 0.67; 
System.out.println("Pound : "+f.format(pound)); 
euro = dollar * 0.92; 
System.out.println("Euro : "+f.format(euro)); 
yen = dollar * 120.90;
System.out.println("Yen : "+f.format(yen));
 } 
//For Pound Conversion 
else if(code == 3) 
{ 
System.out.println("Enter amount in Pound"); pound = sc.nextFloat(); 
rupee = pound * 98; 
System.out.println("Rupees : "+f.format(rupee)); dollar = pound * 1.49; 
System.out.println("Dollar : "+f.format(dollar)); 
euro = pound * 1.36; 
System.out.println("Euro : "+f.format(euro)); 
yen = pound * 179.89; 
System.out.println("Yen : "+f.format(yen)); 
} 
//For Euro Conversion 
else if(code == 4) 
{ 
System.out.println("Enter amount in Euro"); 
euro = sc.nextFloat(); 
rupee = euro * 72; 
System.out.println("Rupees : "+f.format(rupee)); dollar = euro * 1.09; 
System.out.println("Dollar : "+f.format(dollar)); pound = euro * 0.73; 
System.out.println("Pound : "+f.format(pound));
yen = euro * 131.84; 
System.out.println("Yen"+f.format(yen)); 
} 
//For Yen Conversion 
else if(code == 5) 
{ 
System.out.println("Enter amount in Yen"); 
yen = sc.nextFloat(); 
rupee = yen * 0.55; 
System.out.println("Rupees : "+f.format(rupee)); dollar = yen * 0.01; 
System.out.println("Dollar : "+f.format(dollar)); pound = yen * 0.01; 
System.out.println("Pound : "+f.format(pound));
euro = yen * 0.01; 
System.out.println("Euro : "+f.format(euro));
 } 
else 
System.out.println("Invalid Code");
 } 
} 

