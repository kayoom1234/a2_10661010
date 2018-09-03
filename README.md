# a2_10661010
grading system
#include <iostream>
using namespace std;
/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(int argc, char** argv) {
	double score;
	string str;
	
 cout<<"Enter student name: ";
 cin>>str;
 cout<<endl;
 cout<<"Enter student score: ";
 cin>>score;
 if(score>=80 && score<=100){
		cout<<str<<" with "<<score<<" had an A";
	 }
 else if(score>=65 && score<=79){
		cout<<str<<" with "<<score<<" had an B";
	}
		else if(score>=55 && score<=64){
		cout<<str<<" with "<<score<<" had an C";
	}
		else if(score>=40 && score<=54){
		cout<<str<<" with "<<score<<" had an D";
	}
		else if(score>=25 && score<=35){
		cout<<str<<" with "<<score<<" had an E";
	}
		else if(score>=0 && score<=24) {
		cout<<str<<" with "<<score<<" has an F";
	}
	else{
		cout<<"Enter number in range of percentage";
		
	}
	 
	return 0;
}
