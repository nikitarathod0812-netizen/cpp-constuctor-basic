# cpp-constuctor-basic
basic cpp program to understand contructors


#include<iostream>
using namespace std ;
class student {
	public :
	string name ;
	int rno ;
	float gpa ;
	
	student (string s , int r , float g){//parameters.
	
	name = s ;//constructor
	rno = r ;
	gpa = g ;
	
	}
	
};

int main (){
	student s1("nisha" , 10 , 9.08);
	student s2("nikita" , 11 , 9.09);
	
	cout<<s1.name<<" "<<s1.gpa<<" "<<s1.rno<<endl ;
	
	cout<<s2.name<<" "<<s2.gpa<<" "<<s2.rno<<endl ;
	
}
	
	
	
	