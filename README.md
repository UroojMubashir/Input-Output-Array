
 #include <iostream>
 using namespace std;
 
  int main()
{
	int a[5];
	cout << "kindly enter any 5 integer values:"<<endl;
	for (int i = 0; i < 5; i++)
	{
		cin >> a[i];
		
	}
	
	cout<<"The Numbers are :"<<endl;
	for (int j = 0; j < 5; j++)

	{
		cout << a[j] <<endl;
	}
	return 0;
}
