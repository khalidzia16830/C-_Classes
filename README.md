# C-_Classes
This code will help you to understand how classes works in Cpp, moreover classes contains Objects functions, Classes may be public, Private or Protected
# include <iostream>
using namespace std;
class Students{
 public:
 void StudentNames()
 {
    cout << "1. Ume-Habiba\n"
         << "2. Ume-Rubab\n"
         << "3. Ume-Aiman\n";
 }
void StudentMarks()
{
    cout << "Ume-Habiba gets 447 Marks\n"
         << "Ume-Rubab gets 443 Marks\n"
         << "Ume-Aiman gets 420 Marks\n";
    
}
void StudentGrades()
{
    cout << "A\n"
         << "B\n"
         << "C\n";
}
    };
    
    
    
    int main()
{
    Students StNames;
    StNames.StudentNames();
    cout << "There Marks\n";
   StNames.StudentMarks();
   cout << "There Grades\n";
   StNames.StudentGrades();
}
