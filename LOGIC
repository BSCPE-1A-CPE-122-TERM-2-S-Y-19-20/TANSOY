#include<iostream>
#include<string>

using namespace std;

	void conjunction(){
		
		string q,p;
		
		cout << "\n 	Conjunction. The conjunction p ^ q are true if and only if p and q are both true";
		cout<< "\n 	Enter the value of p	";
		cin>>p;
		cout<<"	Enter the value of q	";
		cin>>q;
		
		if( q == "true" && p =="true" )
		 {
			cout<<"\n p ^ q = true";
		}
		
		else cout<< ("\n	 p ^ q = false");	
	}
	
		void disjunction(){
		
		string q,p;
		
		cout << "\n 	Disjunction. The disjunction  p or q it true if  p and q are both true, or one of them is true";
		cout<< "\n 	Enter the value of p	";
		cin>>p;
		cout<<"	Enter the value of q	";
		cin>>q;
		
		if( q == "false" && p =="false")
		 {
			cout<<"\n p or q = false";
		}
		
		else cout<< ("\n	 p or q = true");	
	}
	
		void negation(){
			string q;
			cout<<"\n 	Negation. The negation not p means that the value is the opposite of the original value";
			cin>>q;
			
			if(q=="true") cout << "\n	q= false";
			else cout<<"\n q=true";	
		}
		
		void conditional(){
			string q,p;
			cout<<"\n	Conditional. The conditional q then p, written q-->p is false if q is true and p is false";
			cout<< "\n 	Enter the value of p	";
			cin>>p;
			cout<<"	Enter the value of q	";
			cin>>q;
			
			if(p=="true" && q=="false") cout <<"q-->p is false";
			else "q--p is true";
		}
		
		void biconditional(){
			string q,p;
			cout<<"\n	The Biconditional p<-->q is true if both are true or both are false";
			cout<< "\n 	Enter the value of p	";
			cin>>p;
			cout<<"	Enter the value of q	";
			cin>>q;
			
			if((p=="true" && q=="true")||(p=="false" && q=="false"))
			cout << "\n 	The Biconditional p<-->q is true ";
			else cout << "\n 	The Biconditional p<-->q is false ";
		}

main(){
	
	int num;
	cout<<"Choose a number \n 1.Conjunction	2.Disjunction	3.Negation \n 4.Conditional 	5.Biconditional	6.Exit";
	cin >> num;
	
	switch(num){
		case 1: conjunction(); break;
		case 2: disjunction(); break;
		case 3: negation(); break;
		case 4: conditional(); break;
		case 5: biconditional(); break;
		case 6: cout << "Terminated";
	}
	
	
}
