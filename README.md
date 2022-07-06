# Project Name
> Lending Club Case Study : EDA Analysis


## Table of Contents
* General Information
* Conclusions
* Technologies Used
### General Information
- Problem Statment : Minimize the risk of losing money while lending to customers


-Business Understanding 
	Consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associatedwith the bank’s decision.If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company if the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
	
		1.	When a person applies for a loan, there are two types of decisions that could be taken by the company:
		2.	Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
			a.	Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
			b.	Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
			c.	Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
		3.	Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)



- Minimize the risk of losing money while lending to customers
- Loan Dataset is being used


### Conclusions
- Good to avoid the applicant whose annual income is more with high mortgage value
- Avoid B,C &D Grade applicants
- Avoid A5 ,B3,B4,B5 & D2 Subgrade applicants
- Avoid the applicants from CA state
- Avoid purpose of the loan is either Small business, debt consolidation 


### Technologies Used
- Python 3.2
- library - pandas
- library - numpy
- library - matplotlib.pyplot
- library - seaborn
- library - warnings

# Analysis done by Roshni S & R Sivaramakrishna
The following file are added to the GIT

1. Data_Dictionary.xlsx
2. loan.csv
3. Roshni Siddoju.pdf
4. Roshni_Siddoju.ipynb


