	#include<iostream>
	#include<algorithm>
	using namespace  std;
	int main()
	{
		int t,n,k;
		cin>>t;
		while(t--)
		{
			cin>>n>>k;
			int a[n];
			for(int i=0;i<n;i++)
			{
				cin>>a[i];
				if(a[i]>1 && k>0)
				{
				a[i]=1;k--;
				}
			}
        	sort(a, a+n, greater<int>());	
		if(a[0]>1)
		{
			cout<<"NO"<<endl;
		}
		else{
		cout<<"YES"<<endl;}
		}
	}
