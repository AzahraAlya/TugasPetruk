# TugasPetrukku
This is deskription of excersice Petruk


#include <iostream>
using namespace std;

//pointer fungsi RataRata
void RataRata(float *sum , int *a){
	
	cout << "\n Rata-rata : " << *sum / *a;
	
}
 
int main () {

cout<<"  ================================================"<<endl;

cout<<"   Program Menghitung Rata-Rata Edisi Lengkap "<<endl;

cout<<"  ================================================"<<endl;
cout<<endl;

int a = 0; //banyaknya element data
int i; //untuk iterasi for
float sum = 0, max = 0, min = 0; 

//minta user input banyaknya data
cout << "Banyaknya bilangan yang akan diinput :";
cin >> a;//*

