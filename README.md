# StructExc7
Informatics Coursebook, Structure, p143

#include<iostream>
using namespace std;
struct People
{
  char first_name[20];
  char last_name[20];
  char egn[20];
};
int main()
{
	People people[100];
	int n;
	cout<<"Br people=";
	cin>>n;
	for(int i=0;i<n;i++)
	{
		cout<<"First name:";
		cin>>people[i].first_name;
		cout<<"Last name=";
		cin>>people[i].last_name;
		cout<<"EGN=";
		cin>>people[i].egn;
	}
	
    
	system("pause");
	return 0;
}
