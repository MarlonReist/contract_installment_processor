A simple Java console application to process contracts and generate monthly installment plans with interest and payment fees.

Features
Read contract details (number, date, total value)
Read number of installments
Generate installments starting one month after the contract date
Apply simple monthly interest (1%) + fixed payment fee (2%) per installment
Display each installment's due date and amount
Example
Enter contract data Number: 8028 Date (dd/MM/yyyy): 25/06/2018 Contract value: 600.00 Enter number of installments: 3 Installments: 25/07/2018 - 206.04 25/08/2018 - 208.08 25/09/2018 - 210.12

Technologies & Concepts

Java Interfaces & Polymorphism
Service layer design
LocalDate for date calculations
Simple interest & fee calculations
Dependency injection via constructor
