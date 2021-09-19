#include<iostream>
using namespace std;
class time
{
	public :
	int hour,min,sec;
	void read_input()
	{
      cout<<"Enter time\n";
      cout<<"Hours? ";
      cin>>hour;
      cout<<"Minutes? ";
        cin>>min;
      cout<<"Seconds? ";
        cin>>sec;
	}
	
};
class seconds : public time
{
	public :
		void display()
	{
		cout<<"\nThe time is = "<<hour<<":"<<min<<":"<<sec;
		cout<<"\nTime in total seconds: "<<(hour*3600)+(min*60)+sec;
	}
};
int main()
{
	seconds sec;
	sec.read_input();
	sec.display();
}
