#include<iostream>
#include<string>

using namespace std;

	int set1[100], set2[100], set3[100];
	int c1=0, c2=0, c3=0;
	
	void intersection();
	void print_set(int set[], int size);
	void unite();
	void compliment(string str,int setA[],int setB[], int A, int B);
	void operation(int setA[],int setB[], int A, int B);
	void relative_compliment();
	
main()
{
	int operation;
	int temp=0;

			cout<< "\n Enter the values of first set	";
			for(;;){	
 				cin>> temp;
				if(temp==0) break;
				else{
				set1[c1]=temp;		
				c1++;
				}
		
			}
	

			cout<< "\n Enter the values of second set	";
			for(int a=0; a<100; a++){
				cin>> temp;
				if(temp==0) break;
				else{
				set2[c2]=temp;		
				c2++;
				}
			}
	
			
		 cout<< "SETS OPERATION \n\n\n";
		 cout<< "\n\n The intersection of 2 sets \n";
		 intersection();
		 print_set(set3, c3);
		 unite();
		 compliment("\n\n The complement of set2 to set1",set1,set3,c1,c3); 
		 compliment("\n\n The complement of set1 to set2",set2,set3,c2,c3); 
		 
		 cout<<"\n\nThe relative Compliment of set 1 to set 2\n";
		 print_set(set3, c3);
		 compliment("",set1,set3,c1,c3); 
		 cout<<"\n\nThe relative Compliment of set 1 to set 2\n";
		 print_set(set3, c3);
		 compliment("",set2,set3,c2,c3);
		 
		 cout<<"\n\n the symmetric difference of set1 and set2";
		 compliment("",set1,set3,c1,c3);
		 compliment("",set2,set3,c2,c3);
		 		
}

	void intersection(){		
		for(int a=0; a<c1; a++){
			for(int b=0; b<c2; b++){
				if(set1[a]==set2[b]) {
					set3[c3]=set1[a];
					c3++;
				}
			}
		}
	}
	
	void print_set(int set[], int size){
		for(int a=0; a<size; a++ ){
			cout<<" "<<set[a];
		}
	}
	
	void compliment(string str,int setA[],int setB[], int A, int B){
		cout<<str<<endl;
		operation(setA,setB,A,B);
	}
	
	void operation(int setA[],int setB[], int A, int B){
		int flag=0;
		for(int a=0; a<A; a++){
			for(int b=0; b<B; b++){
				if(setA[a]==setB[b]) flag=1;
			}
			if(flag!=1) cout<< " " << setA[a];
			else flag=0;
		}
	}
	
	void unite(){
		int flag=0;		
		cout<< "\n The union of two sets \n";
		operation(set1,set3,c1,c3);
		print_set(set3, c3);
		operation(set2,set3,c2,c3);
		}
