# codes
#include <iostream>
#include<math.h>
using namespace std;

int main() {
	//code
	int t,j;
	cin>>t;
	for(j=0;j<t;j++)
	{
	    int n,i,k,x,count=0;
	    cin>>n>>k;
	    x=n;
	    while(x>=k)
	    {
	        x=x/k;
	        count++;
	    }
	    cout<<pow(k,count)<<endl;
	    
	}
	return 0;
}
