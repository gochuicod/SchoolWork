Final - Programming Exercise2 

Sanchez Construction Loan Co. makes loans of up to $100,000 for construction projects. There are 
two categories of Loan - those to businesses and those to individuals applicants 

Write an application that tracks all new construction loans. The application must also calculate 
the total amount owed at the due date (original loan amount + loan fee). The application should 
include the following classes: 

Loan - A public abstract class that implements the LoanConstants interface. A Loan includes a loan 
number, customer last  name, amount of loan, interest rate, and term. The constructor requires 
data for each of the fields except interest rate. Do not allow loan amounts over $100,000. Force 
any loan term that is not one of the three defined in the LoanConstants class to a short-term, 
1-year loan. Create a toString() method that displays all the loan data. 

LoanConstants - A public interface class. LoanConstants includes constant values for short-term 
(1 year), medium-term (3 years), and long-term (5 years) loans. It also contains constants for 
the company name and the maximum loan amount. 

BusinessLoan - A public class that extends Loan. The BusinessLoan constructor sets the interest 
rate to 1 percent over the current prime interest rate. 

PersonalLoan - A public class that extends Loan. The PersonalLoan constructor sets the interest 
rate to 2 percent over the current prime interest rate. 

CreateLoans - An application that creates an array of five loans. Prompt the user for the 
currrent prime interest rate. Then, in  a loop, prompt the user for a loan type and all relevant 
information for that loan. Store the created Loan objects in the array. When data entry is 
complete, display all the loans. 

Save the files as Loan.java, LoanConstants.java, BusinessLoan.java, 
PersonalLoan.java, and CreateLoans.java  
