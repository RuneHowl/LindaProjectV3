#include <iostream>

using namespace std;

int main() {
  
    // Write your main here  
  double cost_merchandise;    
double salary_employees;   
double rent_yearly;   
double cost_electricity;   

double profit = 0.1;   
double sale = 0.15;   

double total_expenses = 0;   
double markup_price, mark_percentage = 0;    

cout << "Enter the cost of merchandise";   
cin >> cost_merchandise;

cout <<"Enter the salary of the employees (include yourself):";    
cin >> salary_employees;   

cout <<"Enter the yeary rent:";    
cin >> rent_yearly;  

cout <<"Enter the cost of electricity";   
cin >> cost_electricity;   

total_expenses = cost_merchandise + salary_employees + rent_yearly + cost_electricity;   

markup_price = (profit*cost_merchandise + total_expenses)/0.85;   

mark_percentage = (markup_price*100)/ cost_merchandise;   


cout << " Mark_percentage: ";  
 cout << mark_percentage << endl;   

    return 0;   
}   
