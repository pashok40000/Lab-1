#include <iostream>
using namespace std;
class Employees
{
private:
string name;
double salary;
double up;

public :
void Info()
{
cout<<"Name"<<endl;
cin>>name;
cout<<"Salary"<<endl;
cin>>salary;
cout<<"Up"<<endl;
cin>>up;
};
void print()
{
double new_salary = salary*up + salary;
cout<<"Name: "<<name<<endl;
cout<<"Salary: "<<salary<<endl;
cout<<"Last salary: ";
cout<<new_salary<<endl<<endl;
};

};

int main(int argc, const char * argv[])
{
int n;
cout<<"enter number of employees:"<<endl;
cin>>n;
for (int i=0; i<n; i++)
{ Employees employee;
employee.Info();
employee.print();
};

return 0;
};


