# Lab-2

// Author Konrad 
// Description: Hello World in C++
//============================================================


#include <iostream>
using namespace std;
int hello1Function(string name1);
int hello2Function(string name2);
int main()
{
	string name1="Konrad";
	hello1Function(name1);
	string name2="Austin";
	hello2Function(name2);
	return 0;
}
  
/*
 * hello1Function.cpp
 *
 */
#include <iostream>
using namespace std;
int hello1Function(string name1)
{
	cout << "hello World " << name1 << endl;
	return 0;
}

