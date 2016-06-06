//# pionters
# include <iostream>
# include <conio.h>
using namespace std;
int main()

{
	int a = 100; //value of a
	int *p1; // initilize pointer p1
	int **p2; //  initilize pointer p2
	p1 = &a;
	p2 = &p1;
	
	cout <<"Address of a (using  &a ) = "<< &a;
		cout << "\n" ;
		cout << "\n" ;
	cout <<"Address of a  or ptr value that is ardress of a  (using  p1 ) = "<< p1;
	    cout << "\n" ;
	    cout << "\n" ;
        cout << "\n" ;
    cout <<"Address of p1 (using  &p1 ) = "<< &p1;
        cout << "\n";
		cout << "\n"  ;
    cout <<"value  of a (using  *p1 ) = "<< *p1;
         cout << "\n" ;
		 cout << "\n" ;
	cout <<"value  of a (using  **p2 ) = "<< **p2;
        cout << "\n" ;
    	cout << "\n" ;
	    cout << "\n" ;
    cout <<"value  of p2 which is & of p1 (using  *p2 ) = "<< *p2;
        cout << "\n";
    	cout << "\n" ;
	    cout << "\n" ;
	cout <<"value  of a (using  &p2 ) = "<< &p2;  
}
